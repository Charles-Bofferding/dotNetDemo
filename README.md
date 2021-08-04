## Lab 17: Identity
THe main thrust of this lab was to have a site deplyed through your azuure account which can connect to a test database, run tests, and succesfully run API commands

## The Caveat
So obviously this should be done on further work from my previous Async Inn labs. I think that this morning while going through some code I realized that I had
created the controllers incorectly and that because of that they were not routing any information. WEhile not knowing that I started going into my code and overwriting things
along the way that I think made compounding errors. John sent out a slack message saying that if your code wasn't running to use the demo code as a base and deploy that. Soooo yeah, 
I did that so I could have time to sleep tonight.

Also if you were wondering the IP issues eventually got fixed through some scary stuff but because of the broken controllers I didn't realize it fully. The second reply to the
stack overflow question below was incredibly helpful on how to modufy the settings by haviong to unmount the project, fidle with config files, then put everything back.
https://stackoverflow.com/questions/21202885/how-can-i-change-iis-express-port-for-a-site

Still working on the other code but I think I might need to do a fresh start, there are to many fixes for non-existant problems layered on each other.

## Azure deployed site URL
https://schoolapi20210803213401.azurewebsites.net/index.html

## Code base from class repository
https://github.com/codefellows/seattle-dotnet-401n13/tree/main/class-17/demo/SchoolAPI