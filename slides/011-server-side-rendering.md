---
notes: |
  Server side rendering will help you climb the jam ladder to maximum jam city! remember the quote from jamstack.org, they talk about building **fast** sites, and one way to really speed up the perceived performance of a Single Page application (and to win cool-engineer points) is to implement sever side rendering.

  Now in Ember, we have been able to do SSR with relative ease for years now thanks to the amazing work put into Fastboot, but we have a slight problem. If we setup a node server to host our fastboot application then we're sliding back down the jam continuoum. Remember that Netlify is primarally a static asset CDN, and the definition from JAMStack.org talked about serving "directly from the CDN" ... so instead we need some way to get the goodness of SSR while still being able to serve the assets statically. This is where pre-rendering comes in :tada:
---

# Server-side Rendering

![Fastboot](/images/fastboot.svg)
