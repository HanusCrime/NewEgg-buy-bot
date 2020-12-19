# NewEgg-buy-bot
This is a bot that i made for my friend to buy a 30 series card, this started out as just a way for him to get one in his cart but i decided that i should flesh it out and make it go through the entire checkout process.

There are a few things that will need setting up ahead of time to it is reccommended that you do these things before touching the code in any form.

Lets go over the requirements first, 
this bot needs a MOZILLA FIREFOX profile, the esiest way to get one is to just download firefox, and sign in to it, this doesnt need to become your primary browser, but for "newegg" which I am using as an example, you do need to sign and have firefox save your login info.

once you have done the above, go to the search engine and type about:profiles  this will give you the directory that your profile is in, copy the entire line and put it in a new text file for reference.
example: 'C:\Users\name\AppData\Roaming\Mozilla\Firefox\Profiles\61t8zsml.username'

next you will need a link to the specific item you want or the launch page listing all of them, for my example the rtx evga 3070
copy that to the same text file as your directory for reference.

second to last  is two things. you will need your "newegg" password and your credit or debit card cvv, my bot does NOT autromatically put the entire card information in to new egg, just the cvv, this is for your security and piece of mind. Please ensure that new egg has your payment and shipment information already saved to your account to ensure success.

lastly is your IDE, in short, what we will use to run the code, i personally recommend pycharm community edition which you can get here 
https://www.jetbrains.com/pycharm/download/#section=windows
.


<h3>Setup</h3>

run the pycharm installer and set it up to your liking. then create a new project naming it whatever yoou like, next, right click the folder on the left hand side of pycharm, (it should share the same name you named the project), and go to new> python file, and give it a name fitting of a b0t
