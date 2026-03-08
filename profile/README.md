# ✅ BugHunters Platform

**Stop chasing pixels. Ship with confidence.** BugHunters is an InfoSec-friendly AI QA platform that eliminates visual test flakiness using multimodal LLMs, without ever storing your company's UI in the cloud.

🔗 **[bughunters.dev](https://bughunters.dev)** | 💬 **[Contact Sales](mailto:support@bughunters.dev)**

---

## 🛡️ The BugHunters Philosophy

We believe that QA Automation Engineers shouldn't spend 4 hours a week updating visual baselines just because a marketing banner changed or a timestamp updated. But we also know that Enterprise InfoSec will never let you upload your internal dashboards to a 3rd-party cloud.

**Our Core Tenets:**
1. **Zero Cloud Storage:** We are a passthrough evaluator. Your images are encoded to Base64, evaluated in memory by our AI, and immediately discarded. Baselines stay securely in your local Git repository.
2. **AI Data Tolerance:** Our models understand context. We ignore dynamic data (charts, timestamps, 3rd-party widgets) while catching real semantic UI regressions.
3. **Smart Cost Control:** We run a lightning-fast local `pixelmatch` first. If the pixels match, the test passes instantly for $0. We only invoke AI when there is a real visual diff.

---

## 📦 Our Ecosystem

### 🟢 Production Ready
* **[`@bughunters/vision`](https://github.com/bughunters-vision/playwright-client)** — Our core drop-in plugin for Playwright. Replaces `toHaveScreenshot()` with human-like AI evaluation.
* **[`bughunters-playwright-example`](https://github.com/bughunters-vision/bughunters-playwright-example)** — A public quickstart repository. Clone it, add your token, and see the magic in 3 minutes.

### 🟡 Coming Soon (Roadmap)
* **`@bughunters/vision-cypress`** — Bringing InfoSec-friendly AI testing to the Cypress ecosystem (Q3 2026).
* **`bughunters-vision-python`** — Native integration for Robot Framework, targeting Enterprise & Bank environments (Q4 2026).

---

## 🚀 Try it out

Are you struggling with flaky visual tests? Get a **100-Check Corporate PoC Trial** for free.
👉 **[Claim your token at bughunters.dev](https://bughunters.dev)**
