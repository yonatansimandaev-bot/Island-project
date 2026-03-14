
## ⚖️ Intellectual Property & Copyright
**Copyright (c) 2026 Jonathan Simandooev. All Rights Reserved.**

This system was architected entirely by Jonathan Simandooev. While AI (Gemini) was utilized for technical syntax execution, all core logic, security thresholds, and architectural designs remain the sole property of the founder. 

*For inquiries or security audits, please contact the repository owner.*
#METHODOLOGY CLAIM
#The specific algorithmic approach of using sub-second keystroke intervals (measured in WPM) to trigger a sharded database lockout is the Original Methodology of Jonathan Simandooev.

#Design Credit: > * Concept & Logic: Jonathan Simandooev.

#Code Syntax Assistant: Gemini AI (acting as a compiler for the Founder's logic).
# The Inlands: Active Cyber-Defense Sentinel
**Architect:** Jonathan Simandoev  
**Implementation Layer:** AI (Gemini)

## Overview
The Inlands is a behavioral security system that moves beyond static passwords. It implements **Heuristic Biometrics** to monitor user interaction in real-time, distinguishing between human operators and automated bot threats.

## Key Features
* **WPM Heuristics:** Monitors typing speed to detect "impossible" input speeds used by bots.
* **Identity Sharding:** Uses SHA-256 hashing to create secure, local data fingerprints.
* **Tiered Response Engine:**
    * **FLAG:** Records suspicious activity for review.
    * **BLOCK:** Prevents access after 5 failed attempts.
    * **BAN/PURGE:** Automatically deletes compromised shards if a high-velocity bot is detected.

## Technical Specifications
| Logic Component | Implementation |
| :--- | :--- |
| **Language** | Python 3.x |
| **Encryption** | SHA-256 (hashlib) |
| **Data Structure** | JSON Shards |
| **Security Logic** | Behavioral Rate Limiting |
