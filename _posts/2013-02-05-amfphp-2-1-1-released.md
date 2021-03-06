---
layout: post
title: AmfPHP 2.1.1 Released

type: post
parent_id: '0'
published: true
password: ''
status: publish
categories:
- Blog amfPHP
- The Blog
tags: []

layout_header: "- Select -"
_epLastError: ''
_epLastMessage: ''
_edit_last: '10'
_itemCurrentVersion: ''
wpautop: "- Select -"
skin: "- Select -"
_thumbnail_id: '135923'

display_name: Ariel Sommeria-Klein
first_name: Ariel
last_name: Sommeria-Klein
permalink: "/amfphp-2-1-1-released/"
---

Silex Labs is as always proud to present the latest and greatest version of AmfPHP, **AmfPHP 2.1.1**. AmfPHP 2.1 Generator was a big step forward, and this release is full of improvements building on that foundation.

Here are the main
changes: 
*   The **Service Browser** has been **reworked** to allow you to better work with your services and your data. There are now multiple ways to view data, and scrolling has been reduced to a minimum.
*   A brand new **Flex Client Generator**
*   The **Backoffice** can now be put **online **as it is by default **login protected**
*   An **example** for **Authentification services.  
    **

Many thanks to the community for its continued support!

The Silex Labs team.

[Get it here!](https://www.silexlabs.org/amfphp/downloads/ "Downloads")

See Below for the full Change Log.

Flex Client Generator

example services for Authentication and User management with a Database(PHP Only)

authenticated back office

change AmfphpAuthentication session storage structure. might break some code in some projects, check on it

improved AMF version detection

support for static service methods

add composer.json for use with http://getcomposer.org

generate zip of generated project

in service
browser: 
various ways to view result data including tree

improved use of scroll position

fix passing JSON objects

fix step by step debugging by removing dependency on curl and using included request plugin instead