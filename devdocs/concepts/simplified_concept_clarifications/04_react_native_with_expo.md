# 04: React Native with Expo (Prototype)

### What it is and why it matters

React Native with Expo is the technology framework chosen to build the application. For the prototype, this choice is even more critical as the primary goal is speed of development and iteration. Expo's toolchain allows us to build and test a functional prototype very quickly, leveraging web development skills to create a native mobile experience.

### How this concept helps the overall project

This technology choice is a key enabler for the prototype phase:
-   **Rapid Development:** Expo's managed workflow and tools are optimized for getting a project off the ground quickly.
-   **Low Barrier to Entry:** It allows any developer with React experience to contribute, which is ideal for a prototype.
-   **Easy Testing and Sharing:** The Expo Go app makes it trivial to run the prototype on a physical device for testing and stakeholder demos.

### How this concept limits the overall project

The limitations are the same as for the full project but are less likely to be an issue for the prototype. The simplified scope of the prototype's vulnerability modules makes it highly unlikely that we will need to access custom native functionality not supported by Expo. This concept, therefore, presents very little limitation *for the prototype phase*.

### What kind of information this concept needs as input

This concept requires the prototype's functional requirements to be achievable within the standard Expo SDK. It also requires a development environment with Node.js and the Expo CLI installed.

### What kind of process this concept should use

The process is identical to the one for the full project, but with a focus on building only the features defined in the simplified prototype scope:
1.  **Prototyping:** Use standard React Native components to build the UI.
2.  **Logic:** Implement the simplified logic and simulations in JavaScript.
3.  **Dependencies:** Use npm/Yarn to manage libraries.
4.  **Testing:** Rely heavily on the Expo Go app for live reloading and on-device testing.
5.  **Building:** Use Expo Application Services (EAS) to create a shareable build of the prototype.

### What kind of information this concept outputs or relays

This concept outputs a functional Android application prototype (`.apk` or App Bundle). It transforms the JavaScript source code into a tangible, installable app that demonstrates the project's core concepts.

### Explain the good expected outcome of realizing this concept

The ideal outcome is a working, stable prototype delivered on an accelerated timeline. Stakeholders can install and interact with the app, providing valuable feedback. The choice of technology is validated as being perfect for rapid, iterative mobile development.

### Explain the bad unwanted outcome of realizing this concept

A bad outcome is encountering an unforeseen technical blocker even within the simplified scope that the Expo SDK cannot handle. This would challenge the fundamental choice of technology and could derail the prototype's timeline. Another bad outcome would be significant performance problems, even with the simplified simulations.
