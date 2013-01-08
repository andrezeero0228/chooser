.. -*- rst -*-

=======
chooser
=======

----------------------------------------------
select which browser to use when opening a URI
----------------------------------------------

:Author: Lev Givon <lev@columbia.edu>
:Date: 2013-01-08
:Copyright: BSD
:Version: 0.03
:Manual section: 1

SYNOPSIS
========
**chooser** [*URI*]

DESCRIPTION
===========
**chooser** is a graphical utility that enables one to choose which web browser
to use when opening a URI. To invoke the utility when attempting to view a
selected URI, set your default web browser to 

**chooser** %s

CONFIGURATION
=============
By default, **chooser** searches for several common web browsers. One may also
specify which browsers to display in the configuration file
~/.chooserrc as follows:::

    [Browsers]
    Firefox: /usr/bin/firefox
    Chromium: /usr/bin/chromium-browser

SEE ALSO
========
**chromium-browser**\(1), **exo-open**\(1), **firefox**\(1)

BUGS
====
**chooser** might not recognize certain web browsers.