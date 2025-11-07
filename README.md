# ChatGPT Conversation Navigator – Privacy Policy

_Last updated: 2025-02-14_

## 1. Purpose
The ChatGPT Conversation Navigator extension adds a navigation sidebar to chatgpt.com / chat.openai.com conversations. It scans headings already present on the page to help users jump between sections. The extension is not intended to collect or process personal content.

## 2. Data We Collect
For licensing and abuse prevention we collect:

- A hashed installation identifier generated on the client (`installId` hash). The unhashed ID never leaves the user’s browser.
- License metadata returned by our server (e.g., `allowed`, `reason`, `expiresAt`, `nonce`).

We do **not** collect chat content, browsing history, or any other personal information.

## 3. How We Use the Data
The hashed install ID and license metadata are used solely to:

- Validate whether the installation is authorized for the current build.
- Enforce minimum version requirements and block known abuse.

No profiling or advertising use is made of this data.

## 4. Data Retention
The license metadata is cached locally in the browser for the duration of the license TTL (typically a few hours). On the server (hosted on Heroku), request logs and license audit entries follow Heroku’s standard retention policies (up to 30 days in application logs). After those periods the data is automatically purged.

## 5. Contact
Questions about this policy can be sent to **support@yourdomain.com**.

## 6. Sharing and Selling
We do not sell, rent, or share the hashed install IDs or license metadata with third parties. Data is disclosed only if required by law or to fulfill legal obligations (e.g., responding to lawful requests).

---

By using the extension you agree to this policy. We will update this document if our practices change and note the new “Last updated” date above.
