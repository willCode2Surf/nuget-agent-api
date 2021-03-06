nuget-agent-api
===================

The New Relic .NET Agent API supports custom error and metric reporting, and custom transaction parameters. If the agent is not installed or is disabled, method invocations of this API will have no effect. You can find more information about the NewRelic.Agent.Api at http://newrelic.com/docs/dotnet/AgentApi. This is for the ANY CPU build of the .NET Agent API


Install
---------------

	PM> Install-Package NewRelic.Agent.Api

Contribute
===========================


Setting up your local environment to contribute
---------------------------------
1. Open visual studio
2. Tools menu >> Library Package Manager >> Package manager settings
3. Under the Package Manager, click on Package sources
4. Create a source named "Local" and set the directory to where you cloned the repository (something like "c:\code\nuget-agent-api")
5. Click Add then "OK"

Using the package locally
-----------------------------
1.  To use it you can open up your web app and choose >> tools >> Library Package Manager >> Package manager console
2.  In the console make sure that the source drop down is set to local
3.  Then type in "Install-Package NewRelic.Agent.Api"
4.  Hit enter

Pull requests
--------------------
1. [Fork the repository](https://help.github.com/articles/fork-a-repo)
2. Add awesome code or fix an [issue](https://github.com/newrelic/nuget-agent-api/issues) with awesome code
3. [Submit a pull request](https://github.com/newrelic/nuget-agent-api/pulls)