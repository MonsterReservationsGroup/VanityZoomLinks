# Zoom Vanity Links and Custom Dial-in Phone Numbers

_TL;DR:_ It seems that this is quite easy to achieve, in just a few minutes of research I was able to determine how to do this \(Detailed Below\), the minimum cost to achieve this through Zoom is $300 a month. \(will increase as we add more than 10 people\)

## Vanity Links

### Guidelines and Requirements

1. You can apply for your Vanity URL [here](https://zoom.us/account)
2. You must submit a Vanity URL request from your official domain and not a public domain (gmail.com, hotmail.com, etc.)
3. Vanity URLs should match your company's domain name.
4. If you submit your request from name@hoolicompany.com and request hooli.zoom.us, you must submit evidence that you own hooli.com
5. If you need a vanity URL for a sub-account or department, it should contain the department name and the organization's domain name.
6. For example, if you need a vanity URL for your IT department, you should request "hooli-it.zoom.us".
7. Vanity URLs should be at least 4 characters in length 'https://1234.zoom.us'.
8. Vanity URLs must only contain letters, numbers and dashes (-).
9. You can select from pre-defined Vanity URLs that Zoom suggests based on your account information.
10. Vanity URLs conforming to the guidelines will be approved within 1 business day. Non-conforming Vanity URLS will be declined or approved within 4-5 business days. Notifications will be sent to the email address of the user who requested the URL.
11. We reserve the right to remove or change your Vanity URL if there is a conflict between 2 companies for the same Vanity URL. You will be notified prior to any changes.

#### Prerequisites

1. Business, Education, Enterprise, or API plan
2. Account owner or admin
3. A custom domain owned by your organization
4. Note: Widely used, generic domains, such as @gmail.com or @outlook.com, cannot be used

#### SSO (Custom Identity Managment)

Single sign-on allows you to login using your company credentials. Zoom single sign-on (SSO) is based on SAML 2.0. Zoom works with Okta as well as other enterprise identity management platforms such as Centrify, Microsoft Active Directory, Gluu, OneLogin, PingOne, Shibboleth, and many others. Zoom can map attributes to provision a user to different group with feature controls.

Zoom acts as the Service Provider (SP), and offers automatic user provisioning. You do not need to register as a user in Zoom. Once Zoom receives a SAML response from the Identity Provider (IdP), Zoom checks if this user exists. If the user does not exist, Zoom creates a user account automatically with the received name ID.

> This incurs an extra cost due to needing to subscribe to one of those platfroms above or build our own.

[More_Info](https://support.zoom.us/hc/en-us/articles/201363003-Quick-start-guide-for-SSO)

#### Examples

> - "hooli.com" should apply for "hooli.zoom.us".
> - “hooli.org” should apply for “hooli-org.zoom.us”
> - “hooli.com.au” should apply for “hooli-au.zoom.us”
> - “hooli.org.au” should apply for “hooli-org-au.zoom.us”
> - "hooli.edu" should apply for "hooli-edu.zoom.us"

### Dedicated Dial-in Number

#### Purchasing a Dedicated Dial-In Number

1. Sign in to the Zoom web portal.
2. In the navigation panel, click Account Management then Billing.
3. Click Edit to the right of Audio Conferencing under the Current Plans section.
4. Note: If you have not already purchased the plan, learn more about purchasing audio conferencing.
5. Select the check box next to Dedicated Dial-In Numbers.
6. Enter the number of dedicated dial-in numbers you want to purchase.
7. Click Continue.

Note: A dedicated dial-in number can only be assigned to one user at a time.

### Pricing

> - Zoom buisniness account $19.99 per month. \(10 minimum\)
> - Custom dial in number $100 per month
> - Total: $300 a month to start
