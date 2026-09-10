### Charaf Azzaoui

Product engineer, eight years. Currently technical CPO at an early-stage fintech, where I own product and engineering end to end: I run the customer calls, model the data, design the API and then go build it.

Most of my work is in places where being wrong costs something. Payments, invoices, approvals, KYB, and for the last year an LLM running in production inside a compliance-constrained workflow.

Based in Spain. TypeScript, React, Next.js, Node, Postgres.

---

**[claude-grounded-hooks](https://github.com/chazzaoui/claude-grounded-hooks)**

Evidence grounding, compliance blocking and hashed audit logging as Claude Agent SDK hooks. A model asked to cite its sources will invent identifiers, fluently and in the right format, and a fabricated citation is worse than no citation because it looks like diligence.

The usual answer is a second model call. The check you actually need is set membership: does the id exist in what was retrieved. It takes microseconds and it can't hallucinate.

`6/6 fabricated citations caught · 0 false drops · 0.185ms mean overhead · npm run eval reproduces it on a clean checkout with no API key`

**[exa-freshness-probe](https://github.com/chazzaoui/exa-freshness-probe)**

I was about to build a query-level freshness router on top of a search API, so I spent a morning measuring whether the thing I'd be routing around actually did anything.

It didn't. Cost was flat across every setting and the URLs came back byte-identical, so the server was already picking the freshest thing it had. I published the measurements instead of the project, with the probe scripts so anyone can rerun them. It led to a thread with Exa's engineers and [exa-labs/exa-js#219](https://github.com/exa-labs/exa-js/issues/219).

---

[linkedin.com/in/charaf-azzaoui](https://linkedin.com/in/charaf-azzaoui) · charafazzaoui@gmail.com
