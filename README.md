# SPM-SeCTIS: Severity Pattern Matching for Secure Computable Threat Information Sharing in Intelligent Additive Manufacturing

## Overview

The paper focuses on addressing the security and privacy challenges associated with Cyber Threat Intelligence (CTI) sharing in Intelligent Additive Manufacturing (IAM) environments. IAM systems, which integrate advanced technologies like AI and IoT, face significant cybersecurity risks. Sharing threat intelligence across organisations is crucial for enhancing cybersecurity, but existing methods often fail to protect sensitive data. The paper proposes a solution called Severity Pattern Matching for a Secure Computable Threat Information Sharing System (SPM-SeCTIS), which preserves privacy while enabling the secure exchange of cyber threat information.

## Research Problem

Cyber Threat Intelligence (CTI) sharing plays a crucial role in strengthening cybersecurity defenses across organizations, particularly in Identity and Access Management (IAM). However, existing CTI-sharing systems face significant challenges that hinder effective and secure information exchange.

 -- Confidentiality_: Ensuring that shared threat intelligence does not expose sensitive details about the severity of threats or the specific systems affected.
 -- Privacy of Subscriber Interests_: Preventing adversaries from inferring which threats organizations are actively monitoring, which could expose security priorities and vulnerabilities.
 -- Anonymity of the Publisher_: Protecting the identity of organizations reporting incidents to prevent potential retaliation, reputational damage, or targeted attacks.

These challenges create a trade-off between collaboration and security, making it difficult for IAM organizations to share critical threat intelligence without risking exposure of sensitive operational data. Addressing these limitations is essential to fostering a more secure and cooperative cybersecurity ecosystem.


## Motivation

Cyber threats pose a significant risk to the AM industry, with potential consequences like disruptions in production, theft of intellectual property, and reputational damage. Effective information sharing is crucial for combating these threats, but concerns about data privacy can hinder collaboration. The BEPTIS framework aims to overcome this obstacle by providing a secure and confidential platform for AM organizations to share and analyze threat intelligence.

## Contrbution
SPM-SeCTIS do following:

- Enable privacy-preserving threat information sharing by using techniques like Homomorphic Encryption (HE) and Format-Preserving Encryption (FPE).
- Allow intermediaries to process and forward encrypted threat information without accessing or revealing sensitive details.
- Use distributed ledger technology (private blockchain) to ensure tamper-proof and secure communication.
- Facilitate secure threat evaluation and sharing between trusted stakeholders while maintaining privacy.


## Key Findings

The report highlights several key findings regarding the SPM-SeCTIS framework:

- SPM-SeCTIS effectively preserves privacy by encrypting threat data during computation, evaluation, and sharing.
- It allows for the anonymisation of the publisher's identity and ensures that sensitive information like threat severity is not exposed during the threat matching process.
- Performance analysis shows that the system operates efficiently with minimal encryption/decryption overhead and supports real-time threat intelligence sharing, making it scalable for large IAM environments.
- The system provides significant improvements over existing CTI sharing mechanisms by addressing privacy concerns without compromising functionality or security.


