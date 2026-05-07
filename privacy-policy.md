# Privacy Policy

**Effective date:** May 4, 2026
**Last updated:** May 4, 2026

This Privacy Policy explains how Becom ("Becom," "we," "us," or "our") collects, uses, and protects information when you use the Becom mobile application (the "App"). The App is operated by Becom, LLC, an Idaho limited liability company ("we" / "operator").

If you have questions about this policy, contact us at **support@becom.app**.

---

## 1. Information We Collect

We collect only the information needed to make Becom work for you. Specifically:

### 1.1 Account information
- **Email address and password** — used to create and authenticate your account. Passwords are never stored in plaintext; authentication is handled by our backend provider, Supabase, which stores passwords as salted hashes.
- **Apple ID identifier (optional)** — if you sign in with Apple, we receive a unique identifier from Apple. We do not receive your Apple password.

### 1.2 Profile and preference data
You provide this during onboarding and in settings:
- Your selected goals (e.g., energy, fitness, focus, sleep, mental health, relationships, productivity)
- Coaching style preference (direct, supportive, analytical, balanced)
- Difficulty preference (small wins, steady progress, challenge me)
- Onboarding status

### 1.3 Habit and activity data
- Habits you create (name, emoji, frequency, optional counter targets)
- Daily completion records and streak counts
- Notification preferences and reminder settings

### 1.4 Coaching conversation data
- Text messages you exchange with the AI coach
- Reflections, journal-style entries, and any free-text input you provide
- A long-term memory summary the AI maintains about you (your stated goals, struggles, preferences, and patterns) to provide continuity across sessions
- For voice coaching sessions (when this feature is available): audio of what you say during the session is streamed in real time to ElevenLabs for speech recognition and response generation. Becom does not retain raw audio recordings on its own servers; ElevenLabs may retain audio and transcripts according to its own retention policies (see ElevenLabs' privacy policy).

### 1.5 Subscription and purchase information
- Subscription tier, status, trial state, and entitlements — managed by RevenueCat
- We do **not** receive or store your credit card number, full payment details, or Apple ID password. Apple processes all payments; we receive only a transaction identifier and entitlement status.

### 1.6 Device and technical data
- Device type, operating system version, app version, and language/locale settings
- Crash reports and error logs (no personal content included)
- Approximate timezone, used to schedule reminders correctly

### 1.7 Health data (optional, only if you grant permission)
If you enable health sync on iOS, the App reads from Apple HealthKit:
- Step count
- Sleep analysis
- Mindful sessions

This data is read locally on your device to support habit completion checks. **Health data is not transmitted to our servers and is not shared with third parties.** You can revoke this permission at any time in iOS Settings → Privacy & Security → Health.

### 1.8 Microphone access (optional, only if you use voice coaching)
We request microphone access only when you start a voice coaching session. Audio is used solely for the live conversation and is not used for advertising or training third-party AI models without your consent (see Section 3).

---

## 2. How We Use Your Information

We use the information described above to:
- Create and maintain your account
- Generate your daily focus, AI coaching responses, and personalized insights
- Maintain longitudinal "memory" so the AI coach can refer back to your goals and history in future sessions
- Schedule reminders and send notifications you've enabled
- Process subscriptions, free trials, and entitlement checks
- Diagnose bugs, monitor service health, and improve the App
- Comply with legal obligations and enforce our Terms of Service

We do **not** sell your personal information. We do **not** use your data for cross-app advertising or share it with data brokers.

---

## 3. Third-Party Service Providers

Becom relies on the following third-party services to function. Each receives only the data necessary for its role:

| Provider | Purpose | Data shared |
|---|---|---|
| **Supabase** (Supabase Inc., USA) | Backend database, authentication, edge functions | Account credentials, habit data, conversation history, AI memory |
| **OpenAI** (OpenAI, L.L.C., USA) | Generates text coaching responses (GPT-4o-mini) | Your messages, relevant memory summaries, current habit context. Per OpenAI's published API terms at the time of writing, API data is not used to train OpenAI's models. |
| **Anthropic** (Anthropic PBC, USA) | Alternate model for some coaching responses | Same as above. Per Anthropic's published API terms at the time of writing, API data is not used to train Anthropic's models. |
| **ElevenLabs** (ElevenLabs Inc., USA) | Voice coaching: speech-to-text and AI voice responses | Live audio stream during voice sessions, agent configuration |
| **RevenueCat** (RevenueCat, Inc., USA) | Subscription management and entitlement verification | Anonymous user ID, subscription state, transaction events |
| **Apple** (Apple Inc., USA) | App distribution, sign-in with Apple, in-app purchases, push notifications | Apple ID identifier (if you use Sign in with Apple), purchase receipts, push token |
| **Expo** (650 Industries, Inc., USA) | App build and over-the-air update infrastructure | Anonymous device and crash telemetry |

These providers act as **data processors** on our behalf and are contractually required to handle your data in line with their published privacy and security commitments.

---

## 4. AI and Automated Processing

Becom uses large language models to generate coaching responses, summarize your progress, and pick a daily focus step.

- The AI coach is not a licensed therapist, doctor, or medical professional. Its output is for motivational and educational purposes only and is not a substitute for professional advice. See our Terms of Service for more.
- We maintain a per-user "memory" record (stored as structured JSON) so the coach can reference your earlier goals, habits, and reflections in future sessions. You can view, export, or delete this memory at any time in **Settings → Privacy & Security**.
- Our AI providers are accessed through their developer APIs, which under their current terms do not use API content to train their models. We do not opt you into any model-training programs.

---

## 5. Data Storage, Security, and Retention

- All account data is stored in Supabase, hosted on AWS infrastructure in the United States.
- We use TLS encryption in transit and AES-256 encryption at rest (provided by Supabase / AWS).
- Row-Level Security (RLS) policies ensure that you can only read or modify your own records.
- We retain your data for as long as your account is active. If you delete your account, your habits, completions, messages, AI memory, and profile are removed from active systems shortly thereafter. Residual copies in routine database backups are overwritten according to our backup provider's standard retention cycle.
- Anonymous, aggregated metrics (e.g., total daily active users) and minimal billing records may be retained longer where required for tax or legal compliance.

---

## 6. Your Rights and Choices

Depending on where you live, you have rights under laws such as the EU/UK GDPR, the California Consumer Privacy Act (CCPA), and similar U.S. state privacy laws. These include the right to:

- **Access** the data we hold about you
- **Correct** inaccurate data
- **Delete** your data ("right to erasure")
- **Export** your data in a portable format
- **Object to or restrict** certain processing
- **Withdraw consent** for optional features (e.g., HealthKit, microphone) at any time
- **Lodge a complaint** with your local data protection authority

You can exercise most of these rights directly in the App:
- **In-app:** Settings → Privacy & Security → Export Data / Delete Account
- **By email:** Send a request to support@becom.app from the email address associated with your account

We will respond to verifiable requests within a reasonable timeframe (typically within 30 days, as required under applicable law). We do not discriminate against users who exercise their rights.

### "Do Not Sell or Share My Personal Information" (California residents)
Becom does not sell or "share" personal information for cross-context behavioral advertising as those terms are defined under the CCPA/CPRA.

---

## 7. International Data Transfers

If you use Becom from outside the United States, your data will be transferred to and processed in the U.S. and other countries where our service providers operate. Where required, we rely on standard contractual clauses or other lawful transfer mechanisms approved by the European Commission and UK ICO.

---

## 8. Children's Privacy

Becom is not directed to children under 13 (or under 16 in the EEA/UK). We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, contact us and we will delete it.

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. If we make material changes, we will notify you in the App and update the "Last updated" date above. Continued use of Becom after changes take effect constitutes acceptance of the revised policy.

---

## 10. Contact

For privacy questions, data requests, or any concerns about how we handle your information:

**Email:** support@becom.app
**Operator:** Becom, LLC
**Mailing address:** [Business Address — to be added]
**State of formation:** Idaho, USA

---

*This policy is provided as a clear, plain-language description of our practices. It is not legal advice. If you have specific legal questions about your rights, consult a qualified attorney in your jurisdiction.*
