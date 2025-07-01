
# ⚡ OAuthyia

**Authentication that scales with your platform.**  
A developer-first auth system that brings OAuth, login, profiles, 2FA, custom domains, and more into one unified, powerful API.

---

## 🚀 What Is OAuthyia?

**OAuthyia** is a modern authentication platform built for developers, startups, and teams creating the next generation of digital products.

We’re building an auth service that:
- Offers **enterprise-grade features** from day one
- Provides a **generous free tier** with seamless scalability
- Supports **OAuth**, **2FA**, **custom domains**, **object storage**, and more

OAuthyia isn’t just another auth layer — it’s your brand’s **identity infrastructure.**

---

## 🧠 Why OAuthyia?

Auth shouldn’t be a bottleneck — or a massive cost. OAuthyia changes that:

- Modular, Node.js backend optimized for scaling
- Clean, secure, and customizable APIs
- Custom domain support for both API and CDN
- Storage-agnostic: bring your own Cloudflare R2, AWS S3, and more
- Powerful identity features like profile merging, scope editing, and SSO

> **Even OAuthyia runs on OAuthyia.**  
> Our own stack uses the same API platform we provide to developers.

---

## 🛠️ Developer Endpoints

```http
POST   /v1/account/signup                    → Register a new user  
POST   /v1/account/login                     → User login  
GET    /v1/account/me                        → Get current session info  
POST   /v1/account/logout                    → Log out session  
POST   /v1/account/refresh                   → Refresh auth token  
POST   /v1/account/profile/avatar            → Upload/change avatar  
POST   /v1/account/profile/password          → Change user password  
POST   /v1/account/forgot                    → Request password reset  
POST   /v1/account/reset                     → Reset password with token  
POST   /v1/account/verify                    → Verify email  
POST   /v1/account/resend-verification       → Resend email verification  
GET    /v1/account/oauth/:provider           → Begin OAuth login  
GET    /v1/account/oauth/:provider/callback  → OAuth callback endpoint  
POST   /v1/account/oauth/connect-accounts    → Merge multiple identities  
POST   /v1/account/oauth/connect/:provider   → Connect specific provider  
POST   /v1/account/oauth/disconnect/:provider → Disconnect linked provider  
```

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
- ✅ Custom SAML / SSO (future roadmap)  

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
| **CDN** (You provide your own storage provider) | ✅                                    | ✅                                             | ✅                                            | ✅                            |
| **Custom SAML / SSO**            | ✅                                            | ✅                                             | ✅                                            | ✅                            |
| **Bring Your Own Domain (API)**  | ❌                                            | ✅                                             | ✅                                            | ✅                            |
| **Bring Your Own Domain (CDN)**  | ❌                                            | ✅                                             | ✅                                            | ✅                            |
| **Support Priority**             | Priority Support                              | Priority Support                               | Priority Support                               | Dedicated Manager             |
| **Audit Logs, Webhooks, IP Logs**| ✅                                            | ✅                                             | ✅                                            | ✅                            |

---

### 📜 Overage & Request Limit Policy

If your app surpasses the included monthly request limit, you have two handling options:

1. **Default Mode (Overage Not Enabled)**  
   - Your app will be **throttled to ~350 requests/day** after exceeding your limit.  
   - This prevents abuse and ensures service stability.  
   - No additional charges apply — usage resumes normally when your billing cycle resets.

2. **Optional: Overage Mode (Pay-As-You-Grow)**  
   - When enabled, you’ll be billed a **flat overage fee** based on your tier once your buffer kicks in.  
   - Each time you exceed your base limit + buffer, the same fee will apply again.  
   - This allows **seamless scaling** without service throttling or interruptions.

> **Flat Overage Pricing**:  
> Charges are calculated at a rate of **$2 per 50,000 additional requests**.  
> Each tier’s buffer is priced using this fixed conversion rate.

> ⚠️ Fees may vary depending on your country and usage conditions.

---

## 🧪 Development Roadmap

✅ Internal auth system in production  
✅ Developer API being finalized  
🔜 Beta platform launch (Q1–Q2 2026)  
🔜 SAML & custom SSO integrations  
🔜 Developer dashboard, docs & billing interface  

---

## 🧾 License

MIT License

---

## 📨 Contact

Need help or want to partner?  
📨 support@oauthyia.com  
📘 [Docs](https://docs.oauthyia.com) (coming soon)
