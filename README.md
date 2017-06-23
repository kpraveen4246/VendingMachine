Vending machine application for Pillar Technology Application Development kata

The simplest way to compile and run the code in this project is to open the project in Visual Studio, build the project, and run the tests

If Visual Studio isn't an option then a Windows .NET Framework is required.
First download the projec then navigate to your .NET Framework folder, for example:

\Windows\Microsoft.NET\Framework\v4*

Then use MSBuild.exe to compile the solution, for example:

msbuild  "C:\Users\Praveen\Documents\VendingMachine-master\VendingMachine.sln" /t:Build

Running tests without Visual Studio is a very tricky process, if you really want to do it you can follow the guide here:

Otherwise you can install Visual Studio test agent or just Regular Visual Studio.  To run tests outside of the Visual Studio app
you can use MSTest in the Visual Studio Command Line.  Navigate to \VendingMachine\VendingMachineTest\bin\Debug and run the
following command:

MSTest /testcontainer:VendingMachineTest
