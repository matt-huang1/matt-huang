## Matthew Huang

**I build the layer that decides whether an AI's output is safe to act on.**

Not the model. The engineering around it: the checks, the boundaries, the evaluation, the point where "the model said so" stops being good enough and something actually has to verify it.

> A check only counts if it would give a different answer in the world where the claim is false.

That idea runs through most of what I build. I ask the same few questions of every system: What can fail? How do we know this output is correct? Where should a human stay in control? Then I build the part that answers them.

First Class BSc Mathematics (Bristol), finishing an MSc in Business Analytics & AI at Imperial. Years spent tutoring maths, which is where I learned that the hard part isn't giving answers, it's knowing when not to.

### Selected work

**[claim-verification-pipeline](https://github.com/matt-huang1/claim-verification-pipeline)**
A deterministic verification layer for AI-assisted research. The model proposes; code verifies every URL, quote, and figure against primary sources it fetches itself; humans keep the judgment. It attacks itself in CI with spoofed domains and fabricated quotes (7/7 caught), and it found a real port-injection exploit that a separate review had passed as safe. 363 in CI / 380 total, 93% coverage, 27 ADRs.

**[tutor-analytics](https://github.com/matt-huang1/tutor-analytics)**
A full-stack platform that scores free-text answers with an LLM behind a strict policy boundary, then runs deterministic analytics with zero further model calls. Nothing the model returns reaches the database unchecked.

**[volatility-regime-forecasting](https://github.com/matt-huang1/volatility-engine)**
An ML pipeline classifying 30-day forward volatility regimes, built to avoid look-ahead bias and read with SHAP rather than left as a black box.

### Now

Finishing my MSc, consulting on AI implementation for a major global asset manager, and building something small that people can actually use. Open to applied AI and AI engineering roles at small teams building things people rely on.

**[My website](matthuang.dev)** · **[LinkedIn](https://linkedin.com/in/matthew-huang17)** · **[email](mailto:matt@matthuang.dev)** · **[Twitter/X](https://x.com/matthuang_dev)**
