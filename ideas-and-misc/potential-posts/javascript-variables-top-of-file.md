I was going through a book on node recently and came across something very unfamiliar. Usually, a quick Google search will resolve and clarify any questions or misconceptions, but this one had me stumped. Partially because I didn't really even know if I was searching for it the right way. 

So what was my problem? I came across this line in a node tutorial: 

```
var querystring = require('querystring'), fa = require('fa'), formidable = require('formidable');
```
 
Now you may know exactly what is happening here. I know I felt pretty dumb once I finally was able to figure it out, but at the time, I wasn't even sure how to search for it!  I am used to node files having the large list of requires at the top and I t seemed that was what was going on, but I was not sure why. It goes to show that if we do not use a technique, it can be forgotten. I have almost always seen it written on multiple lines: 

```
var querystring = require('querystring')
fa = require('fa')
formidable = require('formidable');
```

As I said, I knew the program was working how I was expecting it to function, but I wasn't sure why. Additionally, all my searches were not returning anywhere close to the answer I wanted. I knew this was a test, a challenge to my Google Fu, so I kept changing my searches, trying to find the answer to my question. Eventually, I came across [this stackoverflow question](http://stackoverflow.com/questions/21619413/comma-separation-in-javascript]. 

As I read the article, I remembered back to when I first started learning javascript that variables can all be declared on one line by comma separating them. I am not sure have seen this done in a project since that first time, till now. Personally, I prefer to separate by new lines. I don't have a great reason for it, but it just 'feels better' to me. 

No matter how others choose to declare their requirements, I know I will not forget it for the next time I see it in a project!
