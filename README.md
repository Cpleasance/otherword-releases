# Otherword: Local Privacy Proxy for LLMs

[![Download for Windows](https://img.shields.io/badge/Download-Windows%20Installer-blue?style=for-the-badge&logo=windows)](https://github.com/Cpleasance/otherword-releases/releases/latest/download/Otherword-Setup.exe)
[![Latest Release](https://img.shields.io/github/v/release/Cpleasance/otherword-releases?style=for-the-badge)](https://github.com/Cpleasance/otherword-releases/releases/latest)

Otherword is a local privacy proxy and pseudonymous gateway for large language models. It intercepts prompts, detects sensitive PII, substitutes them with deterministic context-aware fake identities locally, verifies outbound wire payloads through a leak canary, and transparently restores real identities upon LLM response.

---

## Download & Installation

Click the download button above or grab the latest setup executable from the **[Releases](https://github.com/Cpleasance/otherword-releases/releases/latest)** tab:

1. Download **`Otherword-Setup.exe`**.
2. Run the installer and follow the on-screen setup wizard.
3. Launch **Otherword** from your Desktop or Start Menu.

### System Requirements
* **Operating System:** Windows 10 or Windows 11 (64-bit)
* **Memory:** Minimum 4 GB RAM (8 GB recommended for local neural models)
* **Storage:** ~500 MB free disk space
* **Browser:** Microsoft Edge or Google Chrome (used in native standalone app mode)

---

## Key Features

* **Zero-Leak Guarantee:** Real identities never leave your device unencrypted. Outbound traffic is actively monitored with canary tokens.
* **Seamless LLM Integration:** Works transparently with Anthropic Claude, OpenAI, Ollama, and custom endpoints.
* **Deterministic Pseudonymization:** Entities (names, emails, phone numbers, API keys) are replaced with context-consistent substitutes and restored automatically when responses return.
* **Native Desktop Experience:** Runs silently in the background with a zero-terminal UI.

---

## Support & Reporting Issues

If you encounter any bugs, crashes, or unexpected detection behavior, please submit an issue on the [Issue Tracker](https://github.com/Cpleasance/otherword-releases/issues).
