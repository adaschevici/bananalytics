# visitors
This is an idea i have about writing a really lightweigth tool for monitoring traffic on the intranet.

Why: piwik - really bulky
     visitors - c, does not really do what I need and does not provide a rest interface, is paid
                has a nice name which I will borrow and emulate some aka most of the functionality [here](https://github.com/antirez/visitors)

What: twisted plugin to monitor things based on the server logs(configurable)
      No database
      No aditional configuration
      Just deploy and it should work based on the rules defined
      
Another thought, even better: Golang -> build, upload and it works 
