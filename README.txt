Welcome to Talend Service Factory Community Edition!
====================================================

Talend Service Factory Community Edition (CE) uses the industry leading 
open source Apache CXF implementation of JAX-WS to help you service enable 
your existing applications and interfaces.  The CXF lightweight, modular 
architecture is based on Spring, so it will work with your application 
regardless of the platform on which it is running.  It will run on 
stand-alone JVM applications, as part of a servlet container such as 
Tomcat, within a JEE server, or in an OSGi container such as Equinox.  

CXF supports Web Services using SOAP with full WS-*functionality including 
support for WS-Addressing, WS-Reliable Messaging, and WS-Security over 
both HTTP and JMS transports.  CXF's elegantly simple architecture allows 
declarative, policy-centric support of these qualities of service through 
configuration rather than code.  It also supports non-SOAP bindings 
including REST.  CXF open standards and portability enable you to deliver 
interoperability for your applications to maximize the value of your 
application to your users.  

The Talend Service Factory CE distribution supplements the Apache CXF 
core with support for OSGi containers along with illustrative examples 
for how to implement different messaging qualities of service in different 
container environments.  CXF design-tools include support for Maven 
plug-ins, WSDL tooling, and Spring 2.x XML configuration support.  TSF 
supplements this with additional Maven archetypes to support development 
in an OSGi environment.


Contents 
======== 

Apache CXF
OSGi Container
Getting Started
Examples

Apache CXF
==========

This package contains a complete version of Apache CXF, the industry 
leading open source solution for web services.  It also includes value
added components such as OSGi container and several new examples.
For more information about Apache CXF see http://cxf.apache.org/ .  


OSGi container 
============== 

The container subdirectory contains a preconfigured OSGi container that 
contains all the required OSGi bundles for the CXF 3rd party dependencies.
It also includes Apache Karaf to provide easy administration and 
configuration.  See the karaf-manual pdf file in the container directory 
for more information about Karaf.  For more information about OSGi and Apache 
Karaf see http://karaf.apache.org/ .

OSGi provides a mature, open standards based, highly modular framework for 
managing component dependencies, service invocation, and lifecycles.  It is 
the basis for Eclipse and provides a lightweight alternative to more 
monolithic JEE containers while still retaining the powerful management 
features necessary for the enterprise.


Lean Java 6 Distribution 
======================== 

The Talend Service Factory CE has been tuned for operation with Java 6.
lib/ - the contents of the lib directory have been optimized for use on 
Java 6.  Jars that are redundant to what is available in Java 6 have been 
removed.



Getting Started 
===============

For information on running the Talend Service Factory OSGi container, 
check the README file in the container folder just below this directory.

If you need more help try talking to us on our forums: http://talendforge.org/forum

You can find more information about Apache CXF at http://cxf.apache.org/

Please submit CXF bug reports with JIRA at https://issues.apache.org/jira/browse/CXF 

Please submit TSF bug reports with JIRA at https://jira.sopera.de/browse/SF

Examples are documented individually and include instructions for building
and running each example with just a few command lines.  See below for obtaining 
the examples.


Examples 
======== 

Talend Service Factory CE provides several new examples in a separate download
available from http://www.talend.com/resources/documentation.php#SF .  The 
example applications and tutorials demonstrate functionality and advanced 
features of Talend Service Factory CE.  The examples demonstrate how to use 
different functionality including:
* Advanced JAX-RS
* multi-platform deployment to JVM / Servlet / JEE Containers / OSGi
* asynchronous messaging
* Various WS-Security options      


Export Notice 
=============

This distribution includes cryptographic software.  The country in which 
you currently reside may have restrictions on the import, possession, use,
and/or re-export to another country, of encryption software.  BEFORE using
any encryption software, please check your country's laws, regulations and 
policies concerning the import, possession, or use, and re-export of 
encryption software, to see if this is permitted.  See 
<http://www.wassenaar.org/> for more information.  

The U.S. Government Department of Commerce, Bureau of Industry and Security 
(BIS), has classified this software as Export Commodity Control Number 
(ECCN) 5D002.C.1, which includes information security software using or
performing cryptographic functions with asymmetric algorithms.  The form 
and manner of this Apache Software Foundation distribution makes it eligible
for export under the License Exception ENC Technology Software Unrestricted 
(TSU) exception (see the BIS Export Administration Regulations, Section 
740.13) for both object code and source code.


