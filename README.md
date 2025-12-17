# AI-Security Framework

Layer 1
Data -> Model -> Use

1 - Data (Train Tune Model):


1.1 Data Posionning;
1.2 Exfiltration;
1.3 Leakeage;

Solution:

Data discovery and classification;
Cryptography;
Access control (RBAC/MFA);
Monitor the system;

2 - Model (LLM):

CHallenging:
How to get models from trusted sources;
API Communication (Attack Path);
Privilege escalation;
IP;

Solution:
Supply chain managment of the model;
Scan the system;
Hardening system;
non-root, limit, Human in the loop;
RBAC
Check sources copyright.


3 - Use (Inference):

Challenges:

Prompt injection;
DDoS;
Model Theft;

Solution:

Monitor the system input (Guardrails);
ML detection and response;
SIEM/SOAR system;


Layer 2
Infra

Servers, Network, Storage, and remaining underlyning infrastructure.


Layer 3:
Governance:

Ensure:
No bias;
no drift;
Regulatory compliance;


Notes:
Use AI to create better security. Ai for security and security for AI.

Key workds:
Attack surface

GenAI Security
Trust = Accuracy, Privacy, Cyber
