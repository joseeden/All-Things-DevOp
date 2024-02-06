
# Risk Management 


- [Importance of Risk Management](#importance-of-risk-management)
- [Risk Management Terminologies](#risk-management-terminologies)
    - [Asset](#asset)
    - [Vulnerability](#vulnerability)
    - [Threat](#threat)
    - [Threat Actor](#threat-actor)
    - [Threat Vector](#threat-vector)
    - [Attacker](#attacker)
- [Likelihood](#likelihood)
- [Risk Management Process](#risk-management-process)
    - [Risk Identification](#risk-identification)
    - [Risk Assessment](#risk-assessment)
    - [Risk Treatment](#risk-treatment)
    - [Risk Priorities](#risk-priorities)
- [Prioritizing RIsks](#prioritizing-risks)
- [Risk Tolerance](#risk-tolerance)
- [Annualized Loss Expectancy](#annualized-loss-expectancy)


## Importance of Risk Management 
Information assurance and cybersecurity are key for risk management. The required cybersecurity level is determined by the entity's risk tolerance. 

- Assess and evaluate risks, and then implement security controls  
- To prioritize risk based on their impact 


## Risk Management Terminologies 

### Asset

An asset is something in need of protection.

### Vulnerability

Gap or weakness in protecting valuable assets, including information.

- Example: IT environment vulnerable to flooding during a major storm.

### Threat

Something or someone aiming to exploit a vulnerability for unauthorized access.

- Example: Natural disaster threatening utility power supply, impacting IT asset availability.

**Harm by Exploitation:**

  - Exploiting a vulnerability allows threats to harm assets.
  - Example: Storm cutting off power, rendering IT components unusable.

**Mitigation and Risk Evaluation:**

  - Evaluate event likelihood and take actions to mitigate risks.
  - Example: Assessing storm risk and implementing measures to protect IT assets.

### Threat Actor  

A Threat Actor is defined as an individual or a group posing a threat (according to NIST SP 800-150 under Threat Actor). Typical threat actors include the following:

- Insiders (either deliberately, by simple human error, or by gross incompetence).
- Outside individuals or informal groups (either planned or opportunistic, discovering vulnerability).
- Formal entities that are nonpolitical (such as business competitors and cybercriminals).
- Formal entities that are political (such as terrorists, nation-states, and hacktivists).
- Intelligence or information gatherers (could be any of the above).
- Technology (such as free-running bots and artificial intelligence , which could be part of any of the above).

### Threat Vector

The means by which a threat actor carries out their objectives.

### Attacker 

An Attacker is always an individual, but a Threat Actor can be either a group or an entity.

The three most common goals of cybersecurity attackers are DAD:

- Disclosure
- Alteration
- Denial

## Likelihood

- **Likelihood of occurrence** 

    - This is the weighted factor based on a subjective analysis of the probability that a given threat or set of threats is capable of exploiting a given vulnerability or set of vulnerabilities.

- **Assessing Impact:**

    - Impact is the magnitude of harm resulting from unauthorized actions like disclosure, modification, destruction, or loss of information or system availability.
    - Consideration: Potential results if a threat materializes and an event occurs.  

## Risk Management Process

### Risk Identification 

- **Risk Identification in Cybersecurity:**
  - Vigilance: Similar to watching for hazards on the street, identifying cyber risks requires constant attention.
  - Ongoing Process: Continuous identification, characterization, and estimation of potential disruptions.

- **Tailored Analysis:**
  - Unique Situation: Analyzing the company's distinctive context.
  - Knowledge: Security professionals understand strategic, tactical, and operational plans.

- **Key Takeaways:**
  - Communication and Protection: Identify risks for clear communication and protection.
  - Employee Involvement: All levels contribute to identifying risks.

- **Security Professional's Role:**
  - Assistance: Assist in system-level risk assessment, focusing on processes, controls, monitoring, or incident response.
  - Opportunities: Contribute to risk management in smaller organizations lacking mitigation plans.

### Risk Assessment 

Risk Assessment is the process of identifying, estimating, and prioritizing risks to an organization's operations, assets, individuals, and mission.

- **Alignment with Goals:**
  - Links risks to organizational goals, objectives, assets, or processes.

- **Example: Fire Risk:**
  - Options: Alarms, sprinklers, gas-based solutions.
  - Goal: Estimate and prioritize, considering costs and effectiveness.

- **Management Prioritization:**
  - Outcome: Report or presentation.
  - Purpose: Aids management in prioritizing identified risks.

- **Further Assessment:**
  - Scenario: Management may request detailed assessments.
  - Result: Reports provided for review and approval.

### Risk Treatment 

Risk treatment involves deciding on the most appropriate actions based on management's risk attitude and the availability and cost of mitigation measures.

- **Risk Avoidance:**
    - Decision to eliminate a risk entirely.
    - May involve halting specific activities.
    - Leadership decision when impact or likelihood is deemed too high.

- **Risk Acceptance:**
    - Decision to take no action to reduce risk likelihood.
    - Management proceeds with associated business functions without further action.
    - Occurs when impact or likelihood is negligible, or benefits outweigh the risk.

- **Risk Mitigation:**
    - Most commonly used in risk management.
    - Aims to prevent or reduce risk likelihood or impact.
    - Involves measures like security controls and policies.
    - While complete mitigation isn't always possible, safety measures should be implemented.

- **Risk Transference:**
    - Involves passing the risk to another party.
    - The party accepts financial impact in exchange for payment.
    - Commonly done through insurance policies.    


### Risk Priorities 

- **Prioritizing and Analyzing Risks:**
  - Essential step post-risk identification.
  - Utilizes qualitative and quantitative analyses.
  - Aims to determine root causes and prioritize risk-response actions.

- **Contextualizing Risks:**
  - Understands the organization's mission and supporting functions.
  - Places risks in context and identifies root causes.

- **Management Direction:**
  - Typically, management directs the use of risk assessment findings.
  - Guides the prioritization of risk-response actions.

- **Risk Matrix for Prioritization:**
  - Aligns likelihood of occurrence with impact.
  - Provides a common language for team and management.
<br>
    <p align=center>
    <img width=300 src='../../Images/risk-matrix-for-prioritization.png'>
    </p>

- **Priority Assignment Factors:**
  - Business priorities.
  - Mitigation costs.
  - Potential losses in case of an incident.

## Prioritizing RIsks 

The highest priority should be given to risks estimated to high impact and low probability over high probability and low impact value (ISC2 Study Guide, Chapter 1, Module 2). 

In qualitative risk analysis, the 'expected probability of occurrence' and the 'frequency of occurrence' refer to the same thing. 

Prioritize: 

- Low frequency of occurrence 
- High expected impact

## Risk Tolerance 

- **Risk Perception and Tolerance:**
  - Likened to the entity's risk appetite.
  - Varies across organizations and departments.
  - Crucial for determining management's actions on risks.

- **Management's Role:**
  - Executives or the Board sets acceptable risk levels.
  - Security professionals align risks with management's tolerance.

- **Geographic Influence:**
  - Risk tolerance often dictated by location.
  - Example: Volcano-prone areas plan for related risks.
  - Calculating downtime likelihood defines risk tolerance.

- **Power Outage Example:**
  - Risks vary by location.
  - Low tolerance leads to generator investment.
  - Higher tolerance involves multiple generators for increased assurance.

## Annualized Loss Expectancy

The Annualized Loss Expectancy (ALE) is a standard metric of risk exposure that refers to the expected cost per year of a given risk if it is not mitigated. 

The business impact of a risk is technically considered a loss, and is better captured by a metric called **Single Loss Expectancy** (see ISC2 Study Guide, chapter 1, module 2). 

The probability of a risk coming to pass in a given year is best captured by a metric called Annualized Rate of Occurrence (ARO).



----------------------------------------------

[Back to main page](../../README.md#security)    