# #100DaysOfCode Log - Round 1 - [Hanif Warren]

The log of my #100DaysOfCode challenge. Started on [May 29, Tuesday, 2018].

## Log

### R1D1 
5/29/18
Restarted 100 days of code to honor it. I didn't want to continue with so many missed days of compliance. 
I did some work on my portfolio site. It's challenging because I'm not super well versed in bootstrap, but I managed to get a nice bulleted list looking right.
The hour ran out just as I was getting in my groove. I decided to take the moment to log my progress, save it in Github, and then tweet all about it.
It feels good, the missteps are part of the progress, and each time I end with more prettier apps.

Todo:
upload contacts app and database to my site, add to modal on my portfolio site
Add database to blog (it's already empty so it's not necessary to do anything.
Start blogging (take progress here and blog about it on my blog site)

Link to work:
https://github.com/hawarren/HWFirstPersonalSite/commit/bb5493855bb168ab9777711f42d6c1de151804c5

### R1D2 
5/30/18
Fixed some links to my portfolio, also decided to add my outstanding bugs from all my projects to my bugtracker. Ran into a stupid problem where rutgers wifi was blocking my connection to my database, and it took me a while to figure out it was them (once I switched to tethering my phone it worked out).
I'm constantly amazed at the number of snafus that turn up that aren't even directly related to what I set out to do that day. It's crazy when something that worked yesterday stops working today. But it's also a test of confidence and being detail oriented, because I need to be sure that I did things right, before I can confidently say the problem isn't with me. I also found some cool resources for checking my connection string.
Link to work:
https://github.com/hawarren/HWProductionBlog/commit/a3c34399a39803a89d0d97265d1459eaf4e8213e
https://github.com/hawarren/BugTrackerV3/commit/ac6fccc5ed0be5ab0b73600b4491cc7f593cdc30

### R1D3 
5/31/18
Worked on contacts up, I am refactoring the multiselectlist, I ran into a problem using the directive, so I embedded it into the my application module. It still runs, so next step is to bring it into my app.
It's fun making stuff work. Instead of getting stuck, I compromised so that I could move on.
I can always refactor later 
I also realized that the previous “object reference not set to an object” error was probably from not using the => lambda function.


### R1D4 
6/1/18
Fully refactored the Angularjs dropdownmenu, and changed the variable names to more smoothly fit into my contacts app. Unfortunately, it didn't quite work when I tried to plug it in. It's strange, because I was fairly confident that I had it all together, yet I'm not sure why it's not working. I also need to learn how to use the debugger a little better. But I definitely made real progress!
Link to work:
https://github.com/hawarren/MULTI_SELECT_DROP_DOWN_LIST/commit/e9cec8ac8bfce966f62d9f05023123bc4bef5d51

### R1D5 
6/2/18
Messing around with this multiselectlist. I really don't understand why my refactored version works, but I can't even drop the files in the app and have them work.

### R1D6 
6/3/18
More messing around with the multiselectlist. At this point, I need to read more documentation so that I understand what works and why. Because I've gotten as far as my limited understanding will take me.

### R1D7 
6/4/18
Figured out part of the issue, the library relies on an older version of jQuery  (3.3.1) and bootstrap (3.3.7)
When I switched the libraries in the standalone dropdownlist, it stopped working. so that means I need to match the libraries at the very least before I port it over. It's been a real learning experience.
I've spent countless hours on this, but I'm not tired or discouraged. Annoyed that I'm still on this, but I'm very determined nonetheless.

### R1D8 
6/5/18
Finally fixed my portfolio! I really sat down and resolved to address some lingering issues, and before I knew it, I was fixing and tweaking multiple things and went way past my "hour" of code. Now my landing page is published and I'm actually proud to show it to people!
The pride of shipping is very real. I love it.
Links to work:
https://github.com/hawarren/HWFirstPersonalSite/commit/70f313c83b1a26164b7a1bc3f9246010527af00a
