# PI-Alexa-NodeRED
Connecting Amazon Echo with time-series data platform OSIsoft PI System via NodeRED

## Overview
This project and tutorial show connecting to Amazon's Alexa service with the OSIsoft PI System.

## Pre-Reqs
* Working Node-RED installation that is accessible from an external source
     * With a certificate issued by a trusted authority
     * I recommend using IBM Bluemix to host Node-RED.
     * This tutorial was written and tested using a Bluemix hosted Node-RED instance.  You may need to make your own adaptations to these instructions if you are not using Bluemix.
     * Bluemix can be tried without credit card for 30 days.  They also offer free service for those running one instance using 512 MB (or less) with the minimal services (requires credit card, but you will not be charged as long as you stay under the limits of all of the services). Instructions for setting up Bluemix can be found at: https://github.com/langanjp/PI-Alexa-NodeRED/wiki/IBM-Bluemix-Setup
* OSIsoft PI Web API Server that can be accessed by you Node-RED instance
     * Version 2016 or greater
     * Ideally with a certificate from a trusted authority
