This organization contains the public archives of my course projects from SMU.

Particularly notable projects:

Schneider Electric AI-Assisted Time-Series Analytics | CS 5351 (Spring 2026)

Repository link: [Private access only](https://github.com/matthewrbenedict/SchneiderElectricTimeSeries)

* Led Agile sprint planning and stakeholder communication for a 4-person team across 3 data centers, adapting project backlog based on live end-user feedback from expanded stakeholder demos.
* Integrated GPT-4.1 mini to convert natural language queries into SQL-like filters, enabling non-technical business users to automate property comparisons across ~100 assets (100k+ data points). 
* Built an unsupervised TensorFlow Isolation Forest model to auto-flag telemetry outliers and established persistent labeling for future ML automation. 
* Re-prioritized core feature deliverables under strict deadlines and engineered a post-deployment patch to satisfy newly identified client cross-property requirements while enforcing mypy/pylint static analysis across 37 files.

SharkBudget C2 vs. Layered System Architecture | CS 7319 (Spring 2026)

Repository link: [Public access](https://github.com/realMatthewBenedict-SMUArchive/CS7319-SharkBudget)

* Engineered a heterogeneous Component-and-Connector (C2) system architecture for a cross-platform desktop budget tracking application, pairing a Flutter/Dart frontend with a high-performance C backend engine and SQLite storage.
* Architected a custom C message-dispatch router using structured request handlers to process asynchronous JSON/string payloads for user authentication, transactional CRUD operations, and cash-flow reports.
* Conducted an empirical architectural trade-off evaluation comparing C2 against a homogeneous JavaFX/Java 21 layered reference implementation, analyzing message-serialization overhead, structural complexity (37 components vs. 13 classes), and maintenance trade-offs between decoupled event-driven systems and monolithic desktop designs.

BabelElephant Audio Denoising Pipeline | HackSMU VII (April 2026)

Repository link: [Public access (outside organization)](https://github.com/matthewrbenedict/BabelElephant)

* Engineered an end-to-end Python machine learning pipeline in a high-velocity hackathon setting (60%+ commits, 24-hour deadline), processing 40 multi-channel audio recordings (212 embedded calls) with complex noise structures.
* Designed DSP feature extraction workflows converting audio to spectrogram tensors via STFT, training a Convolutional Neural Network (CNN) to detect, isolate, and evaluate acoustic noise components.
* Reconstructed cleaned audio via inverse STFT (iSTFT) magnitude masking while preserving phase integrity, establishing reproducible ML workflow documentation for team enablement.
* Pitched final technical demo live to competition judges and attendees, detailing real-time audio filtering and signal preservation.

Timeout iOS UI/UX & Systems Architecture Project | CS 5312 (Fall 2025)

Repository link: [Public access (personal account)](https://github.com/UInt2048/Timeout)

* Designed and prototyped a SwiftUI iOS application applying user-centered design (UCD) principles to visualize low-level system datetime boundaries, epoch overflows, and CoreFoundation timer instability.
* Conducted expert cognitive walkthroughs and empirical usability testing across representative user evaluation sessions using UMUX frameworks to identify navigation friction and cognitive load bottlenecks.
* Iterated from low-fidelity paper sketches to high-fidelity Xcode simulator prototypes, refining hierarchical navigation, color-coded temporal visual metaphors, and system clock telemetry displays.

Social Media Analysis Database System | CS 5330 (Spring 2025)

Repository link: [Public access](https://github.com/realMatthewBenedict-SMUArchive/CS5330-DB-Project)

* Partnered cross-functionally in a 3-person team to design a MySQL relational database application, implementing composite primary keys and foreign key cascading constraints to store cross-platform social media posts and research analysis fields.
* Engineered backend RESTful API endpoints in Next.js using Node.js and mysql2 for user CRUD operations, post management, and dynamic filtering by date range, platform, username, and poster identity.
* Constructed interactive UI components in React/TypeScript for editing/deleting posts using custom modal dialogs, diagnosing and resolving edge-case datetime parsing bugs directly prior to code freeze.

MustangsMatter Health & Wellness Platform | HackSMU VI (October 2024)

Repository link: [Public access](https://github.com/realMatthewBenedict-SMUArchive/MustangsMatter)

* Awarded 3rd place in the SMU OIT Challenge out of competitive hackathon entries under a 24-hour deadline by architecting a comprehensive student health and wellness web application.
* Integrated an AI chatbot powered by HuggingFace LLMs to enable personalized health goal setting and automated referrals to SMU mental health, fitness, and telemedicine resources.
* Engineered backend database pipelines using Python and MongoDB, implementing secure user authentication and session management via PropelAuth API services.
