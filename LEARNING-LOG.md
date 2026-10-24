# Learning Log

What I learned each week, newest first. Weeks are numbered by ISO week (W39-2026 = week 39 of 2026).

## W43-2026
- Open-source video automation: forked [Otopilot](https://github.com/perihangozukara/otopilot) (MIT) and extended it: AI video clips as scenes, a local text-to-speech bridge with a pronunciation dictionary, pauses between sentences, clips that play in full with their ambient sound under the narration, subtitle styling, fade transitions, and re-generating only the paragraphs whose text changed. Every change is covered by the test suite (304 tests passing).
- AI video production: produced a ~9-minute animated children's story episode end to end: script split into 39 scenes, AI-generated video clips with character reference images, local voice-over, automatic editing; fixed voice consistency, pacing and transitions over four review rounds.
- AI-assisted testing: five role-playing agents (different ages, buyer/seller roles) used a mobile app prototype through Playwright; about 85 findings were merged and the critical ones fixed; 25 of 25 automated tests pass.
- Desktop tool: fixed [Seç-Çevir](https://github.com/perihangozukara/SecCevir) going deaf after a few hours. The mouse hook moved to its own thread and is re-installed every minute; copy is sent in one step; a fallback address is used when the translation service rate-limits.
- APIs: connected the YouTube Data and Analytics APIs with OAuth (desktop client) and pulled channel statistics; keys stay in an environment file, never in code. Learned that test-mode tokens expire after 7 days.
- Multi-assistant agent setup: one role file shared by Claude Code, Codex, Gemini and Copilot, with small pointer files for each; compared the token cost of three setups before choosing the cheapest.
- Local search: built a SQLite search index over my notes so agents can find the right note without reading everything.
- Research and planning: competitor analysis for an educational YouTube channel, a master prompt for a Claude Project and a release roadmap. Tested a step-by-step Google Sheets prompt in a clean session and in real Google Sheets; the formulas worked, but I judged the approach unsuccessful and changed course.

## W42-2026
- Web fundamentals: HTTP and APIs, talking to an API with JSON, frontend vs. backend, databases, and first steps in UX.
- Built and published [Prompt Compass](https://github.com/perihangozukara/prompt-compass), a small web page that checks a prompt against clear rules (HTML, CSS, JavaScript, GitHub Pages).
- Repo study: read two open-source repositories (Anthropic's Claude cookbooks, MDN's PWA examples) and tested five recipes on sample data: web search, classification, summarizing, answering questions from a document, and a "devil's advocate" review.
- Claude Code: organized my setup in layers (one top-level rules file, team rules and agent rules) with permission locks; agent notes split between local files and an archive.
- AI-assisted testing: used sub-agents, each playing a different type of user, to test apps and fix what they found.
- Desktop tool: improved [Seç-Çevir](https://github.com/perihangozukara/SecCevir) with caching and a cool-down for rate limits, a 10-second timeout, automatic language detection and smarter popup placement.
- Free video pipeline: set up Remotion, FFmpeg and Whisper; compared text-to-speech voices by license and chose an MIT-licensed one for commercial use; rendered a 15-second style test. Also built a 3D view of a small web dashboard with Three.js.
- Content: bilingual (Turkish/English) posts explaining tools and MCP, the agent loop, and hallucination and verification.

## W41-2026
- Web fundamentals: debugging in the browser console (TypeError, ReferenceError, SyntaxError and a logic error), finding each bug from its file:line:column address, and writing a clear four-part bug report. How a browser requests, loads and draws a page; DevTools tabs (Network, Elements, Console, Application).
- Development environment: set up a new laptop from scratch. Installed Git, Node.js, Python and Android Studio from the terminal with winget, checked versions, and moved my projects, notes and backups over.
- App development process: studied the path from idea to store release for Android (Kotlin + Android Studio) and cross-platform (Flutter) apps. Notes only, nothing published yet.
- Claude Code: wrote reusable skills (packaged instructions) for recurring tasks, and rebuilt an AI project with its instructions and memory under a new account.
- Content: bilingual (Turkish/English) posts explaining AI basics: context and the context window, memory vs. context, and what a skill is.

## W40-2026
- Web fundamentals: CSS layout with Flexbox (cards side by side, wrapping on small screens) and a semantic page structure (header, nav, main, section, article, footer).
- JavaScript basics: finding elements, listening to events and updating the page; if/else; saving data in the browser with localStorage; reading the browser console. Built a small page with search and a shopping list that remembers its items.
- Spreadsheet automation: built a Google Sheets tracking system with formulas, dropdowns, a summary panel and auto-generated personal messages; built a client–listing matching sheet and published it as a sample case study.
- Claude Code: persistent project instructions (CLAUDE.md), a custom review agent, scheduled tasks for recurring work, and my first terminal commands.
- Prompt engineering: studied an open-source prompt cookbook and turned its methods into a reusable prompt package for daily work (email triage, day planning, a prompt that writes prompts), tested on fictional sample data.
- AI agents: wrote a step-by-step build plan for an AI email-sorting agent (not built yet).
- Content: bilingual (Turkish/English) posts explaining AI basics: what an LLM is, tokens, hallucination and the parts of a good prompt; consistent image generation from a reference image.
- Freelance profiles: rewrote my GitHub, LinkedIn and Upwork profiles to show only real, demonstrable work.

## W39-2026
- Development basics: files, folders and paths; first steps in the terminal.
- Formats: Markdown and JSON.
- Git & GitHub: installed Git, learned the basic add → commit → push loop, published my first repository.
- AI assistants: built my first no-code AI assistant from clear instructions and structured context files, and connected it to GitHub so the context stays in sync.
- Web fundamentals: HTML basics (page skeleton, links, images, inputs and buttons, div) and a first look at CSS.

## W38-2026
- Set up a "second brain": a structured note system so every lesson and decision is written down and reusable.
- AI fundamentals: what generative AI and Claude are, what they can and cannot do.
- Working with AI: giving clear instructions, providing the right context, checking the output, treating AI as a working partner.
- GitHub: how to read a repository.
- First look at Android Studio with a starter project.
- Wrote my learning roadmap, from fundamentals to building AI systems.
