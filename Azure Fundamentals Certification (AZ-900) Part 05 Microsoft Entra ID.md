# Introduction Microsoft Entra ID
![image](https://github.com/abdullahbannuwala/Microsoft-Azure-Fundamentals/assets/74914096/dc4bf450-ee59-4d61-95fe-8222eb690dae)
![image](https://github.com/abdullahbannuwala/Microsoft-Azure-Fundamentals/assets/74914096/fa17674e-65be-4ad7-bdda-574b45dce532)

# Use Cases
![image](https://github.com/abdullahbannuwala/Microsoft-Azure-Fundamentals/assets/74914096/99247f7e-bb6e-49d6-ba21-78a2e6ae019b)

# Active Directory Vs Azure Active Directory (Entra ID)
![image](https://github.com/abdullahbannuwala/Microsoft-Azure-Fundamentals/assets/74914096/6da0320f-2334-436b-9029-9071f5e6704a)

# Terminology
![image](https://github.com/abdullahbannuwala/Microsoft-Azure-Fundamentals/assets/74914096/782ad6c4-0d08-4f76-a3fa-64465273fe8d)

# AD Domain Services: Microsoft Entra Domain Services
![image](https://github.com/abdullahbannuwala/Microsoft-Azure-Fundamentals/assets/74914096/46a163cd-881d-4bb8-a402-2c251fa57898)

# Entra ID: Single Sign-On SSO
![image](https://github.com/abdullahbannuwala/Microsoft-Azure-Fundamentals/assets/74914096/a2f9e310-19c4-4da9-be9b-c278e86a0bf7)
![image](https://github.com/abdullahbannuwala/Microsoft-Azure-Fundamentals/assets/74914096/8bed0de0-1a8f-4ea9-b9a9-ab59c608855b)

# Single Sign-On SSO Protocols
Which SSO protocol is best suited for a given scenario?
![image](https://github.com/abdullahbannuwala/Microsoft-Azure-Fundamentals/assets/74914096/7f716f7c-ddb0-479d-98d9-a33c0be28f71)

SAML (Security Assertion Markup Language):

Use When:
You are integrating with enterprise-level or legacy applications, especially those that are standards-based and designed to work with SAML.
The application or service provider explicitly supports SAML.
You need a high degree of security and control over user authentication and authorization.
The application requires detailed assertions about the user's identity and permissions

OAuth 2.0:

Use When:
You need to authorize third-party applications to access resources (like user data) without exposing user credentials.
The application involves API access where the application needs permission to perform actions on behalf of the user.
You need a flexible authorization mechanism that can be scaled and customized for different types of applications, from mobile apps to web services.

OpenID Connect (OIDC):

Use When:
You need an authentication layer on top of OAuth 2.0. OIDC is essentially OAuth 2.0 with additional identity verification.
The application is modern and designed to work with the latest web and mobile authentication mechanisms.
You need to retrieve basic profile information about the authenticated user (like name, email, etc.).

WS-Federation:

Use When:
You are working with legacy systems, particularly those built on Microsoft technology stacks that natively support WS-Federation.
The integration environment is heavily invested in WS-* standards and SOAP-based services.
You require interoperability with systems that are already using WS-Federation for SSO.


Password-Based Authentication:

Use When:
The application requires a simple and direct authentication method without the need for SSO or third-party identity providers.
You're dealing with legacy systems that do not support modern SSO protocols.
The application is internal or has a limited user base where the convenience of SSO is not a primary concern.

Linked Authentication:

Use When:
You want to link multiple identity providers or authentication systems to a single user account.
The application needs to support authentication from various sources (like social logins, enterprise logins, etc.) while maintaining a unified user identity.
You're aiming to enhance user experience by providing multiple login options.


Integrated Windows Authentication (IWA):

Use When:
You have a predominantly Windows-based infrastructure and you want to leverage the user's existing Windows credentials for authentication.
The application is internal to an organization, and users are on a corporate network.
You're looking for a seamless authentication experience for users within the Windows ecosystem.


Header-Based Authentication:

Use When:
The application or system relies on an external gateway or a proxy for authentication.
You need to integrate with legacy applications that rely on user information being passed through HTTP headers.
There’s a need to support a custom authentication mechanism where the application consumes user credentials from HTTP headers set by an intermediate system, like a reverse proxy or a load balancer.
