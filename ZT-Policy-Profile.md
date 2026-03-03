# Zero Trust Policy Profile

## 1.ZTA Compontet Definitions

🔹 Policy Engine (PE)
The Policy Engine (PE) is the central decision-making component in a Zero Trust Architecture.
It evaluates access requests based on organizational policies, user identity, device status, risk level, and contextual information.
The PE determines whether access should be allowed or denied based on predefined security rules and continuous verification.


🔹 Policy Administrator (PA)
The Policy Administrator (PA) is responsible for executing the decision made by the Policy Engine.
Once the PE makes a decision, the PA communicates that decision to the enforcement point and ensures 
the correct configuration is applied to allow or block access.


🔹 Policy Enforcement Point (PEP)
The Policy Enforcement Point (PEP) is the component that physically enforces the access decision.
It sits between the user and the requested resource. Based on instructions from the Policy Administrator.
