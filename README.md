xsd2
====

Improved version of xsd.exe.

This version enables:

* List based collections in generated types
* Auto-capitalization of properties
* Nullable attribute types
* Removal of DebuggerStepThrough attribute

Usage:
xsd2.exe &lt;schema file&gt; [/o:&lt;output-directory&gt;] [/ns:&lt;namespace&gt;] /all

New Option for metro style application
/m
/metro - This will filter attributes and elements not supported by metro applications. (SerializableAttribute and CategoryAttribute and rewrite AttributeAttribute)


Notes:

* [PetaTest](http://www.toptensoftware.com/petatest/) framework is used for testing.
* Original idea http://mikehadlow.blogspot.com/2007/01/writing-your-own-xsdexe.html.
