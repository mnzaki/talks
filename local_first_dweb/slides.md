---
title: P2P Future - A local first DWeb
theme: night
slideNumber: true
controls: true
---

<style>
.reveal h1, .reveal h2, .reveal h3, .reveal h4, .reveal h5, .reveal h6 {
  color: #e8e8e8;
  }
.reveal .panel {
  background: rgba(0,0,0,0.8);
  padding:2em;
}
</style>

# The DWeb and Local First apps

<p>[&commat;mnzakisol](https://twitter.com/mnzakisol) [github.com/mnzaki](https://github.com/mnzaki)</p>
<p>[&commat;GETJolocom](https://twitter.com/GETJolocom/) [jolocom.io](https://jolocom.io)</p>

# The DWeb and Local First apps

# The Decentralized Web {bg=#000 transition=zoom}
<img src="assets/dweb.png" />
<div>
[decentralizedweb.net](https://decentralizedweb.net/)
<p>A BLN/SF initiative trying to connect the dots across the globe</p>
</div>

# DWeb Berlin {bg=#000 transition=zoom style="color: #fff"}
<img src="assets/dweb_bln.png" />
<div>
<p>[https://meetup.com/dweb-berlin/](https://www.meetup.com/dweb-berlin/)</p>
<small>This is the Berlin chapter, facilitated by [jolocom.io](https://jolocom.io). Say hello to [hello@jolocom.io](mailto:hello@jolocom.io)</small>
</div>

# {bg=#000;assets/dweb_nodes.png transition=fade}

# {bg=#000;assets/dweb_nodes.png transition=fade}
<div class="panel" style="position:fixed; top:0; right: 0; padding: 0">
UPCOMING DWEB WEBSITE
</div>

# DWeb Meetup Links {bg=#000 transition=fade}
<p>[#DWebSF](https://www.meetup.com/dwebsf/)</p>
<p>[#DWebBLN](https://www.meetup.com/dweb-berlin/)</p>
<p>[#DWebArizona](https://www.meetup.com/Desert-Blockchain/)</p>
<p>[#DWebAustin](https://www.meetup.com/DWeb-Austin/)</p>
<p>[#DWebBoston](https://www.meetup.com/DWeb-BOS/)</p>
<p>[#DWebPerm](https://www.meetup.com/Permanently-decentralized/)</p>
<p>[#DWebPrague](https://www.meetup.com/dweb-prague/)</p>
<p>[#DWebShanghai](https://www.meetup.com/dweb-shanghai/)</p>

# {bg=#000;assets/dweb_camp.png transition=fade}
<div class="panel">
<h1>DWebCamp 2019</h1>
[dwebcamp.org](https://dwebcamp.org/)
</div>

# {bg=#000;assets/dweb_camp.png transition=fade}
<div class="panel">
There will be more camps! Join your local meetup or start one!
</div>

# Local First Applications

# Local First
- Offline functionality and data access
- Local communication channels

# Data Storage
- store user data locally
- allow collaborative editing even when offline!

# "Databases" Without Servers: How?
- Conflict-free Replicated Data Types (CRDTs)
  - [https://duckduckgo.com/?q=CRDT](https://duckduckgo.com/?q=CRDT)
  - [CRDTs: consistency without concurrency control](https://pages.lip6.fr/Marc.Shapiro/papers/RR-6956.pdf)
- Offline interactions
- Server-less interactions
  - but actually server-less, not with virtualized servers
    (like amazon's lambda)
  - only peers, no servers

# Connection-less (A.K.A. "offline") interaction
- you can consume or edit your replicated application data at any time

# Offline first Trello clone: Trellis

- [Ink & Switch: Local-first software](https://www.inkandswitch.com/local-first.html)
- [Trellis Demonstration on youtube](https://www.youtube.com/watch?v=L9fdyDlhByM)

<iframe width="560" height="315" src="https://www.youtube.com/embed/L9fdyDlhByM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# The Network {bg=#200}
How do you physically reach your peers' devices?

# Local first connectivity
- devices/applications are capable of direct communication on the local network,
  through a wireless access point
- Or also directly over wifi/bluetooth mesh
  - open-mesh's Batman: [open-mesh.org](https://www.open-mesh.org)
  - The Serval Project: [https://servalproject.org](https://servalproject.org/)
  - Open Wireless Link: [owlink.org](https://owlink.org/)
    - (A.K.A. Ap*le Wireless Direct Link)

# The Internet {bg=#300}
But why bother when we already have    
`THE INTERNET`

# The Internet {bg=#400 transition=zoom}
- a given privilege
- can be taken away, censored, disrupted, monitored
- sending memes to your flatmate from the toilet shouldn't need to go through
computers on the other side of the world
- [no-internet.net](https://no-internet.net/)

# No Internet {bg=#500 transition=zoom}
- [no-internet.net](https://no-internet.net/)
- [Andre Staltz: The web began dying in 2014](https://staltz.com/the-web-began-dying-in-2014-heres-how.html)
- [Andre Staltz: A plan to rescue the Web from the Internet](https://staltz.com/a-plan-to-rescue-the-web-from-the-internet.html)
- [Mozilla: Introducing DWeb](https://hacks.mozilla.org/2018/07/introducing-the-d-web/)

# and back
- local first application
  - local data
  - local connectivity
- can still talk to remote peers over `the internet` if there is an internet

# DWeb
## Brewster Kahle at Devcon4: The Web We Want
- Demo of [dweb.archive.org](https://dweb.archive.org) a decentralized version of [The Internet Archive](https://archive.org)
[https://youtu.be/rkdFko6wNuc?t=635](https://youtu.be/rkdFko6wNuc?t=635)
<iframe width="560" height="315" src="https://www.youtube.com/embed/rkdFko6wNuc?start=635" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# {bg=#000;assets/brewster_problems1.png}

# {bg=#000;assets/brewster_problems1.png}
<div class="panel">
There are many unsolved problems on the path to the dweb
</div>

# {bg=#000;assets/brewster_problems2.png}

# {bg=#000;assets/brewster_problems2.png}
<div class="panel">
And this is what [Jolocom](https://jolocom.io) is doing.
We are making an [Identity Wallet](https://github.com/jolocom/smartwallet-app)
based on Self Sovereign Identity principles
</div>

# SSI: Self Sovereign Identity
[https://youtu.be/djhYZZ3CkuM](https://youtu.be/djhYZZ3CkuM)
<iframe width="560" height="315" src="https://www.youtube.com/embed/djhYZZ3CkuM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# {bg=#000;assets/jolocom.png}

# {bg=#000;assets/jolocom.png}
<div class="panel">
Yes we can be more local-first, it's just taking time.... [peer DIDs!](https://openssi.github.io/peer-did-method-spec/index.html)
</div>

# Join us at the DWeb BLN meetup!
We facilitate the Berlin chapter of DWeb.
[#DWebBLN](https://meetup.com/dweb-berlin/)
[hello@jolocom.io](mailto:hello@jolocom.io)
<br />
[https://meetup.com/dweb-berlin/](https://www.meetup.com/dweb-berlin/)
<br />
<img src="assets/dweb_bln.png" />

# Things to look for
- twitter: [&commat;GETDWeb](https://twitter.com/GETDWeb) [&commat;GETJolocom](https://twitter.com/GETJolocom)
- [DWeb Berlin Meetup](https://www.meetup.com/dweb-berlin/)
  - there will be a website soon!
  - not dwebs.io that's something else....
- [Jolocom.io](https://jolocom.io)
- Local First Software
- https://no-internet.net
- [CRDTs](https://duckduckgo.com/?q=CRDT)
- [scuttlebutt](https://scuttlebutt.nz)
- [solarpunk](https://duckduckgo.com/?q=solarpunk)
- [Murray Bookchin](https://duckduckgo.com/?q=Google+Murray+Bookchin)

