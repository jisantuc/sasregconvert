sasregconvert
=============

Lightweight lib for converting SAS regression output to other table formats


##Overview

SAS regression output in text or Excel form is ugly/requires a lot of processing if you want to put a journal-quality regression table into something else. This library reads in SAS output in text, excel, or csv, and allows conversion to .tex (default) or .xlsx (if for some reason you absolutely *must* use Word in output).

Dependencies: python 2.7+ and pandas

Short-run to-do:

- generate some SAS regression output from OLS and put it in examples
- write SASregoutput class
