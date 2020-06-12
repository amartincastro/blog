## API Basic with Postman

 LEARNING THE HARD WAY: API basics with Postman 

I am going to use Github’s Noop Challenge — Hexbot to teach y’all about one of biggest tools in my API toolbelt, Postman.

If you’ve never used an API before in your entire life, it’s cool. This is for you bb

Github is doing this programming challenge call NOOP which basically means functions that do nothing. It’s stuff that has no purpose. We are just dorking around for the sake of it. I love it. We are going to use @github’s web-exposed API for their first challenge, Hexbot, to try out Postman.

Here’s the Hexbot NOOP challenge: https://noopschallenge.com/challenges/hexbot

I am not going to explain what an API is, or why you should care, or any of that. You don’t care. I don’t care. Nothing matters, everything is pain.

Let’s just talk to the API, yeah? First let’s download Postman. Postman is free software that lets you test APIs. You can test other people’s public APIs, like we will do today.

You can also use it to test APIs you make, and even to automate the documentation (!!!!!) of your APIs. Okay, download Postman: https://www.postman.com/downloads/

Once you’ve downloaded and installed Postman, if it gives you any tutorial popups, just skip ’em. We are going to do the code equivalent of eating the juicy center of the PB&J and throw away the crust.

I need to create a new Workspace because mine is cluttered. Top center button

Hit “Create New” and name your Workspace. I named it Github NOOP Hexbot so I don’t accidentally use this workspace for real work later.

I chose a really clever description because I just like the word NOOP. NOOP NOOP NOOP NOOP NOOP NOOP NOOP NOOPNOOP NOOP NOOP NOOP NOOP NOOP NOO

Here’s the workspace I created.

There’s a buncha buttons and words we don’t need to care about right now.

The API that Github made for Hexbot is super simple, and here is the documentation for it: https://github.com/noops-challenge/hexbot#-api-basics

here’s only a single API endpoint for it:

An endpoint is the part of the API that receives requests and does stuff with them. We are going to send a request to the Hexbot API endpoint and get some kinda something back. I don’t know what it’s gonna do yet http://api.noopschallenge.com/hexbot

We are going to copy paste what’s between quotes here “”

And paste it into where it says “Enter request URL” right in the center of Postman

I wonder what color “#326688” is

Drop it into this color-hex site and we see it’s some kind of blue. Neat.

The API documentation showed us some parameters. Let’s try them all out.

If we add “?count=” to the end of our API request, we can get more colors at once. The new API request will read: (api.noopschallenge.com/hexbot?count=5)

It sent me back 5 different colors at once. Let’s try the width and height parameters. These parameters require ranges between 10 and 100,000, so I chose width of 69 and height of 420, because I am a child

Nice.

You can also seed the API. The API is not clear what it does with this information. Are we training a world-destroying artificial intelligence? I dunno. But I know based on the Postman GET request output that the API spits out similar-looking hex colors when you seed it this way



That’s it folks. Today we learned: downloading and installing @postmanclient, setting up a workspace, sending a GET request to a public API, reading API documentation, and experimenting with API parameters. This is basically what I do with every API I find



Check out this incredibly cool Hexbot someone made: (aytekk.github.io/hexbot/)

Polka dot party! 

