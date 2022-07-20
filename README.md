# [brandont.blog](https://brandont.blog)

This is the public repository for my personal blog at [brandont.blog](https://brandont.blog). It runs on [Blot.im](https://blot.im) with a custom template (it's not _too_ custom, yet, just added my own colors and a couple of `.svg` icons). 

All of the published posts will be available here, as well as any changes I've made to the template or additional pages added to the site. For now, no major changes are planned for either the template or new pages, however I do plan on making some adjustments here and there to give the site my own flavor.

You can read about how Blot works in it's [documentation](https://blot.im/how). I've decided to categorize my posts into directories, using brackets (i.e. `[Personal]` or `[Programming]`). Blot will tag posts with the name of the bracketed directory they're contained in. I found that this is the most intuitive way to hold my posts and tag them appropriately, and the best way to organize the repository for public viewing.

I've also set up a git hook in my "production" Blot repository, which will hop to this repo, and pull any changes on a push. This way, I can publish new posts to both [brandont.blog](https://brandont.blog) and this repository at the same time.
