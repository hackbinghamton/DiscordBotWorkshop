# Intents

Intents helped create a new way in which Discord Bots are created. Essentially, [Intents](https://discordpy.readthedocs.io/en/stable/intents.html#) allow your Discord bots to gain access to specific event functions. These functions can allow your bots to have access to many features, thus increasing the capabilites of your Bots!

## Necessary Intents?

With the potential uses of Intents, you may wonder which Intents are necessary for your code to run. Ultimately, the choice is up to you! What is deemed as a ["necessary" intent](https://discordpy.readthedocs.io/en/stable/intents.html#what-intents-are-needed) boils down to the functionality of your Discord Bot and what its capabilities should and should not have access to! You may wish to have your bot respond to when certain events occur or to ignore less important events that are happening.

## Privledged Intents

Some Intents are restricted and require you to maunally allow the Discord Bots to use, which is known as a [privleged intent](https://discordpy.readthedocs.io/en/stable/intents.html#privileged-intents). Allowing access to such privleges requires some manual input. Go to the Application Page on Discord's website. Then select your bot that you would like to give access to. Then scroll until you see "Privleged Gateway Intents" and select the ones you wish your Disocrd Bot to have enabled. Again, which Intents you give access to your Discord Bot should correlate to what information it needs to be fully functional!

### Presence Intent

[Presence Intent](https://discordpy.readthedocs.io/en/stable/intents.html#presence-intent) functions pertain to the activity of members of the server. These types of functions could keep track of statuses or recent activities of members

### Member Intent

[Member Intent](https://discordpy.readthedocs.io/en/stable/intents.html#member-intent) functions help track certain information about specific members. Functions can include seeign whether members join/leave a server or if a member's username or roles change throughout some time!

### Message Intent

[Message Intent](https://discordpy.readthedocs.io/en/stable/intents.html#message-content) functions can used to evaluate messages sent my members. From checking embedded messages to the content of attachments and text, these functions provide utility for your bots.

## Member Cache

[Member caches](https://discordpy.readthedocs.io/en/stable/intents.html#member-cache) are more restrictive due to Intents, but there are many functions that help limit member cache. As a Discord Bot author, its your responsibility to cache as little as possible, especially surrounding these members.

## Retrieving Members

[Retrieving Memebers](https://discordpy.readthedocs.io/en/stable/intents.html#retrieving-members) can be quite difficult if caching is not available. There are some library functions that can help large numbers of members or even search for specific members thorugh IDs or usernames


Intents can offer a wide variety of utility for your Disocrd Bots, so experiment on various ways to make them more efficient and capable for your future server endeavors!