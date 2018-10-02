APIs Coding Against the Web
================
Steven M. Mortimer
10/25/2018

-   [Background](#background)
    -   [What Makes a SOAP API?](#what-makes-a-soap-api)
    -   [What Makes a REST API?](#what-makes-a-rest-api)
    -   [Comparing XML and JSON](#comparing-xml-and-json)
    -   [Setting up R for API work](#setting-up-r-for-api-work)
    -   [Methods to Authenticate](#methods-to-authenticate)
    -   [Becoming Familiar with HTTP Status Codes](#becoming-familiar-with-http-status-codes)
-   [The Open Movie Database API](#the-open-movie-database-api)
    -   [Authenticating](#authenticating)
    -   [Request and Parse XML](#request-and-parse-xml)
    -   [Request and Parse JSON](#request-and-parse-json)
    -   [Summary](#summary)
-   [The Square APIs](#the-square-apis)
    -   [Authenticating to Square APIs](#authenticating-to-square-apis)
    -   [Making a call](#making-a-call)

Background
==========

What Makes a SOAP API?
----------------------

SOAP Simple Object Access Protocol Protocol agnostic (HTTP, SMTP, TCP, or JMS) Almost always XML Definitions provided by WSDL (Web Service Description Language)

Resources: The Difference Between SOAP and REST SOAP vs REST Challenges

What Makes a REST API?
----------------------

REST Representational State Transfer (principles, client not server controlled state) Noun-Verb Paradigm (HTTP GET/POST/PUT/DELETE) Almost always JSON (Javascript Object Notation)

Comparing XML and JSON
----------------------

Setting up R for API work
-------------------------

tidyverse dplyr, purrr, tidyr automatically loaded

library(httr) library(xml2) library(jsonlite)

one non-tidy package library(XML)

Methods to Authenticate
-----------------------

Becoming Familiar with HTTP Status Codes
----------------------------------------

2XX - success! 4XX - your fault! 5XX - their fault!

The Open Movie Database API
===========================

Authenticating
--------------

Request and Parse XML
---------------------

Request and Parse JSON
----------------------

Summary
-------

The Square APIs
===============

Authenticating to Square APIs
-----------------------------

Making a call
-------------
