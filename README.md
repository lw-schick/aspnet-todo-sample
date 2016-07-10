ASP.NET Core ToDo Sample
========================

This is a todo list Webservice sample, inspirated by the M$ article [Building Your First Web API with ASP.NET Core MVC and Visual Studio](https://docs.asp.net/en/latest/tutorials/first-web-api.html).

Testing
-------
To test the api, you yust have to:

1. [Install dotnet core](https://www.microsoft.com/net/core)
2. run ``dotnet restore`` on the cli to load all dependencies
3. run ``dotnet run`` on the cli to build and run the web service

the api will run default on http://localhost:5000/api/

You can use the [Boomerang Google Extension](https://chrome.google.com/webstore/detail/boomerang-soap-rest-clien/eipdnjedkpcnlmmdfdkgfpljanehloah) to test the web service. The file \_Boomerang.json contains a set of all currently available api functions.
