# IT0123 DevNet Resource Validation Plan

## Student and Project

- Name: Matt Reuel P. Bebero
- Section: TN31
- Repository name: `it0123-devnet-resource-plan`

## Purpose

Selecting the correct Cisco DevNet resource is important because each resource supports a different learning or development requirement. Verifying the selection with official Cisco documentation helps ensure that a network-automation task uses an appropriate environment and that an AI recommendation is supported by reliable evidence.

## Validated Resource Decisions

### UC1 Quick Read-Only API Exploration

I selected `always-on-sandbox` because the team needs immediate access to a shared environment for safe, read-only API practice and does not need administrative privileges. Cisco explains that Always-On Sandboxes provide instant shared access without requiring a reservation, while administrative access is restricted.

Official evidence: https://developer.cisco.com/docs/sandbox/

### UC2 Private Configuration Testing

I selected `reservation-sandbox` because the team needs a private environment with administrative access for configuration testing. The team can accept the reservation process, VPN connection, and setup time required for this type of sandbox.

Official evidence: https://developer.cisco.com/docs/sandbox/

### UC3 Guided API Concept Practice

I selected `learning-lab` because the beginner needs structured, step-by-step learning before attempting an independent API activity. The main requirement is guided practice rather than access to devices with administrative privileges.

Official evidence: https://developer.cisco.com/learning/

### UC4 Reusable Automation Example

I selected `code-exchange` because the developer wants to review existing network-automation examples before creating a new solution. Cisco Code Exchange provides Cisco-maintained and community-contributed code repositories that can be examined and adapted to an appropriate use case.

Official evidence: https://developer.cisco.com/codeexchange/

## AI Evaluation

I accepted the four resource recommendations provided by ChatGPT after independently comparing them with official Cisco documentation. None of the recommendations required correction because the suggested resources matched the decisive requirements in the four scenarios. I still verified the claims about immediate access, shared or private environments, administrative privileges, reservations, VPN use, guided learning, and reusable code before recording the final decisions.

## Validation Evidence

- Validator result: `VALIDATION COMPLETE: 9/9 checks passed.`
- Command used: `python -u "c:\Users\matri\Desktop\CS0016\M2\it0123-devnet-resource-plan\validate_plan.py`
- Official Cisco pages reviewed:
  - https://developer.cisco.com/docs/sandbox/
  - https://developer.cisco.com/learning/
  - https://developer.cisco.com/codeexchange/

## Git Evidence

- Initial commit message: `Initial Commit`
- Validation commit message: `Complete DevNet resource decisions`

## AI-Use Disclosure

I used ChatGPT to help interpret the four fictional use cases, recommend the most appropriate Cisco DevNet resource categories, and improve the wording of the JSON rationales and README. I independently reviewed the official Cisco DevNet pages, checked the access and privilege claims, confirmed that the recommendations matched the scenarios, and ran the offline validator. I revised the responses so that they clearly explained the decisive requirement for each resource selection and did not include any credentials or personal account information.
