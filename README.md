# Perspective Shield
Building AI course project

## Summary

Perspective Shield is an AI media suite for political commentators. It uses neural facial transforms (like baby filters for dry humor), voice modification, and an AI fact-checking co-pilot to enable safe, disarming global dialogue without exposing real faces.

## Background

Modern political commentary on social media is heavily polarized, reaction-driven, and vulnerable to misinformation. Commentators sharing nuanced, non-mainstream perspectives face severe privacy, social, and legal risks if their real identities are exposed. 

This problem occurs daily across public digital spaces like X, YouTube, and Instagram, driving divisions within communities and families during global crises.

My personal motivation stems from:
* **Deep Self-Reflection:** Encouraging viewers to "listen to digest"—honoring the Xhosa philosophy *indaba ixoxwa ntsukuntsuku* ("important matters take time to talk through").
* **Language as a Cognitive Code:** Highlighting how structural language nuances shape human thinking patterns.
* **Global Lived Experience:** Grounded in living across South Africa, the UK, the UAE, the US, and Poland (10+ years), paired with formal political science education.
* **Early Inspiration:** Growing up sitting alongside my literate grandfather, learning to read upside down from newspapers and exploring his library to read *Religions of the World*. His open responses taught me to trust my own critical judgment over popular consensus.

## How is it used?

The process follows a structured, four-step creation and broadcast workflow:

1. **Creation & Anonymization:** The host records video commentary. The AI pipeline applies neural facial transforms and alters voice timbre.
2. **Editorial & Legal Vetting:** An AI co-pilot reviews the content before export, asking clarifying questions, pointing out logical leaps, and flagging legal risks like defamation.
3. **One-Directional Broadcast:** The finalized clip is published to public social platforms (YouTube, X, Instagram).
4. **Reflective Audience Engagement:** Viewers interact in comment sections guided by a unique prompt: *comment specifically on the opposing view to challenge yourself*.

```mermaid
graph TD
    A[Creator Records Video] --> B[AI Neural Facial Transform]
    A --> C[Voice Timbre Alteration]
    B & C --> D[AI Editorial & Legal Vetting Agent]
    D --> E[Zero-Knowledge Credibility Badging]
    E --> F[One-Directional Broadcast to Social Media]

This solution serves privacy-conscious commentators seeking physical security, while providing global viewers with well-reasoned, disarming perspectives.

## Data sources and AI methods

The project relies on primary video/speech streams from the creator, trusted international legal and fact-checking databases, linguistic datasets for regional idiom translation, and zero-knowledge cryptographic layers for credential verification.

| AI Technique | Function & Implementation |
| ----------- | ----------- |
| Neural Facial Transforms | Generative keypoint models that map facial micro-expressions onto disarming visual filters (e.g., hyper-realistic baby transforms). |
| Voice Timbre Alteration | Audio models that shift vocal acoustics to prevent biometric voiceprinting while preserving speech rhythm and dry humor. |
| Editorial AI (LLM Agent) | Pre-publication pipeline that scans scripts/audio to flag legal risks and present critical counter-arguments. |
| Zero-Knowledge Badging | Cryptographic verification rendering on-screen badges (e.g., "Verified Political Science Scholar") without exposing legal names. |

## Challenges

This project does not solve subjective political disagreements, as political opinions remain inherently open to interpretation. It also cannot eliminate platform-level bot noise in public comment sections. Additionally, the creator must guard against over-relying on the AI editor, ensuring human judgment retains final creative control.

## What next?

The project can grow by developing a real-time AI "Devil's Advocate" proxy that acts as an on-screen interview partner during recording sessions. Future developments also include multi-language neural dubbing into Swahili, Zulu, Polish, Spanish, and Arabic with lip-synchronized avatar movements, alongside building a sustainable creator monetization model.

## Acknowledgments

* **Family Roots:** Inspired by sitting by my literate grandfather’s side reading newspapers upside down, and exploring his library to read *Religions of the World*.
* **Open Inquiry:** Dedicated to my grandfather's willingness to answer genuine questions openly, instilling the confidence to seek my own answers to complex world problems.
* **Cultural Philosophy:** Grounded in the Xhosa principle *indaba ixoxwa ntsukuntsuku*.
* **Open Source Community:** Built using tools from PyTorch, OpenCV, Hugging Face NLP libraries, open-weight diffusion models, and zero-knowledge cryptographic frameworks.
