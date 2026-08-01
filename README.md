
<img src="./assets/mascot.png" width="200" align="right" />

<br/>

```ts
class Sujit implements Developer {
  role      = "SDE-1 @ Auragold";
  building  = "Tovix — a microlearning app (stealth · ships in ~30 days)";
  stack     = {
    ship:     ["TypeScript", "React", "Next.js", "React Native"],
    leveling: ["Python", "backend", "applied ML", "infra"],
  };
 mission = "build and ship my own apps, products, and SaaS";

  quirks = {
    thermostat: "16°C AC + a blanket, non-negotiable — my brain only compiles when I'm basically in cryosleep",
    bookmarks: () => {
      const saved = 400;
      const read = 3;
      return `${saved} tabs bookmarked "for later" — later has not arrived`;
    },
    lostAndFound: "once used my own phone's flashlight to search for... my phone",
    memoryLeak: "the 'where did I keep that' bug has no patch yet",
  };

  status(): string {
    return this.building ? "heads down, building" : "open to ideas";
  }
}
```

<br/>

```bash
$ git log --oneline --graph --decorate career

* stealth   building Tovix — microlearning, not public yet, dropping soon
* current   SDE-1 @ Auragold — shipping product in TypeScript, web + mobile
* learning  going deep on Python — backend, applied work, infra
* endgame   launch my own SaaS
```

<br/>

<table align="center">
<tr>
<td valign="top" width="50%">

**shipping with**

```ts
import { TypeScript, React } from "daily-driver";
import { NextJS, ReactNative } from "web-and-mobile";
import { Redux, TailwindCSS } from "the-usual-suspects";
```

</td>
<td valign="top" width="50%">

**leveling up in**

```py
from python import backend, applied, infra
from tools import FastAPI, Docker, AWS

still_learning = True
```

</td>
</tr>
</table>

<br/>

```bash
$ cat currently-reading.txt

[Book / Course Name 1]      — chapter 4 of 12
[Book / Course Name 2]      — in progress
[Docs / Resource Name]      — reference, ongoing
```
<sub>swap these in for whatever you're actually reading right now</sub>

<br/>

```bash
$ ls -la projects/

drwxr-xr-x  tovix/    microlearning app · stealth · shipping in ~30 days
```

<table align="center">
<tr>
<td valign="top" width="100%">

**Tovix** — a microlearning app, currently in stealth.
Built end-to-end on the TypeScript stack (web + mobile). More coming once it's live.

</td>
</tr>
</table>

<br/>

```
$ cat contact.txt
mail     → officialsujitmemane@gmail.com
linkedin → linkedin.com/in/sujit-memane-4704b01b0
twitter  → @iAmSujitMemane
youtube  → @thesujitmemane
```

<div align="center">
<sub>Tovix is currently in stealth. Come back in ~30 days. 👀</sub>
</div>
