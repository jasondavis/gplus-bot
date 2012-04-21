# Google Plus status update bot

* Readme date: Dec 15 2011
* Contributors: lukapusic
* Author: Luka Pusic <luka@pusic.si>
* URI: http://360percents.com/posts/first-google-google-plus-status-update-bot-in-php/

## Description
This bot can log into your Google account and update your Google Plus status,
but you can extend it to other Google products. All this is done without Google API,
OAuth, tokens or any other annoying products.

## System requirements
* PHP curl extension

## Instructions
1. Copy config.sh.example to config.sh, open config.sh and edit email and password
2. run it ```source config.sh && php gplus.php```

## Changelog

#### Nov 11 2011
* added debug parameter, pageid parameter, pc_uagent parameter
* page updating still not implemented

#### Nov 16 2011
* changed the way baseurl is determined, google removed base href

#### Dec 15 2012
* post visibility is not public by default

## Known issues
* fails if you didn't confirm mobile location terms and conditions
* fails if you have mobile verification enabled

## TODO
* add an option to change post visility
* add posting to pages
* add page links

## License
 ----------------------------------------------------------------------------
 "THE BEER-WARE LICENSE" (Revision 42):
 <luka@pusic.si> wrote this file. As long as you retain this notice you
 can do whatever you want with this stuff. If we meet some day, and you think
 this stuff is worth it, you can buy me a beer in return. Luka Pusic
 ----------------------------------------------------------------------------
