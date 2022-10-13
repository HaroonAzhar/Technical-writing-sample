###Problem Summary: 
-Create a new case with data. 
-Add a new tag alongside the new case. 
-The new tag will appear in the site, but the link to that tag is a 404 page 
-Can only be fixed by restarting.

Steps to Reproduce: -Create a new case wih data. -Create a new tag alongside the case; -Go to all tags page and navigate to the the new crreated tag's page.

Investigation results, if any. -Tag an already submited case or create a new one with the newly created tag. -Use a browser to access the tag URL. -Receive a 200 (OK.), tag appears now when assigned to any other additional cases. -Attempt to reproduce i.e create case without new tag Again: 1)Delete the tag from the case and re-publish it without the newly created tag again. 2).Use a browser to access the tag URL. 3)Receive a 404 (Page not found.) -> Although tag does exist

Vesrion and Engine: { "node": ">=10.16.0 <=14.x.x", "npm": ">=6.0.0" },

Relevant log / error output: -No error and log -undesired output of blank tag page.
