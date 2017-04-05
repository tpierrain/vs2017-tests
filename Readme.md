# NUnit with VS.NET 2017 


### ClassicNetLibrary
- .NET framework (4.5.2) + NUnit 3.6.1 + NUnit3TestAdapter v 3.7.0 (Windows classic Desktop -> Class Library)
 - via VS (Ctrl+R, A): OK
 - via R# test runner: OK
 - via NCrunch: OK



### NetStandardLibrary
- .NET standard (1.6) + NUnit 3.6.1 + NUnit3TestAdapter v 3.7.0 (Windows Standard -> Class Library)
 - via VS (Ctrl+R, A): __KO - test not detected by the runner__
 - via R# test runner: __KO - test not detected by the runner__
 - via NCrunch: __KO - test not detected by the runner__. It even seems to brake the proper execution of the ClassicNetLibrary project (which works again after removing the NetStandard project ;-)



### DotNetCoreLib
- .NET core app (1.1) + NUnit 3.6.1 + NUnit3TestAdapter v 3.7.0 (Windows Standard -> Class Library)
 - via VS (Ctrl+R, A): __KO - test not detected by the runner__
 - via R# test runner: __KO - test not detected by the runner__
 - via NCrunch: __KO - test not detected by the runner__


# Version used

## .NET versions for the various projects (and how I created those projects)

### .Net Classic
![Classic](https://github.com/tpierrain/vs2017-tests/blob/master/ClassicNetLibrary-How.png?raw=true)
![Classic](https://github.com/tpierrain/vs2017-tests/blob/master/ClassicNetLibrary-Version.png?raw=true)

---

### NetStandardLibrary
![Classic](https://github.com/tpierrain/vs2017-tests/blob/master/NetStandardLibrary-How.png?raw=true)
![Classic](https://github.com/tpierrain/vs2017-tests/blob/master/NetStandardLibrary-Version.png?raw=true)

---

### DotNetCoreLib
![Classic](https://github.com/tpierrain/vs2017-tests/blob/master/DotNetCoreLib-How.png?raw=true)
![Classic](https://github.com/tpierrain/vs2017-tests/blob/master/DotNetCoreLib-Version.png?raw=true)


## Visual Studio

 Microsoft Visual Studio Community 2017
Version 15.0.26228.12 D15RTWSVC
Microsoft .NET Framework
Version 4.6.01586

Installed Version: Community

Visual Basic 2017   00369-60000-00001-AA970
Microsoft Visual Basic 2017

Visual C# 2017   00369-60000-00001-AA970
Microsoft Visual C# 2017

Visual F# 4.1   00369-60000-00001-AA970
Microsoft Visual F# 4.1

ASP.NET and Web Tools 2017   15.0.30223.0
ASP.NET and Web Tools 2017

ASP.NET Web Frameworks and Tools 2017   5.2.50127.0
For additional information, visit https://www.asp.net/

Azure App Service Tools v3.0.0   15.0.30209.0
Azure App Service Tools v3.0.0

Azure Data Lake Node   1.0
This package contains the Data Lake integration nodes for Server Explorer.

Azure Data Lake Tools for Visual Studio   2.2.5000.0
Microsoft Azure Data Lake Tools for Visual Studio

Common Azure Tools   1.9
Provides common services for use by Azure Mobile Services and Microsoft Azure Tools.

Fabric.DiagnosticEvents   1.0
Fabric Diagnostic Events

JavaScript Language Service   2.0
JavaScript Language Service

JavaScript Project System   2.0
JavaScript Project System

JetBrains ReSharper Ultimate 2017.1    Build 108.0.20170402.75312
JetBrains ReSharper Ultimate package for Microsoft Visual Studio. For more information about ReSharper Ultimate, visit http://www.jetbrains.com/resharper. Copyright © 2017 JetBrains, Inc.

KofePackagePackage Extension   1.0
KofePackagePackage Visual Studio Extension Detailed Info

Merq   1.1.13-alpha (2f64b6d)
Command Bus, Event Stream and Async Manager for Visual Studio extensions.

Microsoft Azure Hive Query Language Service   2.2.5000.0
Language service for Hive query

Microsoft Azure Tools   2.9
Microsoft Azure Tools for Microsoft Visual Studio 2017 - v2.9.50131.1

Microsoft MI-Based Debugger   1.0
Provides support for connecting Visual Studio to MI compatible debuggers

Mono Debugging for Visual Studio   Mono.Debugging.VisualStudio
Support for debugging Mono processes with Visual Studio.

NCrunch   
Continuous Testing Tool for .NET
Copyright © 2010-2016 Remco Software Ltd

Node.js Tools   1.3.50201.08
Adds support for developing and debugging Node.js apps in Visual Studio

NuGet Package Manager   4.0.0
NuGet Package Manager in Visual Studio. For more information about NuGet, visit http://docs.nuget.org/.

Redgate SQL Search   2.3.10.1131
Search functionality for SQL Server databases, from within Visual Studio

SQL Server Data Tools   15.1.61702.140
Microsoft SQL Server Data Tools

ToolWindowHostedEditor   1.0
Hosting json editor into a tool window

TypeScript   2.1.5.0
TypeScript tools for Visual Studio

Visual Studio Tools for Apache Cordova   15.113.6201.1
Visual Studio Tools for Apache Cordova

Xamarin   4.3.0.795 (aece090)
Visual Studio extension to enable development for Xamarin.iOS and Xamarin.Android.

Xamarin.Android SDK   7.1.0.43 (3a62f1e)
Xamarin.Android Reference Assemblies and MSBuild support.

Xamarin.iOS and Xamarin.Mac SDK   10.6.0.9 (a05f40e)
Xamarin.iOS and Xamarin.Mac Reference Assemblies and MSBuild support.



## Resharper

JetBrains ReSharper Ultimate 2017.1  Build 108.0.20170402.75312
ReSharper 2017.1.20170403.124732

Application Packages:
JetBrains Platform Core Ide build 108.0.20170402.75312 on 2017-04-02 07:53:16Z rev git::refs/heads/wave08-eap9-rtm::785a59cee420e007b65d9fb37e049a8f7db8a268
.
JetBrains Platform Core Shell build 108.0.20170402.74901 on 2017-04-02 07:49:08Z rev git::refs/heads/wave08-eap9-rtm::ccbb79c9ac0ea5f8f0cc94b4153866d50f1574e2
.
JetBrains Platform Core Text build 108.0.20170402.75312 on 2017-04-02 07:53:16Z rev git::refs/heads/wave08-eap9-rtm::785a59cee420e007b65d9fb37e049a8f7db8a268
.
JetBrains Platform Installer build 108.0.20170402.75312 on 2017-04-02 07:53:16Z rev git::refs/heads/wave08-eap9-rtm::785a59cee420e007b65d9fb37e049a8f7db8a268
.
JetBrains Platform Interop dotMemoryUnit Framework build 108.0.20170402.75312 on 2017-04-02 07:53:16Z rev git::refs/heads/wave08-eap9-rtm::785a59cee420e007b65d9fb37e049a8f7db8a268
.
JetBrains Platform Interop dotMemoryUnit Interop build 108.0.20170402.75312 on 2017-04-02 07:53:16Z rev git::refs/heads/wave08-eap9-rtm::785a59cee420e007b65d9fb37e049a8f7db8a268
.
JetBrains Platform Interop dotMemoryUnit Interop.Ide build 108.0.20170402.75312 on 2017-04-02 07:53:16Z rev git::refs/heads/wave08-eap9-rtm::785a59cee420e007b65d9fb37e049a8f7db8a268
.
JetBrains Platform RdProtocol build 108.0.20170402.75312 on 2017-04-02 07:53:16Z rev git::refs/heads/wave08-eap9-rtm::785a59cee420e007b65d9fb37e049a8f7db8a268
.
JetBrains Platform Symbols build 108.0.20170402.75312 on 2017-04-02 07:53:16Z rev git::refs/heads/wave08-eap9-rtm::785a59cee420e007b65d9fb37e049a8f7db8a268
.
JetBrains Platform VisualStudio build 108.0.20170402.75312 on 2017-04-02 07:53:16Z rev git::refs/heads/wave08-eap9-rtm::785a59cee420e007b65d9fb37e049a8f7db8a268
.
JetBrains Psi.Features Core build 108.0.20170403.124105 on 2017-04-03 12:41:11Z rev git::refs/heads/wave08-eap9-rtm.
JetBrains Psi.Features SolutionBuilder build 108.0.20170403.124105 on 2017-04-03 12:41:11Z rev git::refs/heads/wave08-eap9-rtm.
JetBrains Psi.Features src build 108.0.20170403.124105 on 2017-04-03 12:41:11Z rev git::refs/heads/wave08-eap9-rtm.
JetBrains Psi.Features Tasks build 108.0.20170403.124105 on 2017-04-03 12:41:11Z rev git::refs/heads/wave08-eap9-rtm.
JetBrains Psi.Features UnitTesting build 108.0.20170403.124105 on 2017-04-03 12:41:11Z rev git::refs/heads/wave08-eap9-rtm.
JetBrains Psi.Features VisualStudio build 108.0.20170403.124105 on 2017-04-03 12:41:11Z rev git::refs/heads/wave08-eap9-rtm.
JetBrains ReSharper src build 108.0.20170403.124732 on 2017-04-03 12:47:43Z rev git::refs/heads/wave08-eap9-rtm::7e832fe5921a06430775ae4474ea6a3ac7788412


## NCrunch
For Visual Studio 2017 v. 3.6.0.2

