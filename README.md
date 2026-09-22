# Walter Marshall

I build software end to end. The mobile app, the web app, and the backend behind both.

Right now that's **Dealer Recon Systems**, a dealer management platform I built and
run on my own — about 50,000 lines of Dart serving iOS, Android and web from one
Flutter codebase, with 37 Cloud Functions and 933 lines of Firestore rules behind
it. I spent years working in dealerships before I wrote a line of software for one.

Looking for a remote role. Portfolio and résumé at **[waltermarshall.dev](https://waltermarshall.dev)** · **elatjobs@gmail.com**

---

### Things you can read

| | | |
|---|---|---|
| **[Hindsight](https://github.com/ElatDev/Hindsight)** | TypeScript | Free, offline chess game review. Stockfish grades every move, and it explains mistakes by finding the actual pin, fork or hanging piece. v0.1.0 has installers for Windows, macOS and Linux; CI runs 581 tests on all three. |
| **[paeth](https://github.com/ElatDev/paeth)** | Rust | A PNG decoder written from the spec. Decodes all 162 valid PngSuite images pixel-for-pixel identically to an independent decoder, and rejects all 14 corrupt ones. 151 tests. |
| **[loupe](https://github.com/ElatDev/loupe)** | C | Read-only PE and ELF inspector. Every offset in a binary is attacker-controlled, so every read goes through one bounds-checked accessor. Parses all 4,264 binaries in System32 under ASan, UBSan and LeakSanitizer with no crashes and no leaks. |
| **[unspool](https://github.com/ElatDev/unspool)** | Python | A pcapng parser and protocol decoder. Checked frame by frame against `tshark` across all 562 public Wireshark sample captures — 1,290,282 packets. |
| **[vinspect](https://github.com/ElatDev/vinspect)** | Go | Validates and decodes VINs offline. Verified against 6,516 real VINs from NHTSA crash-test records. |

### Things I can't show you

**Mogadishu** — a working model of a 2003 game engine rebuilt from compiled x86
with no source, symbols or documentation. 467 commits, ~210,000 lines, 826 tests.
Every claim is labeled as read from the disassembly, derived, or a guess, and
cross-checked against the running game: predicted blast knockback of 7.69 m/s
against 7.7 measured. Stays private because the binary it studies is DRM-protected.

**Shardfall** — a co-op bullet-hell MMO. Authoritative server running the realm
simulation at 20 ticks/s, browser client, netcode on raw WebSockets with no game
framework. 40,470 lines of TypeScript, 18,711 of them tests. Built a lag proxy and
a bot swarm to test it.

---

I like problems where you can check the answer. The math section of my site
animates sixteen results and ships a separate checker that re-derives every number
from scratch, sharing no code with the animations — it has caught six errors of
mine so far, and the cards say which.
