# MSBuildSSISExtension

For more information on this project please refer to this blog post:
"Insert URL Here"

Feel free to Fork this code or submit issues that you have with the code. I am more than willing to answer and questions or fix anything that is wrong with my code. If you wish to contribute feel free to email me at LINQtothepast@gmail.com and we can talk.

DLLProjects contains various versions of working solutions that when build will work with what is specified in the pathing of the folder. For instance VS2017/SQL2016/DotNet471/ would expect the SSIS project to be built using Visual Studio 2017, targetting SQL Server 2016, and be built using the .Net Framework 4.7.1

TestProjects contains simple SSIS projects. These projects use the password "password" if you wish to use them to test the MSBuild extension. The current project in there uses "EncryptedWithPassword" levels of protection but the actual project is empty otherwise.

CommandLineTest contains all of the files needed in order to try out this project and see the end result. In order for it to work on your machine, you will need SQL Server Management Studio, SQL Server 2016, and SSDT 2017 installed. Or you will need all of the DLLs present in one shape or another.
