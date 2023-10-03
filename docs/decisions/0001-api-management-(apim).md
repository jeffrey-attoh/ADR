# API Management (APIM)

* Status: proposed
* Deciders: Jeffrey Attoh
* Date: 2023-10-03

Technical Story: Migration from Apigee to Azure API Management (APIM) Due to Contract Expiration

## Context and Problem Statement

The organization currently utilizes Apigee for API management. With our contract about to expire and the need for specific features and capabilities, we need to make a decision on migrating from Apigee to a new solution, namely APIM. The transition should be seamless, ensuring no disruption to current services, and taking into account cost, features, and future scalability.

## Decision Drivers

- **Contractual Constraints**: Apigee's contract expiration necessitates this transition.
- **Financial Considerations**: Cost-effectiveness of the new solution versus renewing the contract with Apigee.
- **Scalability and Extensibility**: The new solution should cater to the organization's growth and future API needs.
- **Security**: Enhanced security features, especially with increasing cyber threats.
- **Integration Compatibility**: Ease of integration with existing systems and future tools.
- **Usability and Developer Experience**: How intuitive is the platform for API developers and consumers.

## Considered Options

1. **API Management (APIM)**: An integrated solution providing robust API management capabilities.
2. **Akamai (with WAF capabilities)**: While primarily a content delivery network, Akamai offers security features and Web Application Firewall (WAF) capabilities which can secure ingress and protect our APIs.

## Decision Outcome

"After evaluating the options based on our architectural drivers:  
**Chosen Option**: **API Management (APIM)**
- - APIM provides a comprehensive solution tailored for extensive API management.
- - It offers scalability, extensibility, and a favorable developer experience.
- - The organization will have a robust API infrastructure in conjunction with Akamai for enhanced security.

### Positive Consequences

- **Seamless Transition**: With proper planning, the migration from Apigee to APIM can be smooth.
- **Enhanced Security**: Leveraging Akamai's WAF capabilities adds an extra layer of security.
- **Cost Efficiency**: Possible cost savings compared to renewing the Apigee contract.
- **Future-proofing**: APIM offers features that cater to future needs and growth.

### Negative Consequences

- **Migration Challenges**: Potential unforeseen issues during the migration process.
- **Learning Curve**: The team might need time to adapt to the new system.
- **Integration Overhead**: Initial efforts will be required to integrate APIM with the current setup and ensure Akamai's compatibility.

