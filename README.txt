URL Rewriting Engine README
---------------------------

Change:
	2017-04-18 Upgrade Solution to Visual Studio 2015 and .NET 4.0
	
*******************************************************************************************
This Project is cloned from URL Rewriting in ASP.NET
https://msdn.microsoft.com/en-us/library/ms972974.aspx
*******************************************************************************************
The URLRewritingCode solution is a Visual Studio .NET 2003 Solution file with two projects:

	-- ActionlessForm
	-- URLRewriter

You will need to compile these two projects.

The RewritingTester contains an ASP.NET Web application that can be used to test out the
URL rewriting engine.  You will need to create a virtual directory in IIS named RewriterTest
that maps to the directory where these files exist.
