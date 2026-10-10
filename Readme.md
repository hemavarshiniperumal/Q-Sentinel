◈ Q-Sentinel — Quantum-Aware Document Security

Q-Sentinel is a web-based document security prototype designed to demonstrate secure digital document signing, signature analysis, risk-based authentication, and document integrity verification.

🚀 Features

- User Profile: Create a profile using your name, Gmail address, phone number, and optional location.
- Document Upload: Upload a document or use the built-in sample document.
- Digital Signature: Draw a signature directly on the webpage.
- Signature Analysis: Analyze signature complexity and calculate a demo risk score.
- Risk-Based Authentication: Demonstrate OTP verification and additional security checks based on the risk level.
- Document Integrity: Generate a SHA-256 hash to help verify whether a document matches a previously recorded version.
- Threat-Aware Security: Simulate suspicious sessions and demonstrate security alerts.
- Digital Twin: Track basic typing and pointer interaction events.
- Quantum-Safe Migration Lab: Demonstrate RSA-PSS signature verification and explain a possible migration path to post-quantum cryptography.
- Audit Trail: Export security events and document verification records.
- Responsive Design: Use the interface on desktop and mobile devices.

🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Web Crypto API
- HTML Canvas API
- Browser Local Storage
- GitHub Pages

⚙️ How to Run

1. Clone or download this repository.
2. Open "index.html" in a browser, or deploy it using GitHub Pages.
3. Create your demo profile.
4. Upload a document or select the sample document.
5. Draw your signature and click Analyze signature & risk.
6. Complete the displayed demo authentication steps.
7. Finish the signing workflow and download the verification record.
8. Use the Security Center to explore integrity verification and audit features.

🔐 Security Workflow

1. Profile Enrollment — Enter basic user details.
2. Document Selection — Upload a document for the signing workflow.
3. Signature Capture — Draw a signature on the canvas.
4. Risk Assessment — Calculate a demonstration risk score.
5. Step-Up Authentication — Complete the demo OTP and any additional checks required by the risk level.
6. Integrity Record — Generate a SHA-256 document hash and save a local verification record.
7. Audit and Verification — Export the audit trail and compare document hashes.

💡 Novelty

Q-Sentinel combines several document-security concepts in a single prototype:

- Risk-based authentication that demonstrates different verification steps for different risk levels.
- Signature complexity analysis as an additional risk signal.
- A simulated Digital Twin using basic user interaction events.
- Document integrity records using SHA-256 hashing.
- A quantum-safe migration demonstration to introduce post-quantum cryptography.

⚠️ Limitations

This is a hackathon prototype, not a production-ready document-signing service.

- OTPs are generated and displayed locally; real SMS or email delivery is not implemented.
- Face verification, biometric verification, and administrator approval are simulated.
- Signature complexity analysis does not establish the signer's identity.
- SHA-256 hashing detects differences only when compared against a trusted reference hash.
- RSA-PSS is classical cryptography, not post-quantum cryptography.
- Post-quantum signing algorithms are described but are not implemented.
- User information and records are stored locally in the browser.
- The downloaded JSON record does not make the original document a legally binding digital signature.

Do not use confidential documents or real authentication credentials in this demo.

🔮 Future Enhancements

- Integrate real email/SMS OTP delivery.
- Add secure server-side authentication and authorization.
- Implement trusted digital-signature standards.
- Add verified biometric authentication where appropriate.
- Integrate a vetted post-quantum cryptography library.
- Store audit logs securely on a backend.
- Add tamper-evident document records and secure key management.

👩‍💻 Project Information

Project Name: Q-Sentinel
Category: AI-Assisted Document Security Prototype
Platform: Web Application
Status: Hackathon MVP / Prototype

---

Q-Sentinel aims to demonstrate how risk-aware verification, document integrity checks, and quantum-safe migration planning can work together in a document-security workflow.
