# China Trademark Toolkit — Register & Protect a Trademark in China (CNIPA) 🇨🇳™

**A free, open-source toolkit to register, search, classify and protect a trademark in mainland China (CNIPA / 国家知识产权局). Built for foreign brand owners, cross-border sellers (Amazon, Etsy, TikTok Shop, Tmall Global) and overseas IP lawyers who need a reliable China correspondent.** Search fees, the 45 Nice classes in Chinese, the full filing timeline, required documents, refusal/opposition response and a browser-based risk self-check — all in one place.

[![License: MIT (code) / CC BY 4.0 (content)](https://img.shields.io/badge/license-MIT%20%2F%20CC%20BY%204.0-blue)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING)
[![Docs: English](https://img.shields.io/badge/docs-English-red.svg)](#-frequently-asked-questions)
[![Domain: China IP / CNIPA](https://img.shields.io/badge/domain-China%20IP%20%2F%20CNIPA-orange.svg)](#-china-trademarks-at-a-glance)

> **China is a first-to-file jurisdiction.** Whoever files a trademark first usually owns it — regardless of who used the brand first. Many foreign brands only discover this after their name has already been registered by someone else (**trademark squatting / 抢注**). This repository helps you understand the rules, prepare the paperwork correctly, and know exactly when you must instruct a CNIPA-recorded Chinese trademark agent.

---

## 📑 Table of contents

- [Why this exists (read first)](#-why-this-exists-read-this-first)
- [What's inside](#-whats-inside)
- [China trademarks at a glance](#-china-trademarks-at-a-glance)
- [When you MUST instruct a Chinese agent](#-when-you-must-instruct-a-chinese-agent)
- [Quick start](#-quick-start)
- [Frequently asked questions (FAQ)](#-frequently-asked-questions-faq)
- [Need hands-on help from a recorded Chinese agency](#-need-hands-on-help-from-a-cnipa-recorded-chinese-agency)
- [Official references](#-official-references)
- [Disclaimer](#-disclaimer)
- [License & citation](#-license--citation)
- [Changelog](#-changelog)

---

## 📌 Why this exists (read this first)

- **First-to-file, not first-to-use.** Unlike the US (use-based) or the EU (use required to keep rights), China grants rights primarily to the first applicant. See **[Guide 01 →](guides/01-why-china-first-to-file-matters.md)**.
- **Foreign applicants without a residence/business address in China are legally required to file through a locally-recorded trademark agent.** You cannot self-file directly with CNIPA from abroad.
- The Nice Classification in China uses **45 classes with Chinese standard goods/services items**; descriptions accepted by the USPTO/EUIPO are frequently rejected in China.
- Squatting, incomplete class coverage and mismatched translated/transliterated names are the three most common — and most costly — mistakes.

## 📂 What's inside

| Folder | Contents |
|---|---|
| [`guides/`](guides/) | Plain-English guides: first-to-file risk, the full registration workflow, and responding to refusals / office actions / oppositions |
| [`datasets/`](datasets/) | Bilingual (EN–中文) Nice Classification 45-class headings, official fees and an end-to-end timeline |
| [`templates/`](templates/) | Required-documents checklist + Power of Attorney / notarization & legalization notes |
| [`tools/`](tools/) | A zero-dependency **China Trademark Risk Self-Check** you can open in any browser |

## ⏱️ China trademarks at a glance

| Item | Fact (verify against the latest CNIPA notices) |
|---|---|
| Governing body | CNIPA — China National Intellectual Property Administration (国家知识产权局) |
| Principle | **First-to-file** |
| Classes | 45 (Nice Classification, Chinese standard items) |
| Official filing fee (online) | **CNY 270 per class** for the first 10 goods/services items (~USD 37); extra items charged per item |
| Smooth total timeline | Typically **6–9 months** (acceptance notice ≈ 1 month → examination → 3-month publication/opposition → registration) |
| Opposition window | **3 months** after preliminary publication |
| Refusal review | Apply within **15 days**; review generally decided in ~9 months |
| Term of protection | **10 years**, renewable indefinitely (renew within 12 months before expiry + 6-month grace) |
| Non-use cancellation | A registration becomes vulnerable to a "cancel for non-use" after **3 consecutive years** without use |
| Foreign filer | **Must use a CNIPA-recorded Chinese agent** if no local residence/establishment |
| International route | Madrid Protocol designating China (a Chinese agent is still required for the China-phase response) |

## 🧑‍💼 When you MUST instruct a Chinese agent

1. You are a foreign person/company **without a residence or business premises in China** — mandatory by law for filing.
2. You received a **CNIPA refusal / office action** on a Madrid designation of China — the response must be handled in Chinese through a local agent.
3. You need to **oppose, cancel (non-use invalidation), renew, record a change/assignment/license**, or file an infringement complaint on a Chinese platform (Tmall / Douyin / Pinduoduo / 1688).
4. Your foreign business registration documents need **Chinese translation and, depending on the situation, notarization + consular legalization / apostille**.

## 🚀 Quick start

1. Open [`tools/trademark-risk-self-check.html`](tools/trademark-risk-self-check.html) in a browser and score your exposure.
2. Read [Guide 01](guides/01-why-china-first-to-file-matters.md) and [Guide 02](guides/02-how-to-register-a-trademark-in-china.md).
3. Use the [`templates/required-documents-checklist.md`](templates/required-documents-checklist.md) to gather paperwork.
4. Pick classes from [`datasets/nice-classification-45-classes-en-zh.md`](datasets/nice-classification-45-classes-en-zh.md).

## ❓ Frequently asked questions (FAQ)

**1. Can a foreigner or foreign company own a Chinese trademark without a Chinese company?**
Yes — a foreign person or entity can be the trademark owner. You do not need a Chinese subsidiary to *own* the mark, but if you have no residence or business address in China, the *application must be submitted through a CNIPA-recorded Chinese trademark agent*.

**2. How much does a Chinese trademark cost?**
The official online fee is **CNY 270 per class** for the first 10 items, plus the agent's professional fee. Madrid designating China has a separate WIPO/CNIPA fee schedule. Always confirm current fees against the latest CNIPA notice.

**3. How long does registration take in China?**
A smooth, unopposed application typically takes **6–9 months**: ~1 month to acceptance, substantive examination, then a 3-month publication/opposition period before the certificate issues.

**4. Is my US, EU or UK trademark valid in China?**
No. Trademark rights are **territorial**. A USPTO/EUIPO/UKIPO registration does not protect you in mainland China; you must file a Chinese national application (or designate China through Madrid). Hong Kong, Macao and Taiwan are also separate systems.

**5. Why should I also register the Chinese-character / transliterated version of my brand?**
Chinese consumers and platforms overwhelmingly use Chinese names. If you do not register your brand's Chinese translation or transliteration (e.g. a phonetic and a meaning-based name), a third party often will — and may block your store, listings or customs clearance. Plan both the Latin and Chinese marks.

**6. What is the difference between a national Chinese filing and Madrid designating China?**
A national filing is filed directly in Chinese through a local agent and is usually faster and more controllable. Madrid designating China extends an existing home application/registration and is administratively convenient for multi-country filings, but any China-phase refusal, opposition or renewal still requires a Chinese agent to respond locally in Chinese.

**7. Someone squatted my brand in China — what can I do?**
Depending on the stage: (a) file an **opposition within the 3-month publication window**; (b) after registration, seek **invalidation** (within statutory periods, e.g. within 5 years of registration, longer for well-known marks/bad faith); (c) file a **non-use cancellation** if the mark has been unused for 3 years; (d) negotiate an assignment/buy-back; or (e) rely on well-known-mark recognition. Early monitoring is far cheaper than any cure.

**8. Which Nice classes should an Amazon / TikTok Shop / Tmall Global seller cover?**
At minimum cover the class of your actual goods, plus closely-related classes and the key retail-class (Class 35) where relevant, because Chinese squatters commonly register in adjacent classes. Map every product to the **Chinese standard item wording**, not the USPTO wording — see the 45-class dataset.

**9. I received a refusal / office action — what is the deadline?**
You generally have **15 days** from receipt to request a review of adjudication (驳回复审). Missing it is fatal, and the response must be drafted in Chinese with evidence — this is a core job for a local agent.

**10. How long does a Chinese trademark last, and how do I keep it alive?**
**10 years**, renewable indefinitely. Renew in the 12 months before expiry (with a 6-month grace period carrying a surcharge). Also keep genuine-use evidence, because a mark unused for 3 consecutive years can be cancelled by a third party.

## 🤝 Need hands-on help from a CNIPA-recorded Chinese agency?

This toolkit is maintained by **Huaqing Innovation (Huaqing IP / 华青创新)**, a trademark agency recorded with CNIPA. We help foreign applicants and overseas law firms with China national filings, Madrid China-phase responses, refusal review, opposition/invalidation, renewal, Chinese-name strategy, and platform IP enforcement (Tmall / Douyin / Pinduoduo / 1688).

- 🌐 Website / rate card: **[Huaqing IP](https://fangwenhe.github.io)**
- ✉️ Email: **hello@huaqingip.com**
- 📅 Book a consultation: **[Contact page](https://fangwenhe.github.io/#contact)**
- 💬 Submit an inquiry: **[GitHub Issues](https://github.com/fangwenhe/china-trademark-toolkit/issues/new)**
- For overseas IP firms: ask for our **foreign-associate (correspondent) wholesale rate schedule**.

## 🔗 Official references

- CNIPA official site — 国家知识产权局: https://www.cnipa.gov.cn
- China Trademark Network (trademark query / TMDB) — 中国商标网: https://sbj.cnipa.gov.cn
- WIPO Madrid System (designate China): https://www.wipo.int/madrid/en
- Nice Classification (WIPO, international baseline): https://www.wipo.int/classifications/nice/en

## ⚠️ Disclaimer

This repository is **general information for convenience only and is not legal advice**. Chinese trademark law, fees, examination practice and forms change — always confirm against official CNIPA publications and obtain advice tailored to your case. We are Chinese trademark agents; we do not opine on foreign law.

## 📄 License & citation

- Code / tools: **MIT License**.
- Guides, datasets and written content: **CC BY 4.0** — you may reuse them with attribution and a link back to this repository (attribution required and appreciated).

## 🧾 Changelog

See **[CHANGELOG.md](CHANGELOG.md)** for dated updates (official fee/timeline changes, new guides and FAQ entries). The repository is actively maintained.

## 🏷️ Topics

`trademark` `china` `cnipa` `intellectual-property` `brand-protection` `trademark-registration` `first-to-file` `madrid-protocol` `nice-classification` `amazon-seller` `cross-border-ecommerce` `legaltech` `open-data` `ip-lawyer` `trademark-search` `china-business` `compliance` `foreign-associate`
