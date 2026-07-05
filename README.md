# Secura Cloud — Secure Cloud Storage Concept using FHE & ABE

🔗 **Live Demo:** https://riya-kumari06.github.io/Secura-Cloud/
📂 **Repo:** https://github.com/riya-kumari06/Secura-Cloud

Secura Cloud is a mini project born out of research into the **2024 Microsoft global outage**. We studied the incident to identify systemic vulnerabilities in centralized cloud infrastructure — single points of failure, weak access control granularity, and exposure of unencrypted data during downtime — and designed Secura Cloud as a conceptual response to those gaps.

## Research & Motivation

The Microsoft outage exposed how a single faulty update could cascade across millions of systems worldwide, taking down cloud services, airlines, hospitals, and banks simultaneously. Studying this incident, we focused on two core weaknesses:

- **Data exposure risk** during infrastructure failure or breach, since most cloud data isn't processed in encrypted form
- **Coarse access control**, where systems often over-trust anyone with basic access rather than enforcing fine-grained, attribute-based permissions

## Our Approach

Secura Cloud's design is built around two advanced cryptographic techniques:

- **Fully Homomorphic Encryption (FHE)** – allows computation on encrypted data without ever decrypting it, so files remain secure even if the storage layer is compromised.
- **Attribute-Based Encryption (ABE)** – ties file access to specific user attributes/roles rather than a single shared key, enabling fine-grained, policy-driven access control.

Together, these ensure that even in the event of a large-scale outage or breach like the one we studied, encrypted data stays protected and access remains tightly controlled.

## What's in This Build

This project is a UI prototype of the Secura Cloud platform, showcasing the intended user experience:

- **Encrypt & Upload** – file upload flow with encryption status shown at every step
- **File List** – dashboard view of stored files with their encryption status
- **Cloud Node Distribution** – visualizing how files are distributed and load-balanced across multiple secure server nodes
- **Contact Page** – for reaching out regarding the project

## Tech Stack

- HTML, Tailwind CSS
- Hosted on GitHub Pages

## Team

Built as a mini project exploring cloud security through the lens of real-world infrastructure failures.

---

*Secura Cloud — rethinking cloud storage security after studying what happens when it fails.*
