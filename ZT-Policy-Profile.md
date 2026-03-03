# Zero Trust Policy Profile

## 1.ZTA Compontet Definitions

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

### Principle: Least Privilege

The principle of Least Privilege means that users should only have access to the resources they need to perform their job. They should not have extra permissions.

For example, in a university system, a student can access their own grades and course materials, but cannot access other students' records or administrative data. Access is limited based on role and necessity.



## 3. Simplified Policy Table

| User        | Resource           | Condition                     | Decision |
|------------|--------------------|------------------------------|----------|
| Student     | Course Portal      | Valid login and enrolled     | Allow    |
| Faculty     | Student Records    | Verified identity and role   | Allow    |
| Student     | Student Records    | Not authorized               | Deny     |




