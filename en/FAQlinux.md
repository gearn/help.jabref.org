---
title: JabRef and Linux
helpCategories: ["FAQ"]
---

# JabRef and Linux

## Q: JabRef does not start under Linux! What can I do?

JabRef requires at least Java 8.
Please follow the steps provided on our [installation page](Installation).

## Q: I am on Debian/Ubuntu and clicking on the JabRef icon works, but I cannot start JabRef from the command line. What is wrong?

A: You have several Java Virtual Machines installed, and under the command line the wrong one is chosen.
Have a look at the previous question that tells you how to change the virtual machine used.

For Ubuntu you may also have a look at the [Ubuntu page on Java](https://help.ubuntu.com/community/Java).


## Q: Does JabRef run under free Java (Classpath, Kaffee, GCJ, etc.)?

A: As far as we know, JabRef is not yet running on these free JVMs, due of our dependencies.
However, JabRef is reported to run nicely on the [IcedTea](http://fedoraproject.org/wiki/Features/IcedTea) runtime, which is based on the [OpenJDK](http://openjdk.java.net/) built with [GNU Classpath](http://www.gnu.org/software/classpath/) to fill in missing classes.
Some issues have been encountered with the LookAndFell (see issues [#393](https://github.com/JabRef/jabref/issues/393) and [#2003](https://github.com/JabRef/jabref/issues/2003)).
Please let us know if newer versions give different results.
If you have an idea or the expertise to make JabRef work under Classpath, let us know.
