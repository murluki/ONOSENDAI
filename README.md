# ONOSENDAI オノセンダイ
The reference metaverse client for the permissionless, decentralized, thermodynamic [cyberspace meta-protocol built on nostr](https://github.com/arkin0x/cyberspace)

![onosendai-pano](https://user-images.githubusercontent.com/99223753/223734919-ee5fc4d0-ee89-409c-a7c8-1848310bb92d.png)

ONOSENDAI enables human agents to interact with the 3D extension of reality known as 'cyberspace'.

Try it out at [https://onosendai.tech](https://onosendai.tech)

[Check out the FAQ](#faq)

https://user-images.githubusercontent.com/99223753/223145715-31174a68-9bc5-4c06-abb2-5f3a1e1352a6.mp4
> Music from #Uppbeat (free for Creators!):
> https://uppbeat.io/t/hey-pluto/miami-1987
> License code: VLG0ATMLGHSH4MT8

## Controls

**Desktop**

 - WASD/arrow keys - move
 - click - read
 - click + drag - look
 - R - up
 - F - down

**Mobile**

 - touch 2 fingers - move forward
 - drag - look
 - tap - read

*The ideal experience is currently desktop. There are bugs on iOS Safari.*

## Concepts and Explanations

In our universe all actions require energy expenditure as entropy and all actions are permissionless; the only way to oppose an action in reality is to expend energy. Cyberspace is a meta-protocol on the permissionless nostr protocol, and all actions in cyberspace have a thermodynamic cost via proof-of-work. Therefore, cyberspace is a digital extension of reality because cyberspace shares those 2 fundamental properties with reality: it is permissionless and thermodynamic.

Short explanation of cyberspace as an extension of reality: [https://telegra.ph/Cyberspace-and-Proof-of-Work-04-17](https://telegra.ph/Cyberspace-and-Proof-of-Work-04-17)

In-depth explanation of cyberspace: [https://telegra.ph/Cyberspace-A-Real-Digital-Place-04-13](https://telegra.ph/Cyberspace-A-Real-Digital-Place-04-13)

arkinox video talk about ONOSENDAI and cyberspace: [https://youtu.be/6POq0eaW1J0](https://youtu.be/6POq0eaW1J0) (ignore the weird video spam at 3:20)

## Implementation 😅🛠

### cyberspace meta-protocol [https://github.com/arkin0x/cyberspace](https://github.com/arkin0x/cyberspace)

- [ ] Construct
- [ ] Shards
- [ ] Operators
- [ ] Drift
- [ ] Derezz
- [ ] Armor
- [ ] Vortex
- [ ] Bubble
- [ ] Stealth
- [ ] Shout

### client features

- [x] Address `kind 1` events by simhash
- [x] Flight/navigation controls
- [x] `kind 1` new state
- [x] `kind 1` selected state
- [x] `kind 1` read state
- [x] `kind 1` bookmarked state
- [x] Bookmark events (stored locally)
- [x] Acceleration-based controls to handle large distances
- [x] Visualize speed
- [x] Show current coordinates
- [x] Mobile: 2x touch to accelerate
- [x] Mobile: 3x touch to reverse
- [x] Persist bookmarked events (localStorage)
- [ ] Cross-browser testing and fixes
- [ ] Mobile: scroll event content by touch
- [ ] Mobile: gyroscope controls to look (but keep drag-to-look controls)
- [ ] Note access history panel
- [ ] Persist read events (simhash + id only) so you can skip over them
- [ ] Zap visualization for `kind 1`
- [ ] Visualize traveled routes
- [ ] Add a marker to nearby notes so they are easier to track; marker should hug edge of screen if the note is nearby but not in frustum
- [ ] NIP-26 for sign-in
- [ ] speech-to-text-to-speech communication
- [ ] Publish kind 1 notes from ONOSENDAI
- [ ] Search/filter notes by string
- [ ] Locate note by entering Event ID
- [ ] Locate user by entering pubkey
- [ ] Filter POW for notes
- [ ] Filter POW for constructs
- [ ] VR support

## Support FOSS You Believe In ⚡

If you'd like to support ONOSENDAI development, you can contribute at our [geyser.fund](https://geyser.fund/project/onosendai) zap me at arkinox@getalby.com or become a sponsor. Get in touch with me on [nostr](https://snort.social/p/npub1arkn0xxxll4llgy9qxkrncn3vc4l69s0dz8ef3zadykcwe7ax3dqrrh43w), npub1arkn0xxxll4llgy9qxkrncn3vc4l69s0dz8ef3zadykcwe7ax3dqrrh43w

Join the official ONOSENDAI Telegram: [https://t.me/ONOSENDAITECH](https://t.me/ONOSENDAITECH)

Other great ways to contribute:

- pull requests
- sharing ideas & expertise
- bug reports
- reading sci-fi
- and telling your friends!

Check out the cyberspace spec and contribute: https://github.com/arkin0x/cyberspace

npub1arkn0xxxll4llgy9qxkrncn3vc4l69s0dz8ef3zadykcwe7ax3dqrrh43w

NIP-05 arkinox@arkinox.tech

## Name

"ONOSENDAI" is the name of the device of Japanese manufacture that allows one to connect their mind to cyberspace in the foundational sci-fi book "Neuromancer" by William Gibson.

# FAQ

### Q: Cyberspace? Metaverse? Seriously? What is this all about?

### A: 

Cyberspace (in this context) is an early-internet trope from the 80s. It's an enthusiastic and naive speculation on the future of network-connected computers and how humans might use them. Ultimately, instead of interacting in 3D virtual spaces, humans ended up interacting via documents in web browsers which is much more practical and efficient than 3D visualizations.

Besides the problem of visualizing content, there are several more critical problems with the ['shared consensual hallucination'](https://www.goodreads.com/quotes/14638-cyberspace-a-consensual-hallucination-experienced-daily-by-billions-of-legitimate) — problems rarely (if ever) addressed in fiction: 

- Who hosts it?
- Who decides how it looks?
- Who owns the content?
- Who makes the rules?
- Who assigns the space?
- Who controls it?

These questions are answered satisfactorily in the era of bitcoin and nostr:

- Who hosts it? **nostr relays**
- Who decides how it looks? **nostr clients**
- Who owns the content? **users cryptographically own their content**
- Who makes the rules? **open source consensus**
- Who assigns the space? **an impartial algorithm + proof of work**
- Who controls it? **NOBODY**

In my opinion, it is **only** in the context of bitcoin and nostr that something like cyberspace could conceivably exist. Without the decentralized and permissionless properties of nostr and bitcoin, cyberspace is just another 3D game owned by a company. However, when cyberspace is decentralized, enforces property rights, responds to proof of work, and enables instant value transfer, it becomes something entirely different.

If it were not for the profound inventions of bitcoin and nostr, metaverse aspirations would be nothing but ludicrous and delusional, because a centralized permissioned metaverse does not accomplish anything more than being a video game, and a metaverse without proof-of-work only succeeds in mirroring the existing power structures in society and computing today.

Thanks for coming to my TED talk. Let's build.

### Q: How do I log in with my private key/browser extension?

### A:

You can't login yet. ONOSENDAI can't yet do anything on your behalf. See the implementation checklist for upcoming features.

# License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
