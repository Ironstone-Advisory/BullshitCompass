# BullshitCompass
The Bullshit Compass project aims to create software that identifies vague, fluffy, syntactically correct but meaningless language ("bullshit") in business texts like memos and pitch decks. Distinct from detecting lies, it focuses on linguistic fog. Development started spec-first (RFC FS02) due to the concept's complexity.
# The Bullshit Compass 🧭

**Detecting the Fluffy, Plausible Fog: A Spec-First Approach to Linguistic Clarity**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Status: Experimental](https://img.shields.io/badge/status-experimental-red.svg)](./spec/FS02_Bullshit_Compass.md) ---

> *"Back in the early internet days... there was this beautifully nerdy ritual called writing an RFC... They were born as documents... Because once you’ve got a solid spec, the code becomes the easy part. (Roughly speaking.)"*

This project is an experiment in building software differently, inspired by the foundational principles of the early internet. We believe that for complex challenges, especially those involving language, meaning, and AI, **specification must come before implementation**.

## The Core Philosophy: Meaning First

In contrast to the common modern approach of hacking together AI models and retroactively defining their purpose, the Bullshit Compass project adheres to a **spec-first methodology**:

1.  **Define the Meaning:** Start by rigorously defining *what* the software should do, its principles, its ontology, and its intended interpretation. This is done through detailed specifications (RFCs - Requests for Comments).
2.  **Seek Frictionless Truth:** A clear spec allows everyone involved to understand and critique the *concept* before investing heavily in code.
3.  **Code Comes After the Soul:** Once the meaning and specification are solidified, the implementation becomes a more focused task of realizing that pre-defined vision.

We believe this approach, potentially part of a "NeoAgile" paradigm, leads to greater clarity, integrity, and ultimately, more meaningful software – and maybe even less bullshit in the world.

## What is the Bullshit Compass?

The **Bullshit Compass (RFC FS02)** is a tool designed to detect **linguistic bullshit**.

* **Not Lies:** It doesn't primarily aim to detect factual inaccuracies or deliberate deception.
* **Not Spam:** It's not focused on unsolicited bulk messages.
* **It Detects:** The *fluffy, plausible, syntactically correct fog* that permeates much of modern communication – pitch decks, strategy memos, corporate jargon, thought leader posts, and managerial speak.

It analyzes text for characteristics such as:
* **Tautologies:** Saying the same thing twice in different words.
* **Over-reliance on Jargon:** Buzzwords used without clear meaning.
* **Vagueness and Ambiguity:** Lack of concrete specifics.
* **"Peterson Weakness":** Our term for camouflaged tautologies combined with ideological injections.
* **Semantic Emptiness:** Sentences or paragraphs that sound good but convey little actual information.

The underlying logic is informed by philosophical work (e.g., Harry Frankfurt's "On Bullshit"), linguistic studies (e.g., Pennycook), and satirical observations (e.g., Ambrose Bierce). The goal is to provide a quantitative and qualitative assessment of text clarity and substance.

* **Read the Draft Specification:** [RFC FS02: The Bullshit Compass](./spec/FS02_Bullshit_Compass.md) *(Link to your spec file)*

## The Fingerprint Spider Platform (RFC FS01)

The Bullshit Compass is one application emerging from a broader approach to **semantic intelligence** and **epistemic traceability**, conceptually underpinned by protocols like the **Fingerprint Spider (RFC FS01)**.

* **What it is:** The Fingerprint Spider defines an experimental protocol for a semantic agent designed to detect, track, and analyze document reuse and linguistic pattern propagation across digital ecosystems. Inspired by the original "finger" protocol, it uses semantic fingerprinting (like trigram analysis) to understand how textual patterns spread.
* **Purpose:** Its primary goal is identifying **semantic reuse** – detecting potential plagiarism, intellectual property drift, or repetitive rhetorical devices, providing traceability in documents.
* **Read the Specification:** [RFC FS01: Fingerprint Spider](./spec/FS01_Fingerprint_Spider.md) *(Link to the provided RFC text, ideally placed in your spec folder)*

### Connection to the Bullshit Compass

Think of the **Fingerprint Spider protocol (RFC FS01)** as defining core principles and mechanisms for a *platform* focused on deep semantic analysis and textual lineage.

The **Bullshit Compass (RFC FS02)** is a *specific application* built upon the same spec-first philosophy and leveraging related semantic analysis techniques. However, its focus is different:

* **Fingerprint Spider:** Detects **reuse** and **propagation** of specific textual patterns.
* **Bullshit Compass:** Detects **semantic emptiness** and **linguistic fog**, regardless of whether the specific phrasing has been reused. It analyzes the *quality* and *substance* of the language itself.

Essentially, the Compass is one type of specialized tool that can emerge from the foundational approach to semantic intelligence exemplified by the Fingerprint Spider platform. Both prioritize understanding meaning within text, but apply that understanding to different problems.

## Project Status: Experimental 🧪

This project is currently **experimental**. The specifications are drafts, and the code is under active development (or planning). We are sharing this early to invite feedback and collaboration, in the true spirit of a Request for Comments.

## Installation

*(Instructions will be added here once the tool is packaged for distribution.)*

```bash
# Example (placeholder):
# pip install bullshit-compass

# Example (placeholder):
# from bullshit_compass import assess
#
# text = "We are leveraging synergistic paradigms to actualize next-generation value-added solutions..."
# score, analysis = assess(text)
# print(f"Bullshit Score: {score}")
# print(analysis)

Specification-Driven Development
This project is committed to a spec-first development process. Please refer to the /spec directory for the governing RFC documents:

RFC FS01: Fingerprint Spider
RFC FS02: The Bullshit Compass
Discussions, critiques, and suggestions regarding the specifications themselves are highly encouraged via GitHub Issues, tagged with spec-discussion or rfc-feedback.

Contributing
We welcome contributions! Please read our CONTRIBUTING.md guidelines to understand how you can participate, report issues, suggest features, and submit pull requests.

Please also adhere to our CODE_OF_CONDUCT.md.

License
This project is licensed under the MIT License. See the LICENSE file for details.

(Replace MIT License and link if you chose a different one)

Acknowledgements & References
This work builds upon ideas from various fields and prior art:

Early Internet RFCs (e.g., RFC 5321, RFC 2616, RFC 742)
Frankfurt, H. (1986). On Bullshit.
Pennycook, G., et al. (on the reception and detection of pseudo-profound bullshit)
Salton, G., et al. (Vector Space Model)
The general spirit of Open Source development.
Initial feedback from @ruv (as mentioned in the original post).
Request for Comments! 😁🧠🤖👾👨‍⚖️👍🤯🎲🪙🃏🙊🙉🙈❤️
What are your thoughts? We believe this way leads to clarity, to integrity—and maybe even to less bullshit.

Open an Issue to share your feedback, critique the specifications, or discuss the underlying philosophy.



