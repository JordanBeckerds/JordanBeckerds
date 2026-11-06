# Hi, I'm Jordan Becker Damour 👋

Web developer and self-hoster from Pau, France. I build products end to end: the app, the server it runs on,
the deploy pipeline and the marketing site. French (native) · English.

### What I've shipped

- **[TryTechSafe](https://trytechsafe.com)**: practice phones and computers in the browser for seniors and
  beginners. There are 4 device simulators (Android, iPhone, Windows, Mac styles), each with 140+ guided
  lessons, plus accounts, subscriptions and a Microsoft Store app. *Source is private; ask me for a demo.*
- **[outils-ia.life](https://outils-ia.life)** ([BDNews](https://github.com/JordanBeckerds/BDNews)): an AI content
  engine, with a Python "journalist" pipeline on top of LLMs, a PHP site and a gateway, all in Docker.
- **[PatteForm](https://github.com/JordanBeckerds/PatteForm)**: an open-source, white-label platform for animal
  shelters (adoption site + admin).
- **[PlanningCo](https://github.com/JordanBeckerds/PlanningCo)**: team scheduling (shifts, leave, roles), PHP + MySQL
  + Docker.
- **[Keys & Click](https://jordanbeckerds.github.io/Keys-Clicks/)**: tests for typing speed, mouse accuracy and
  reaction time.
- **[Fraudes-Roleplay](https://jordanbeckerds.github.io/Fraudes-Roleplay/)**: a scam role-play simulator that helps
  seniors spot phone scams.
- Client websites through my studio, **[JBD.dev](https://jordanbeckerds.github.io/jbd-studio/)**.

### How I run things

- My own **Debian server** hosts about 15 Docker Compose stacks: PHP, Node, Python, MySQL and MariaDB.
- Every site is published through **Cloudflare Tunnels**, with no open inbound ports. Previews are routed by
  subdomain or path.
- **Cloudflare Pages + D1** run the TryTechSafe website and API.
- End-to-end tests run in headless browsers, with gates before every deploy.
- Local AI on a GPU: **Ollama**, **ComfyUI**, plus Claude API integrations.
- I patch fast: when a critical PHP RCE hit in 2026, I rebuilt and upgraded every PHP container the same day.

### Stack

`JavaScript` `Node.js` `PHP` `Python` `HTML/CSS` `MySQL` `SQLite/D1` `Docker` `Linux` `Cloudflare` `Git` `LLMs`

📫 Contact: [jbeckerdamour.com](https://jbeckerdamour.com)
