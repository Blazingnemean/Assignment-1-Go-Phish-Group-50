 # Phishing Attack Flow - Speaker Invitation

```mermaid
flowchart TD
    A[Attacker creates realistic email<br>using conference branding] --> B[Email sent to target speaker]
    B --> C[Target sees professional invitation<br>with real-looking logo and button]
    C --> D[Target clicks 'Respond to This Invitation']
    D --> E[Redirected to fake credential harvesting page]
    E --> F[Credentials stolen or malware delivered]
   
    style A fill:#1a2a3a,stroke:#0d9dd9
    style F fill:#2a1f1f,stroke:#e74c3c
