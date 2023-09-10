# Cloud Security 
A successful cloud infrastructure deployment depends on countermeasures to secure against modern-day cyberattacks. You should have adequate cloud security solutions in all cloud environments, whether they are private, public, or hybrid to ensure business continuity and security.

## Need for Data Security
Migration of workload to a hybrid cloud environment:
- Expansion of attack surface
- Data security & compliance challenges
- Centralised visibility & monitoring

## Data Security Capabilities
- improve maturity across people, processes, and technology.
- Identify your most critical data assets, who has access to them, and how they are protected.
- Implement data security governance by establishing processes, metrics, and continuous steady-state data discovery and classification.
- Prevent data loss.
- Monitor database security by enforcing data protection and compliance policies across hybrid cloud environments.

## Cloud Network Security
refers to the security measures, technology, policies, controls, and processes used to protect data on public, private, and hybrid cloud networks.

![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/5b8d4ee2-c9f9-4ba5-b819-e3e3ec19083a)

###  Cloud Security Posture Management (CSPM)
CSPM solutions are designed to address a common error in many cloud environments, that is, misconfigurations.
CPSM also addresses issues by helping in the deployment of the core components of cloud
security.
They include identity and access management (IAM), regulatory compliance management, traffic monitoring, threat response, risk mitigation, and digital asset management. 
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/34037462-294e-4664-ab79-a9c1e4480117)

## POLICIES
A policy in cloud security refers to a set of rules and guidelines that determine how users should access and protect resources within a cloud environment. These policies provide a framework for maintaining security, ensuring compliance with industry regulations, and mitigating potential risks

The format of a policy typically includes the following:
- A title that provides a descriptive name or identifier for the policy
- The scope of the policy, which defines the specific resources, systems, or individuals to which the policy applies
- The objective of the policy, or its goals and purpose
- A policy statement that lists the rules, procedures, and restrictions of the policy
- The roles and responsibilities of the individuals and groups that are enforcing and adhering to the policy
- Compliance and enforcement details or the measures taken to monitor and ensure policy compliance
- A review and revision section that outlines how often to review and update the policy to remain relevant and effective

## Service provider and customer-managed policies
Cloud service providers (CSPs) typically have security policies that govern the overall security of their infrastructure, data centers, and services. These policies ensure a baseline level of security and protection for customer data. Service provider policies cover various aspects such as physical security, network security, data encryption, access controls, and incident response.

In addition to service provider policies, customers can implement their own policies, also known as customer-managed policies. These policies allow customers to tailor security measures according to their requirements, industry regulations, and risk tolerance. Customer-managed policies can include additional security controls, access restrictions, data protection measures, and compliance frameworks.

By combining service provider and customer-managed policies, organizations can establish a comprehensive security framework that aligns with their unique needs while benefiting from the underlying security measures provided by the cloud service provider.


## Principle of Least Privilege
The principle of least privilege is a key concept in access control that minimizes the risk of unauthorized access or accidental misuse of resources. It dictates that organizations should grant users only the minimum necessary permissions required to perform their tasks. By following the principle of least privilege, organizations limit the potential damage caused by compromised user accounts.

### User Access Level
In a cloud environment, user access levels vary depending on their roles and responsibilities. Some users may only need access to the console, or the graphical user interface (GUI) provided by the cloud service provider for resource management and configuration. These users interact with the cloud through the console to perform tasks such as provisioning resources, monitoring, and administration.

On the other hand, users involved in software development may require access to the development environment. This environment includes tools, APIs, and services necessary for building, testing, and deploying applications in the cloud. These users interact with the cloud infrastructure using APIs and command-line interfaces (CLIs) rather than relying solely on the console.

Depending on the organization’s requirements, certain users may have access to both the console and development environment, enabling them to perform a broader range of tasks and responsibilities.

## Identity and Access Management (IAM)
- AI-powered context to automate risk protection & constantly authenticate any user to any resource.
- Modernize at your own pace
- Establish a zero-trust implementation that will provide centralized access control, preserve client confidentiality, reduce insider threats, and secure your remote resources.
- Enable scalability.

![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/9551a9b7-7a69-4f72-9ad6-e2ea43a79b06)

## Standard Password Policy
A standard password policy for users logging into the cloud should adhere to best practices to ensure strong password security. Typically, a password policy includes requirements for password complexity, such as a minimum length and a combination of upper and lowercase letters, numbers, and special characters. The policy may also define password expiration intervals, after which users must change their passwords. Additionally, enforcing a password history, which is a required number of unique passwords used before reusing an old password, adds an extra layer of protection against password reuse. Other password policies may include account lockout, multi-factor authentication, and user awareness and training. The specific requirements of a password policy will depend on the organization’s needs, requirements, and risk assessments.


## Identity provider standards (SAML, OpenID)
Identity provider standards are protocols and frameworks that define how identity providers (IdPs) and service providers (SPs) securely exchange authentication and identity information. These standards ensure consistent and standardized approaches to authentication and access management. Two widely used identity provider standards are:

Security Assertion Markup Language (SAML) - SAML is an XML-based standard for exchanging authorization and authentication data between IdPs and SPs. It enables secure single sign-on (SSO) and identity federation. SAML allows users to authenticate once with their IdP and access multiple SPs without needing separate authentication. SAML assertions contain information about the user’s identity and attributes, which SPs rely on to grant access to their resources.
OpenID Connect - OpenID Connect is a modern standard built on the OAuth 2.0 protocol. It provides a framework for authentication and identity federation. OpenID Connect allows users to authenticate using their chosen OpenID provider and obtain an ID token that contains information about their identity. Service providers can use the ID token to authenticate users and provide access to their resources.

## Cloud Encryption
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/b8cd84db-2082-4b58-a088-b7e77728b74e)
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/aaaf781f-4c45-492b-b74d-04af525f9bbb)
