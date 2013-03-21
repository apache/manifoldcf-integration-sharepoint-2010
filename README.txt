# Licensed to the Apache Software Foundation (ASF) under one or more
# contributor license agreements.  See the NOTICE file distributed with
# this work for additional information regarding copyright ownership.
# The ASF licenses this file to You under the Apache License, Version 2.0
# (the "License"); you may not use this file except in compliance with
# the License.  You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.


Instructions for Building Apache ManifoldCF Plugin for SharePoint 2010 from Source
-------------------------------------------------------------------------------

This source MUST be built on a Windows system.

1. Make sure you have .NET Framework 1.0 and .NET Framework 3.0 installed.

2. Place the Microsoft SharePoint 2010 dll in the right place, you can take this file from C:\Program Files\Common Files\Microsoft Shared\Web Server Extensions\14\UserCode\assemblies.  There are several places
   that will work.  The preferred place is:
   
   C:\Program Files\Reference Assemblies\Microsoft\Framework\v3.5\Microsoft.SharePoint.dll
   
3. Download the Java SE 5 JDK (Java Development Kit), or greater, from http://www.oracle.com/technetwork/java/index.html.
   You will need the JDK installed, and the %JAVA_HOME%\bin directory included
   on your command path.  To test this, issue a "java -version" command from your
   shell and verify that the Java version is 1.5 or greater.

4. Download the Apache Ant binary distribution (1.7.0 or greater) from http://ant.apache.org.
   You will need Ant installed and the %ANT_HOME%\bin directory included on your
   command path.  To test this, issue a "ant -version" command from your
   shell and verify that Ant is available.

5. In a shell, change to the root directory of the source (where you find the outermost
   build.xml file), and type "ant" for directions.


Some Files Included In Apache ManifoldCF Plugin for SharePoint 2010 Distributions
------------------------------------------------------------------------------

dist/MetaCarta.SharePoint.MCPermissionsService.wsp
  The Apache ManifoldCF Plugin for SharePoint 2010 assembly.

Licensing
---------

Apache ManifoldCF SharePoint 2010 Plugin is licensed under the
Apache License 2.0. See the files called LICENSE.txt and NOTICE.txt
for more information.

Cryptographic Software Notice
-----------------------------

This distribution may include software that has been designed for use
with cryptographic software. The country in which you currently reside
may have restrictions on the import, possession, use, and/or re-export
to another country, of encryption software. BEFORE using any encryption
software, please check your country's laws, regulations and policies
concerning the import, possession, or use, and re-export of encryption
software, to see if this is permitted. See <http://www.wassenaar.org/>
for more information.

The U.S. Government Department of Commerce, Bureau of Industry and
Security (BIS), has classified this software as Export Commodity
Control Number (ECCN) 5D002.C.1, which includes information security
software using or performing cryptographic functions with asymmetric
algorithms. The form and manner of this Apache Software Foundation
distribution makes it eligible for export under the License Exception
ENC Technology Software Unrestricted (TSU) exception (see the BIS
Export Administration Regulations, Section 740.13) for both object
code and source code.

The following provides more details on the included software that
may be subject to export controls on cryptographic software:

  The Apache ManifoldCF Plugin for SharePoint 2010 
  does not include any implementation or usage of cryptographic software
  at this time.
  
Contact
--------

  o For general information visit the main project site at
    http://manifoldcf.apache.org

