### Java backend developer exploring classical ML and local LLMs

I work on Java backend services. Lately I've been going deeper into classical
ML and local-first LLM tooling, using AI assistants for scaffolding and
boilerplate while keeping ownership of architecture, trade-offs, and review.

## Projects

### Local LLM companion — desktop agent (JavaFX, in progress)
Desktop agent that stores conversation logs, summarizes them, and runs a
scheduled reflection pass over the day's logs using local models. This grows
out of my Java backend work. Still in local development; not public yet. I'll
publish it once the first usable version is ready.

### SyntheticHealthSimulator — ML coursework (Python)
https://github.com/kavalex/SyntheticHealthSimulator

Coursework on causal health insights and synthetic cohorts. My part: problem
framing, feature design, model selection, and evaluation. I used AI for
boilerplate; the analytical decisions were mine.

### mysite — small Go web template
https://github.com/kavalex/mysite

A "how small can a secure Go service be?" experiment: standard library plus
3 dependencies. I designed the architecture, selected the dependencies, and
reviewed the code, paying extra attention to security-relevant parts. No formal
security audit.

I'm not a Go expert. The implementation was generated with DeepSeek and MiniMax
under my direction. This was a deliberate exercise in reviewing AI-generated
code. It started as a small landing-page experiment, but the template grew into
a backend skeleton — authentication, sessions, CSRF protection and CSP headers,
rate limiting, and SIGHUP-based config reload — that I plan to reuse as the
backend service for the companion's future web UI.

## How I use AI

I use AI as a coding assistant for scaffolding, boilerplate, and exploring
unfamiliar stacks. Architecture, trade-offs, security review, and final
decisions are mine. Where relevant, each repo README states how AI was used and
what was reviewed.
