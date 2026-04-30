# Broken Access Control

## Description
Access control is a security mechanism that defines and enforces which users are authorized to access specific resources and perform certain actions within an application. It operates alongside authentication, which verifies user identity, and session management, which maintains user state across requests. Access control can be implemented through vertical, horizontal, and context based models to ensure appropriate restrictions. When improperly designed or enforced, it can lead to broken access control vulnerabilities, allowing unauthorized access, privilege escalation, or data exposure. Therefore a secure implementation should follow a deny-by-default approach and consistently validate user permissions.

<img width="781" height="461" alt="image" src="https://github.com/user-attachments/assets/5d11356f-89c4-4f67-83ce-41898bb4f2ac" />

---

## Risk level = High or Critical

## Tools used: 
- Burp Suite
- Gobuster
- Mozilla

### Lab reference:
#### - Unprotected admin functionality 
https://portswigger.net/web-security/access-control/lab-unprotected-admin-functionality

#### - Unprotected admin functionality with unpredictable URL
https://portswigger.net/web-security/access-control/lab-unprotected-admin-functionality-with-unpredictable-url

#### - User role controlled by request parameter
https://portswigger.net/web-security/access-control/lab-user-role-controlled-by-request-parameter

#### - User role can be modified in user profile
https://portswigger.net/web-security/access-control/lab-user-role-can-be-modified-in-user-profile

#### - URL-based access control can be circumvented
https://portswigger.net/web-security/access-control/lab-url-based-access-control-can-be-circumvented

#### - Method-based access control can be circumvented
https://portswigger.net/web-security/access-control/lab-method-based-access-control-can-be-circumvented

#### - User ID controlled by request parameter
https://portswigger.net/web-security/access-control/lab-user-id-controlled-by-request-parameter

#### - User ID controlled by request parameter, with unpredictable user IDs
https://portswigger.net/web-security/access-control/lab-user-id-controlled-by-request-parameter-with-unpredictable-user-ids

#### - User ID controlled by request parameter with data leakage in redirect
https://portswigger.net/web-security/access-control/lab-user-id-controlled-by-request-parameter-with-data-leakage-in-redirect

#### - User ID controlled by request parameter with password disclosure
https://portswigger.net/web-security/access-control/lab-user-id-controlled-by-request-parameter-with-password-disclosure

#### - Insecure direct object references
https://portswigger.net/web-security/access-control/lab-insecure-direct-object-references

#### - Multi-step process with no access control on one step
https://portswigger.net/web-security/access-control/lab-multi-step-process-with-no-access-control-on-one-step

#### - Referer-based access control
https://portswigger.net/web-security/access-control/lab-referer-based-access-control
