# Walter Marshall

I build software end to end: the mobile app, the web app, and the backend behind both.

Right now that's **Dealer Recon Systems**, a dealer management platform I built and
run by myself. It's about 50,000 lines of Dart serving iOS, Android and web from one
Flutter codebase, with 37 Cloud Functions and 933 lines of Firestore rules behind it.
I worked in dealerships for years before I wrote software for one.

I'm looking for a remote role. My portfolio and résumé are at
**[waltermarshall.dev](https://waltermarshall.dev)**, or email me at **elatjobs@gmail.com**.

---

### Projects

| | | |
|---|---|---|
| **[Hindsight](https://github.com/ElatDev/Hindsight)** | TypeScript | Free, offline chess game review. Stockfish grades every move, and it explains mistakes by finding the actual pin, fork or hanging piece. v0.1.0 has installers for Windows, macOS and Linux, and CI runs 581 tests on all three. |
| **[paeth](https://github.com/ElatDev/paeth)** | Rust | A PNG decoder written from the spec. Decodes all 162 valid PngSuite images pixel-for-pixel identical to an independent decoder and rejects all 14 corrupt ones. 153 tests. |
| **[loupe](https://github.com/ElatDev/loupe)** | C | Read-only PE and ELF inspector. Every read goes through one bounds-checked function, and it parses all 4,264 binaries in System32 under ASan, UBSan and LeakSanitizer with no crashes or leaks. |
| **[unspool](https://github.com/ElatDev/unspool)** | Python | A pcapng parser and protocol decoder, checked frame by frame against `tshark` on all 562 public Wireshark sample captures (1,290,282 packets). |
| **[vinspect](https://github.com/ElatDev/vinspect)** | Go | Validates and decodes VINs offline. Tested against 6,516 real VINs from NHTSA crash-test records. |

### Private projects

**Mogadishu:** a working model of the 2003 Delta Force: Black Hawk Down engine,
rebuilt from compiled x86 with no source, symbols or documentation. 467 commits,
about 210,000 lines and 826 tests. I check it against the running game: it predicted
a blast knockback of 7.69 m/s, and the game measured 7.7. The code stays private
because the game it studies is DRM-protected.

**Shardfall:** a co-op bullet-hell MMO. An authoritative server runs the realm at
20 ticks a second, with a browser client and netcode on raw WebSockets, no game
framework. 40,470 lines of TypeScript, 18,711 of them tests. I built a lag proxy
and a bot swarm to test it.
