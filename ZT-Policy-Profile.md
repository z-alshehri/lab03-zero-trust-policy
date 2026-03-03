# Zero Trust Policy Profile

## 1. ZTA Compontet Definitions

### Policy Engine (PE)
The Policy Engine (PE) is the central decision-making component in a Zero Trust Architecture.
It evaluates access requests based on organizational policies, user identity, device status, risk level, and contextual information.
The PE determines whether access should be allowed or denied based on predefined security rules and continuous verification.


### Policy Administrator (PA)
The Policy Administrator (PA) is responsible for executing the decision made by the Policy Engine.
Once the PE makes a decision, the PA communicates that decision to the enforcement point and ensures 
the correct configuration is applied to allow or block access.


### Policy Enforcement Point (PEP)
The Policy Enforcement Point (PEP) is the component that physically enforces the access decision.
It sits between the user and the requested resource. Based on instructions from the Policy Administrator.



## 2. Core Principle Application

### Principle: Verify Explicitly
The principle of Verify Explicitly means that every access request must be evaluated using all available security signals before access is granted.
In the Golden State Water Treatment Facility, the Policy Engine verifies the employee’s identity, device security posture, and network location before granting access to the HR Employee PII Database. 

For example, if an HR employee requests access, the Policy Engine checks:
- Multi-factor authentication is completed
- The device is compliant and up to date
- The connection is coming from an approved internal network
Access is only granted if all conditions are satisfied.


## 3. Simplified Policy Table

| Policy Signal     | Condition to be Met                                  | Action if Condition is Met |
|-------------------|------------------------------------------------------|----------------------------|
| User Identity     | Valid credentials and multi-factor authentication    | Grant Access               |
| Device Posture    | Device is compliant and has latest security updates  | Grant Access               |
| Network Context   | Access request originates from approved secure network | Grant Access               |



## 4. Submission Details 

Name: Zainab Alshehri 
Course: Enterprise Infrastructure and Networks 
Dr. [ Safi Mojidi] 
Repository Link: https://github.com/z-alshehri/lab03-zero-trust-policy


## Git Repository Metadata

Project: Lab 03 – Zero Trust Policy  
Filename: ZT-Policy-Profile.md  
Commit Message: Final submission for Lab 03  
Due Date: March 2, 2026
