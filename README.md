openmrs-atomfeed-publisher
==========================

[![Build Status](https://travis-ci.org/ICT4H/openmrs-atomfeed-publisher.png)](https://travis-ci.org/ICT4H/openmrs-atomfeed-publisher)

AtomFeed Publisher Module For OpenMrs.

What it does
===========================

Publishes an event for every Drug Regimen create/update. It publishes the drug regimen details such as medicines and 
frequency of dosages.

Why
===========================

This module is built to demonstrate how events can be broadcasted using the ATOM protocol.

Dependencies
===========================

This module depends on the OpemMRS event module to intercept events. 
This uses [the atomfeed module](https://github.com/ICT4H/atomfeed) to publish events.
