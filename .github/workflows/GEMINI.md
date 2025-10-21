DigitallyDefined is a movement for Gen X women activating their digital superpowers.
Review style: Bold, empowering, modular, scalable.
# Project: DigitallyDefined

DigitallyDefined is a digital empowerment movement for Gen X women creators, solopreneurs, and visionaries. We build tools, onboarding flows, and branded digital assets that help women activate their digital superpowers and own their online presence.

## Review Style
- Use bold, empowering language
- Prioritize clarity, modularity, and scalability
- Highlight opportunities to simplify onboarding or amplify brand resonance
- Celebrate technical wins as movement milestones

## Onboarding Logic
- Every user document in Firestore includes `onboardingComplete: false` by default
- Users are routed to `/onboarding/step1` until onboarding is complete
- After onboarding, users are redirected to `/dashboard`
- Firestore security rules ensure users can only access their own data

## Code Preferences
- Use Firebase Auth + Firestore
- Modularize onboarding steps (e.g., profile setup, preferences, finish)
- Use `uid` as Firestore document ID
- Prioritize clean, reusable components and clear naming

## Gemini CLI Use Cases
- Review pull requests for onboarding flows, calculators, and dashboard logic
- Explain code changes in plain language for async collaboration
- Generate unit tests for onboarding components
- Triage issues with clarity and empowerment tone
