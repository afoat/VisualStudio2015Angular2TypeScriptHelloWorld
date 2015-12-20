This is a Visual Studio 2015 / Node. JS Implementation of the 5 Minute Quick Start for Angular 2 (beta) and Type Script.

https://angular.io/docs/ts/latest/quickstart.html

It took me forever to get the details worked out so hopefully this might save someone some time.

1) Install Node.JS Tools for Visual Studio - https://www.visualstudio.com/en-us/features/node-js-vs.aspx
2) Clone or fork this git: https://github.com/afoat/VisualStudio2015Angular2TypeScriptHelloWorld.git
3) Open up the solution in visual studio
4) Right click on the npm node found under the VisualStudo2015Angular2TypeScriptHelloWorld project (where nuget would be in an asp.net project) and select install missing npm package 
5) Open a visual studio command prompt - navigate to the folder that contains the njsproj project file.
6) run the command 'npm start' - this will compile the app and launch a browser to the index.html file in the project. Compiler stays open and watches for changes to make for an easier workflow.

Please let me know if you run in to any problems.
