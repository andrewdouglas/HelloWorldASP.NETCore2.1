# HelloWorldASP.NETCore2.1
Bare-bones ASP.NET Core 2.1 SPA with Vue.js created using "dotnet new vue"

# Prerequisites to running:
- .NET Core 2.1 (runs on Windows, Linux, macOS) https://www.microsoft.com/net/download
- Node.js and npm https://nodejs.org/en/

# To install:
```
git clone https://github.com/andrewdouglas/HelloWorldASP.NETCore2.1
cd HelloWorldASP.NETCore2.1
npm install
npm audit fix
```

# To run:
    dotnet run
Open a browser, and navigate to the URL reported in the command/terminal window e.g. http://localhost:5000.  If Chrome redirects you to https://localhost:5000 and shows a "This site can't be reached" error, in the URL bar of the browser, type chrome://net-internals/#hsts, scroll down to the bottom and in the "Delete domain security policies" section, type localhost and click the Delete button.  Now you should be able to navigate to http://localhost:5000 in Chrome.