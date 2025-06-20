# CS405
Portfolio submission for CS-405: Secure Software Development

## CS-405 Portfolio Reflection

## Key Learnings

### Secure Coding Standards From the Start

Throughout this course, the importance of adopting a secure coding standard from the outset has become clear. Leaving security to the end of a project increases the likelihood of costly vulnerabilities and rework.

Secure coding standards—like those recommended by CERT or OWASP—provide developers with clear guidelines to prevent common coding flaws such as:

- Buffer overflows
- Injection attacks
- Insecure memory use

By integrating these standards early, teams can embed security into the development lifecycle, aligning with DevSecOps principles that emphasize “shift left” strategies.

Tools like Cppcheck and Fortify SCA help enforce these standards and detect violations before code reaches production.

### Risk Evaluation and Cost-Benefit Mitigation

Not all vulnerabilities carry the same weight. Understanding likelihood and impact helps prioritize limited resources.

Example: A high-severity issue in a public-facing login service should be addressed before a low-risk flaw in an internal admin panel.

We used risk matrices and threat modeling to simulate real-world tradeoffs between cost, effort, and potential damage.

### Zero Trust Architecture

The “never trust, always verify” mindset of zero trust challenges traditional perimeter-based thinking.

Key aspects include:

- Continuous authentication
- Least privilege access
- Context-aware security

This approach assumes breach and verifies every access attempt—limiting lateral movement and reducing insider threats. It ties directly into defense-in-depth and identity management strategies.

### Policy Implementation and Maintenance

Implementing and maintaining strong security policies ensures consistent practices across the team.

Our Green Pace Secure Coding Policy showed how:

- Technical controls
- Employee training
- Threat awareness

...can collectively build a culture of security.

Regular reviews and automation help keep policies adaptable, enforceable, and current with evolving threats and compliance needs.

## Final Reflection

Secure software development is not a one-time task—it’s a continuous process built into every phase of the software development lifecycle. Through:

- Secure coding standards
- Risk-based prioritization
- Zero trust principles
- Clear, evolving security policies

developers can build software that is not only functional but resilient.

