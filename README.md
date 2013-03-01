Eclipse Snippets
================

Collection of code snippets that I use in Eclipse. Code snippets are in Java, mainly focused on Android.

Installation
------------

Note: instructions are inspired by [this page](http://boulderinformationservices.wordpress.com/2011/05/13/share-eclipse-snippets-among-workspaces-or-even-different-computers/), and are for Windows only. This principle will also work on Mac and Linux, but there's a different command for making links.

1. Clone this git repo
2. Link the user.xml file to your workspace using this command (run in elevated command prompt):
	```mklink /H "C:\users\username\path\to\workspace\.metadata\.plugins\org.eclipse.wst.common.snippets\user.xml" "C:\path\to\git\repo\user.xml"
3. Go!