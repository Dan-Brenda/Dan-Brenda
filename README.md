# Daniel Brenda

I turn product ideas into shipped software by writing clear specs and directing AI coding agents to build against them. My current product, Measured Size, is live in the Chrome Web Store and Firefox Add-ons. I'm looking for product manager and AI implementation roles.

## What I'm building

**[Measured Size](https://measuredsize.com)**: your bra size, in each store's own labels. Enter two measurements once, and on a product page it shows your size as that listing labels it, whether it is in stock, and how confident it is, with a reason. It covers 167 brands, and the sizing engine is deterministic: no AI model decides a size.

- [Chrome Web Store](https://chromewebstore.google.com/detail/phffgakipjdnplpmkibfgnondilcfkpa) (Chrome, Edge and Brave)
- [Firefox Add-ons](https://addons.mozilla.org/firefox/addon/measured-size/) (Firefox on desktop and Android)
- iPhone and iPad app: in App Store review
- [Free bra size calculator](https://measuredsize.com/bra-size-calculator.html), installable on a phone
- [Free Fit API and MCP server](https://measuredsize.com/how-it-works.html#api) for AI agents, listed in [awesome-remote-mcp-servers](https://github.com/punkpeye/awesome-remote-mcp-servers/pull/1429)

## How I work

- **Spec-driven development with Claude Code.** Every change starts as a written phase spec with scope and acceptance criteria, and ends with a findings report of what changed and what was verified.
- **Release gates.** A store build ships only after scripted checks pass: package contents, per-browser QA, and a check that no personal data is in the build.
- **Automated testing.** Unit and page tests, plus a benchmark that re-runs the engine against saved real retailer product pages before each release.

## Contact

- Email: [dan.breny@gmail.com](mailto:dan.breny@gmail.com)
- LinkedIn: [linkedin.com/in/danielbrenda](https://www.linkedin.com/in/danielbrenda)
- Portfolio: [dan-brenda.github.io](https://dan-brenda.github.io)
