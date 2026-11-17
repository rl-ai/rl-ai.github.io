# RL AI

We build open-source AI applications: autonomous agents that do real
work, run on your own hardware, and stay under your control.

Our first product is in pilot today â€” and the pilot is open. Feedback
from people running it shapes the roadmap.

## Aerial â€” pilot release (beta)

**Aerial is the control tower for a swarm of autonomous agents.**
Agents fly solo â€” finding opportunities, running 24/7, self-healing
when infrastructure fails â€” while the operations layer keeps the whole
swarm coordinated, evidenced, and saturated.

- **Ticket hub** â€” tasks as shared context: multiple agents and roles
  work the same task, each inheriting the chain of evidence and
  decisions
- **Ops agent** â€” polls every 5 minutes: failures classified, ticketed,
  fixed, and re-verified. The fix isn't done until a symptom probe proves it.
- **Fleet manager** â€” bring your own model (local VRAM, self-hosted, or
  cloud); VRAM management, seat-swap, self-healing seats
- **Built-in reporting** â€” daily board, exec report, usage per call and
  per seat on a 15-minute cadence
- **Fully local** â€” hub, console, runners, and models on your hardware.
  No telemetry. No data leaves the machine.

Pilot release (beta): the core is production-tested daily on the team's
own fleet, but not yet packaged for general distribution.

â†’ [github.com/rl-ai/aerial](https://github.com/rl-ai/aerial) Â·
[Getting started](https://github.com/rl-ai/aerial/blob/main/GETTING-STARTED.md) Â·
[60-second teaser](https://rl-ai.github.io/aerial-teaser.html)

## Contribute

This is a pilot â€” feedback is the roadmap.

- **Running it?** Post your setup in
  [Discussions â†’ Show and tell](https://github.com/rl-ai/aerial/discussions) â€”
  model seats, workflows, integrations, screenshots
- **Found something broken?** [Bug report](https://github.com/rl-ai/aerial/issues/new?template=bug.md) â€”
  include `bin/aerial_verify.py` output; it's the most useful thing you can send
- **Want something?** [Feature proposal](https://github.com/rl-ai/aerial/issues/new?template=feature.md)
- **Code contributions welcome** â€” see [CONTRIBUTING.md](https://github.com/rl-ai/aerial/blob/main/CONTRIBUTING.md)

Known limitations and the running fix log:
[ROADMAP.md](https://github.com/rl-ai/aerial/blob/main/ROADMAP.md) Â·
[docs/BUGLIST.md](https://github.com/rl-ai/aerial/blob/main/docs/BUGLIST.md)

## Where we came from

RL AI started as AI-assisted investing research: market-data pipelines,
feature engineering, backtesting, and model evaluation for systematic
strategies. That heritage built the engineering discipline Aerial runs
on â€” evidence over claims, reproducible workflows, risk-aware outputs.
The research platform continues in parallel; the disclaimer still
applies: nothing here is financial advice, and trading involves risk.
