# What is This?

The initial script is Taken from Rob Conery's post on [Creating a Massively Scalable Wordpress Site on Azure's Hosted Bits](https://rob.conery.io/2019/01/09/creating-a-massively-scalable-wordpress-site-on-azures-hosted-bits/). There were a few shortcomings to this script, and I felt a moment of insanity so I decided to modify a few things.

## Changes
 - PHP Settings

 By default PHP has an abysmally small maximum upload which will prevent the upload of quite a few Wordpress themes / plugins that need to be uploaded this way. (Purchased themes and plugins sometimes require upload).

 - Wordpress Volume
 
 Mounting the Wordpress Volume may prove useful