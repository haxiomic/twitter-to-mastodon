# twitter-to-mastodon

So long and thanks for all the fish!

**Not ready yet, will write this as fast as I can, come join the fun!**

# Why are we leaving twitter?
It's now an offense to even so much as mention another social network[[0]](https://help.twitter.com/en/rules-and-policies/social-platforms-policy), that sort of environment is not one I feel comfortable talking in. There's plenty more reasons listed over here https://twitter.com/elonmusk

[0] https://help.twitter.com/en/rules-and-policies/social-platforms-policy

# Where is the code?
Literally just started, will push as I go!

# Other tools (please suggest more!)

**Re-post to mastodon via your archive**

- Download your archive (while you still can!)
https://twitter.com/settings/download_your_data
- Follow instructions here
https://github.com/FGRibreau/import-tweets-to-mastodon

**Find accounts you follow on mastodon**

_Extension Based_

- [Mastodon Handles in Twitter](https://chrome.google.com/webstore/detail/mastodon-handles-in-twitt/ncgejfiheecflhpoifeembagnjgigioi)

_API Based_
- https://debirdify.pruvisto.org/ (thanks  
@guerrilla)
- https://www.movetodon.org/ (thanks @NelsonMinar)
- https://fedifinder.glitch.me/
- https://twitodon.com/

# Plan

I want to copy all my posts over to my mastodon account and I want to find all my friends who have moved too. I also want to have some way to tell people I've moved. It should be _super simple_. Everyone should be to be able use

Twitter are limiting API access for this, so this tool will scrape posts and contacts from your page instead. You should control all the data (I don't want to authorize anything with twitter)

My twitter bookmarks and likes are special to me I want some way to preserve those too

Roadmap
- [ ] Read twitter page, extract follow lists
- [ ] Navigate infinite scroll and request rate limits
- [ ] Read all posts, just text content (media later)
- [ ] Navigate mastodon, explore simultaneous read-and-post
- [ ] Track visited posts in localStorage to avoid duplication
- [ ] POC: can copy text posts reliably in order of posting
--
- [ ] Image positing, progressively to avoid saving the images in mass
