# Known Requirements

## Technical Requirements

- **Platform:** The application must be developed for the Android operating system.
- **Technology Stack:** The project must be built using React Native with the Expo framework.
- **Performance:** The app should be lightweight and responsive, with minimal resource consumption.
- **Extensibility:** The project architecture should be modular to allow for the easy addition of new vulnerability demonstrations in the future.
- **Safety:** All vulnerabilities must be simulated and self-contained within the app. The application must not introduce any actual security risks to the user's device.

## Business Requirements

- **Educate:** To provide a practical, hands-on educational tool for learning about Android and mobile application security.
- **Demonstrate:** To create interactive and easy-to-understand demonstrations of common vulnerabilities.
- **Remediate:** To offer clear, concise guidance and code examples on how to fix and prevent these security flaws.
- **Promote Security Awareness:** To encourage a "security-first" mindset among mobile developers.

## User Requirements

- **Vulnerability Modules:** The application must be structured into distinct modules, with each module dedicated to a specific vulnerability. Initial modules shall include:
  - Insecure Data Storage
  - Hardcoded Secrets
  - Insecure Communication
  - Deep Link Exploitation
  - WebView Injections (XSS)
  - Insecure Logging
- **Educational Content:** For each vulnerability module, the app must have three distinct sections:
  - "The Problem": A clear explanation of the vulnerability and why it is a security risk.
  - "The Attack": A step-by-step guide or interactive element showing how the vulnerability can be exploited in a simulated environment.
  - "The Fix": A description of the secure coding practice or mitigation technique, complete with examples of "bad" vs. "good" code snippets.
- **Navigation:** The app must have a main dashboard or home screen that allows users to easily navigate to any of the vulnerability modules.
- **User Interface (UI):** The UI must be clean, intuitive, and focused on clarity. The primary goal is education, not complex design.
