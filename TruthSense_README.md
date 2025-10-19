TruthSense: Agentic AI System for Misinformation Detection
A High-Integrity Fact-Checking Paradigm
Developed for MumbaiHacks 2025

Team VeritasAI – Kunal Parmar: Lead Developer, API integration and database & Nisha Sarvaiya: Backend Engineer, Agent workflow and testing.

I. Executive Summary
TruthSense is engineered as a robust, agentic AI platform designed to mitigate the rapid proliferation of misinformation across digital channels. Leveraging the power of Google's foundational models (Gemini API) and Search Grounding, the system establishes a new standard for real-time veracity validation. It does not merely detect keywords; it executes a multi-step verification workflow to deliver transparent, credible, and contextually grounded fact-check reports.

II. System Architecture & Core Innovation
Our core innovation lies in the three-stage Agentic Workflow and the use of Structured JSON Output enforced by the Gemini API.

A. Core Agentic Workflow
Stage
Agent Role
Key Functionality
1. Collection & Validation
Collector Agent
Continuously monitors data streams (simulated here via user input) and isolates specific, verifiable claims.
2. Grounding & Synthesis
Verifier Agent
Leverages Google Search Grounding (via Gemini API) and external APIs (simulated: Google Fact Check, PIB) to find and weigh conflicting or supporting evidence.
3. Reporting & Dissemination
Summarizer Agent
Generates a concise, objective explanation, and enforces a mandatory Structured JSON Schema for machine-readable output.

B. Unique Technical Features
Strict Structured Output: We mandate a JSON schema for the AI's final report (verdict, confidence, actionableSteps). This ensures predictable, robust parsing and prevents the common failure mode of unformatted LLM text.
Robust Error Handling: The application includes advanced, self-reporting error states to immediately diagnose API failure modes, network issues, and JSON parsing errors, demonstrating high code maturity.
Scalability Architecture: The system is explicitly decoupled, ready for integration with dedicated Firebase/MongoDB for multi-user history and persistent state management, as indicated by the built-in user authentication placeholders.

III. Technology Stack & Implementation
Layer
Primary Tool
Rationale for Selection
AI Foundation
Gemini 2.5 Flash API
Chosen for its superior reasoning capabilities, low latency, and native support for Google Search Grounding.
Front-End / UI
HTML5, Tailwind CSS
Single-file architecture for rapid prototyping and deployment; Tailwind ensures a fully responsive, modern design paradigm.
Data Verification
Google Search Grounding
Enables real-time, up-to-the-minute verification against the live web, crucial for emerging misinformation.
Future Integration
Firebase Auth & Firestore
Placeholder initialization code demonstrates architectural readiness for user-specific claim history and a community trust layer.
Languages
HTML, CSS (Tailwind), JavaScript (ES6)
Standard, high-performance web languages.

IV. Project Demonstration & Validation
The application features a Live/Dummy Mode Toggle to facilitate validation.
Dummy Mode (Default): Used for stable testing of UI presentation and demonstrating the end-to-end report structure without reliance on external APIs.
Live API Mode (Toggled): Executes the full Agentic workflow, including the API call with Search Grounding and JSON schema enforcement, validating the real-time detection capability.
Code Validation Features
Feature
Architectural Significance
Simulated Steps
Visually demonstrates the 3-stage Agentic reasoning loop during the loading process.
JSON Pre-Parser
Implements defensive coding by stripping external markdown fences, preventing the common SyntaxError: Unexpected end of input.
Verbose Debugging UI
In the event of an error, a detailed failure report (including the error stack) is displayed, proving comprehensive error management.

V. Societal Impact and Scalability
TruthSense is immediately deployable as a widget or API service. Its potential societal impact is highest during large-scale events or crises where automated verification speed is critical. The design anticipates expanding into a full Crisis Mode Dashboard and multi-lingual bot system, fulfilling the core challenge of MumbaiHacks 2025 by delivering timely, verified truth.
