# Homebridge Lutron Caseta

[![Build Status](https://semaphoreci.com/api/v1/jcoleman/homebridge-lutron-caseta/branches/master/badge.svg)](https://semaphoreci.com/jcoleman/homebridge-lutron-caseta)

tl;dr: A Homebridge plugin for integration with the Lutron Caseta Smart Bridge Pro.

Primary motivation:

Lutron doesn't expose its versatile Pico remotes as HomeKit accessories so it's not possiboe to use them to comtrol non-Lutron accessories.

Hoever the Smart Bridge Pro allows connections over telnet via the Lutron Integration Protocol. This connection allows direct comtrol of accessories, and, more critically for our purposes, streams notifications of Pico button presses.
