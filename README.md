Console Application (WinRT) Template
====================================

Huh?
----
It's a simple project template for creating a (C#) command-line application, with access to WinRT APIs.

Does that even work?
--------------------
Well right now, not many WinRT APIs work outside an Package/AppContainer context. So things like MessageDialog are broken. But hey, it's a start!

How do I rebuild this?
----------------------
Due to the current state of Visual Studio "11" tooling, I used:
* Visual Studio 2010 SP1
* [Visual Studio 2010 SP1 SDK](http://www.microsoft.com/en-us/download/details.aspx?id=21835)

(Then I built a simple VSIX and edited the project file to target Visual Studio "11")