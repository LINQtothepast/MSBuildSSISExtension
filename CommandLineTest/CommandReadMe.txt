
//This folder is configured for use with SQL2016, VS2017, .Net 4.7.1

//change directories to whatever folder you plan on running the SSIS build with
cd C:\Users\*YourNameHERE*\Documents\GitHub\MSBuildSSISExtension\CommandLineTest

"C:\Program Files (x86)\Microsoft Visual Studio\2017\Enterprise\MSBuild\15.0\Bin\MSBuild.exe" "./SSIS.MSBuild.proj" /t:SSISBuild /p:SSISProj="SSIS_VS2017_EncryptedWithPassword",password="password" /verbosity:d