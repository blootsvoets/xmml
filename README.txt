The xMML format, version 0.3.2
==============================

The xMML format is documented in xmml.dtd and xmml.xsd. Two examples 
implementing the specification are given: isr_xmml.xml and canal.xml.

With the scripts in the bin directory certain tasks are eased.
* bin/validate: call to validate an xmml file, which must be in the
  same directory as xmml.dtd. With two arguments, it performes
  XInclude and saves the result in the second file.
* bin/mkrelease: call with a version number to have a release of that
  version put in the release directory
* bin/dtd2xsd.pl: call to convert xmml.dtd to xmml.xsd
