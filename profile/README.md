<p align="center">
  <a href="https://github.com/Proxyabel"><img alt="ProksiAbel" src="https://img.shields.io/badge/ProksiAbel–Active%20Defense-0d1117?style=for-the-badge&logo=github&logoColor=5eead4&labelColor=0d1117&color=5eead4" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Verified-Organization-58a6ff?style=flat-square&logo=github" alt="Verified org" />
  <img src="https://img.shields.io/badge/%F0%9F%93%8D%20Estonia-5eead4?style=flat-square" alt="Estonia" />
  <a href="https://proksiabel.ee"><img src="https://img.shields.io/badge/%F0%9F%8C%90%20proksiabel.ee-a78bfa?style=flat-square" alt="Website" /></a>
  <img src="https://img.shields.io/badge/Since-2022-fb7185?style=flat-square" alt="Since 2022" />
  <img src="https://img.shields.io/badge/Repos-3-9aa3b8?style=flat-square" alt="3 repos" />
</p>

<br />

<h1 align="center">The only real defense is <b>active defense.</b></h1>

<p align="center"><b>ProksiAbel</b> is an independent security research collective from Estonia. We study how client-side anti-fraud and bot-mitigation systems <i>actually break</i> — then publish the hardening that follows. We operate where defenders and attackers meet.</p>

<br />

## 🔭 What we research

We work inside the client-side fraud arms race: the place where a legitimate browser, a hardened headless browser, and an attacker's relay all look identical — until they don't.

| Repository | Type | What it is |
|------------|------|------------|
| [`js-security-research`](https://github.com/Proxyabel/js-security-research) | Fork · 2025 | **"Kits Kärneriks"** — a case study in bypassing client-side anti-fraud. A hardened headless browser mints a valid on-domain BotGuard token, then authorizes a session in a MITM context. |
| [`evilginx.botguard`](https://github.com/Proxyabel/evilginx.botguard) | Owned | Tooling at the seam of phishing frameworks and bot-mitigation — used to reproduce, then harden against, token-relay attack paths. |
| [`.github`](https://github.com/Proxyabel/.github) | Owned | Org-wide defaults, community health files, and the supply-chain baseline. Every repo enforces web commit sign-off. |

<br />

## 📡 2026 — State of the Art

The cat-and-mouse is shifting. These are the movements that shape what "active defense" means next — and where our research lands:

- **AI-agent traffic outnumbers bots.** Fingerprinting moves past JA3/JA4 TLS heuristics toward behavioral attestation of the client runtime.
- **Privacy-preserving detection (PACT).** Private Access Tokens trade device-bound secrets for issuer-signed, unlinkable proofs — catching fraud without surveilling users.
- **Passkeys / FIDO2 dissolve shared-secret phishing.** Client-side anti-fraud pivots from *"is this password real"* to *"is this runtime real."*
- **On-device ML fraud inference.** Models run at the edge to avoid leaking signals to the page — our token-relay research shows why the model can never fully trust the client it runs on.
- **Adversarial ML & synthetic identity.** Deepfake onboarding and model-extraction attacks target the fraud stack itself; robustness is now a research surface.
- **Signed everything (SLSA).** Supply-chain integrity goes from recommendation to requirement — sign-off, reproducible builds, attested artifacts.

<br />

## 🛡 Posture

> Research, not exploit-dumps. Case studies document the bypass *and* the hardening — responsible disclosure by design.

- 🔏 **Web commit sign-off required** across every repo
- ✓ **Verified organization** tied to the ProksiAbel legal identity
- 🧪 **Reproducible, documented** PoCs over noise

<br />

## 🤝 Connect

- 🌐 Website: [proksiabel.ee](https://proksiabel.ee)
- 📫 Email: [info@proksiabel.ee](mailto:info@proksiabel.ee)
- 🐙 Org: [@Proxyabel](https://github.com/Proxyabel)

<p align="center"><sub>The only real defense is active defense.</sub></p>
