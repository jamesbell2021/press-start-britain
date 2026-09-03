# Games Industry in Northern Ireland

An interactive single-page site making the case for games as a career: where the British games industry came from, how big it is right now, and nine real people whose careers show there's no one way in.

**Live site:** https://jamesbell2021.github.io/press-start-britain/

Built to help inspire Level 3 students (roughly 17+) to consider the games industry as a career — grounded in real studios, real people, and current, sourced statistics rather than generic career-day talking points.

## What's on the page

- **Origins** — a timeline from the early-1980s home-computer "bedroom coder" boom (Manic Miner, Ultimate Play the Game, Elite — and Northern Ireland's own David Perry) through to today, with dated, named examples at each stage.
- **Now** — current UK games industry statistics (market size, jobs, GVA, number of studios), animated on scroll, plus five studios shipping major titles today: Rockstar North, Frontier Developments, Team17, Media Molecule, Playground Games.
- **People** — nine short, factual case studies spanning programming, founding a studio, business leadership, and narrative writing, each with an optional "+ fun fact" toggle, closing with Demis Hassabis's path from Bullfrog Productions to a Nobel Prize.
- **Here** — Northern Ireland's own part in the industry, past and present: David Perry (Lisburn, Shiny Entertainment, MDK), Italic Pig (Holywood), Hypixel Studios/Hytale (Derry~Londonderry), and Belfast's Pixel Mill co-working space.
- **Your move** — a short "find your route in" quiz that matches a student's answers to one of the featured case studies and a suggested pathway, plus the four routes people actually use to get in: college, apprenticeships, game jams, university or shipping something yourself.

Every statistic and biographical claim is sourced — see the footer on the page, or [`SOURCES.md`](SOURCES.md) for the full list of links used while writing it.

## Using it in class

Works well as a 10–15 minute read at the start of a careers or industry-context session, or as a pre-read before a guest speaker/employer visit. Hand it to students directly and let them take the quiz in "Your move" — it's a quick, low-stakes way to get them talking about which part of development actually appeals to them before you set a task (start a portfolio piece, sign up for a game jam, research one of the studios named on the page). There's a sound toggle in the top-right if you want the quiz's chiptune-style feedback audible.

## Running it

No build step — it's one HTML file with no dependencies beyond three Google Fonts.

- **Online:** use the GitHub Pages link above.
- **Offline:** download [`index.html`](index.html) and open it in any browser.

## Updating the content

All copy lives directly in `index.html`, organised by section (`#origins`, `#now`, `#people`, `#here`, `#move`). Statistics will age — the market-size and jobs figures in the **Now** section are dated to Ukie's 2025/26 reporting and should be refreshed periodically from [ukie.org.uk](https://ukie.org.uk/).

---

🤖 Built with [Claude Code](https://claude.com/claude-code)
