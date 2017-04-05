# NUnit with VS.NET 2017 


### ClassicNetLibrary
- .NET framework (4.5.2) + NUnit 3.6.1 + NUnit3TestAdapter v 3.7.0 (Windows classic Desktop -> Class Library)
 - via VS (Ctrl+R, A): OK
 - via R# test runner: OK
 - via NCrunch: OK



### NetStandardLibrary
- .NET standard (1.6) + NUnit 3.6.1 + NUnit3TestAdapter v 3.7.0 (Windows Standard -> Class Library)
 - via VS (Ctrl+R, A): __KO__ test not detected by the runner
 - via R# test runner: __KO__ test not detected by the runner
 - via NCrunch: __KO__ - test not detected by the runner. It even seems to brake the proper execution of the ClassicNetLibrary project (which works again after removing the NetStandard project ;-)



### DotNetCoreLib
- .NET core app (1.1) + NUnit 3.6.1 + NUnit3TestAdapter v 3.7.0 (Windows Standard -> Class Library)
 - via VS (Ctrl+R, A): __KO__ test not detected by the runner
 - via R# test runner: __KO__ test not detected by the runner
 - via NCrunch: __KO__ test not detected by the runner





