# Decomposition Drill

Practice tool for Palantir-style decomposition (system design) interviews.

1. Pick a problem or write your own.
2. Answer each clarifying question, one at a time.
3. Get a drawn architecture with component specifics, estimates, APIs, data model, tradeoffs and failure modes.
4. Rehearse a talk-through script line by line.

## Using it

Open the site and paste an Anthropic API key under **Problem**. The key is stored only in your browser's local storage and is sent only to `api.anthropic.com`. Without a key you can still browse the example design and answer a standard set of clarifying questions.

The page calls Claude Opus 5.5 through the official Anthropic JavaScript SDK (loaded from jsDelivr), with Anthropic's server-side fallback model turned on in case a request is declined.

## Hosting

This folder is a static site. On GitHub: Settings → Pages → Deploy from a branch → `main` / root.
