# OAuthyia

**Scalable authentication for developers. OAuth, login, profiles, 2FA, custom domains & more — all in one powerful, customizable platform.**

---

## Overview

OAuthyia is an authentication system designed to provide developers and startups with a scalable, free account management solution — with optional paid plans for growing businesses. Our mission is to disrupt legacy auth providers by offering a generous free tier and powerful features, making it easier than ever for developers to build secure, reliable authentication & a account system into their apps and services.

OAuthyia supports OAuth integrations, custom profiles, two-factor authentication (2FA), custom domains, and much more, all accessible via a clean, developer-friendly API.

---

## OAuthyia Planning

OAuthyia aims to be the go-to auth platform for startups and developers who want a scalable, easy-to-use system. The free tier is especially valuable, allowing teams to get started without upfront costs, while offering scalable paid options as your app grows.

By providing a modern, comprehensive authentication system, OAuthyia helps developers focus on building their business — not wrestling with complex auth infrastructure.

---

## Endpoints for App Developers

| Method | Endpoint                                     | Description                          |
|--------|----------------------------------------------|--------------------------------------|
| POST   | `/v1/account/signup`                         | Register a new account               |
| POST   | `/v1/account/login`                          | User login                           |
| GET    | `/v1/account/me`                             | Get current user info                |
| GET    | `/v1/account/profile`                        | View user profile                    |
| POST   | `/v1/account/profile/avatar`                 | Update profile avatar                |
| POST   | `/v1/account/profile/password`               | Change user password                 |
| POST   | `/v1/account/forgot`                         | Request password reset               |
| POST   | `/v1/account/reset`                          | Reset password using token           |
| POST   | `/v1/account/verify`                         | Verify user email                    |
| POST   | `/v1/account/logout`                         | Log out current session              |
| POST   | `/v1/account/refresh`                        | Refresh authentication token         |
| POST   | `/v1/account/resend-verification`            | Resend email verification            |
| GET    | `/v1/account/oauth/:provider`                | Initiate OAuth login                 |
| GET    | `/v1/account/oauth/:provider/callback`       | OAuth callback                       |
| POST   | `/v1/account/oauth/connect-accounts`         | Connect multiple OAuth accounts      |
| POST   | `/v1/account/oauth/connect/:provider`        | Connect specific OAuth provider      |
| POST   | `/v1/account/oauth/disconnect/:provider`     | Disconnect OAuth provider            |

---

## 🔗 OAuthyia – App Integration Providers

### 🧩 General & Social Login
- ✅ Google  
- ✅ Discord  
- ✅ Facebook  
- ✅ Instagram  
- ✅ Apple  
- ✅ Reddit  
- ✅ Twitch  

### 💻 Developer & Productivity Platforms
- ✅ GitHub  
- ✅ GitLab  
- ✅ Bitbucket  
- ✅ Slack  
- ✅ Zoom  
- ✅ Microsoft (Azure/Outlook)  

### 🎨 Creative & Media Platforms
- ✅ Spotify  
- ✅ Dribbble  
- ✅ Behance  
- ✅ DeviantArt  

### 🏢 Enterprise SSO & Identity (Enterprise Tier)
- ✅ Okta  
- ✅ Auth0 (integration compatibility)  
- ✅ Custom SAML/SSO (future roadmap)  

---

## 💡 Feature / Plan Comparison

| Feature                          | Free Plan                                     | Starter Plan                                   | Premium Plan                                  | Enterprise Plan               |
|----------------------------------|-----------------------------------------------|------------------------------------------------|-----------------------------------------------|-------------------------------|
| **Monthly Price**                | $0/mo                                         | $10/mo                                         | $30/mo                                        | Custom Pricing                |
| **User Slots**                   | 50,000                                        | 100,000                                        | 500,000                                       | 5,000,000+ (scalable)         |
| **Monthly Request Limit**        | 400,000 + 150,000 buffer                      | 800,000 + 450,000 buffer                       | 2,000,000 + 1,000,000 buffer                  | Custom SLA / unlimited        |
| **Overage Fee (if buffer is triggered)** | $6 flat (for extra 150k requests)           | $18 flat (for extra 450k requests)             | $40 flat (for extra 1M requests)              | Unlimited                    |
| **All Features Included**        | ✅                                            | ✅                                             | ✅                                            | ✅                            |
| **Projects Per Account**         | 4                                             | 10                                             | 10                                            | 20+                           |
| **Custom Domain (API/CDN)**      | ❌                                            | ✅                                             | ✅                                            | ✅                            |
| **OAuth Provider Support**       | ✅                                            | ✅                                             | ✅                                            | ✅                            |
| **User Profile Merging**         | ✅                                            | ✅                                             | ✅                                            | ✅                            |
| **Scope Editor**                 | ✅                                            | ✅                                             | ✅                                            | ✅                            |
| **CDN** (You provide your own storage provider)      | ✅                   | ✅                                             | ✅                                            | ✅  |
| **Custom SAML / SSO**            | ✅                                            | ✅                                             | ✅                                | ✅          |
| **Bring Your Own Domain (API)**  | ❌                                            | ✅                                             | ✅                                            | ✅                            |
| **Bring Your Own Domain (CDN)**  | ❌                                            | ✅                                             | ✅                                            | ✅                            |
| **Support Priority**             | Priority Support                             | Priority Support                                       | Priority Support                                      | Dedicated Manager             |
| **Audit Logs, Webhooks, IP Logs**| ✅                                            | ✅                                             | ✅                               | ✅                            |

---

### 📜 Overage & Request Limit Policy

If your app exceeds the included request limit, you have two options:

1. **Default Behavior (Overage Not Enabled)**  
   - Your app will be **heavily throttled**, limited to approximately **350 requests per day**.  
   - This ensures the service remains online, but is **practically unusable** until your usage resets in the next billing cycle.  
   - No additional charges will be applied.

2. **Optional: Enable Overage Mode (Pay-As-You-Grow)**  
   - When enabled, you will be charged a **flat overage fee** based on your plan tier to unlock an additional buffer of requests.  
   - If you exceed the combined total of your **included limit + buffer** again during the same month, you will be charged **the same flat fee again**.  
   - This can occur **multiple times per billing cycle** as needed — with **no throttling or service interruptions**.

> **Overage Conversion Rate:**  
> All overage buffer fees are calculated using a fixed rate of **$2 per 50,000 requests**.  
> Buffer sizes and pricing tiers are determined based on this conversion.

> **Note:** Fees may vary depending on your **location (country)** and **specific API usage patterns**.
---

## Getting Started

To get started with OAuthyia, sign up for a developer account and explore our API documentation to integrate secure and scalable authentication into your application.

---

## License

MIT License

---

## Contact

For support or inquiries, please visit our [support site](https://support.oauthyia.com) or email us at **support@oauthyia.com**.
