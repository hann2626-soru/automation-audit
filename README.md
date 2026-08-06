# Automation Audit

**A free tool that shows a freelancer's client exactly how many hours — and dollars — are stuck in repetitive admin, and which tasks are actually worth automating.**

→ **[Open the tool](https://hann2626-soru.github.io/automation-audit/)** (no signup, runs in your browser, EN / 日本語 / ES)

Most "automate your business" advice tells you to automate repetitive tasks. That's how people burn a weekend automating invoicing — the task that *feels* worst — and get 40 minutes back. This tool scores each task the way it actually matters:

- **Can a machine reach the inputs?** (or do they live in your head?)
- **Is it safe if it's occasionally wrong?** (a wrong invoice loses a client; a rough draft doesn't)
- **Is it the same routine every time?** (or a fresh judgment call?)

A task is only worth automating if all three hold — so it's ranked by its **weakest** answer, not an average. Then it prices the recoverable hours at your real rate. Every number comes from your inputs; nothing is invented.

## Why it exists

This is the diagnostic from **The 8-Hours-a-Week-Back AI Automation Audit**, packaged as a tool. The tool finds *where* the hours are. The guide walks you through the full 90-minute audit, the scoring rubric in depth, and the three builds that recover the time.

## Selling automation to clients?

The reason freelancers stay underpaid isn't skill — it's positioning. If you send a client a scored diagnostic like this *before* you quote, you stop competing on a price list and start selling the outcome. That move, and the scripts around it, is the whole point of the ladder these come from:

| | |
|---|---|
| **Free** | This tool — send a client their number |

## How it works

Single self-contained HTML file — no build, no backend, no tracking. The scoring engine (cost math + weakest-link ranking) runs client-side in JavaScript. Fork it, host it, embed it, white-label it for your own clients.

- `index.html` — the whole tool
- Method fidelity: the engine reproduces the guide's worked example (invoicing scores as *do-not-automate* — the trap most rankings get backwards)

## License

MIT — use it, change it, ship it.
