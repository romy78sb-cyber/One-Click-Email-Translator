## 1. Information We Collect
Our extension is designed with privacy as a foundational principle. We collect minimal data necessary solely to provide the core translation functionality:
* **Email Text Content:** When you invoke the translation feature, the text of the selected email is temporarily processed to fetch and display the translated output. This data is transmitted securely to our translation service provider and is **never stored, logged, or retained** by us.
* **User Preferences:** We store local configuration settings (such as your preferred target language and UI choices) locally on your device using the browser's `storage` API.

---

## 2. Permissions and Justifications
To deliver its single purpose effectively, the Extension requests specific browser permissions:
* `storage`: Used strictly to save your local user preferences and configuration settings on your device.
* `activeTab`: Used temporarily to interact with your active email tab so the extension can read selected email text and display translations on demand.
* **Host Permissions:** Required to inject necessary content scripts into webmail interfaces to enable seamless text detection and translation replacement directly inside your inbox.

---

## 3. How We Use Information
The information processed by the Extension is used exclusively for the following purpose:
> **Single Purpose:** To provide instant, one-click text translation for emails directly within your browser interface, removing language barriers without compromising your privacy.

We do **not** sell, trade, rent, or lease your personal data or email contents to any third parties. We do not use your email data for advertising, marketing, or behavioral profiling.

---

## 4. Data Security
We implement robust technical and administrative safeguards to protect any data processed during transmission. All communication between the Extension and translation services is encrypted using secure HTTPS protocols. Because translation text is processed in real-time and discarded immediately, no historical archives of your private emails are maintained on external servers.

---

## 5. Third-Party Services
The Extension utilizes standard, secure third-party translation APIs to convert text between languages. These services process text strictly for translation output and are bound by stringent confidentiality and data protection standards.

---

## 6. Changes to This Privacy Policy
We may update our Privacy Policy from time to time to reflect functional updates, compliance requirements, or regulatory changes. Any modifications will be posted directly within our repository or store listing, with a revised effective date.

---

## 7. Contact Us
If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please open an issue in this GitHub repository or reach out via our support channel.
