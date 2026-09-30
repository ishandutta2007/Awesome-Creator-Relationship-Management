# Awesome-Creator-Relationship-Management

# Top Creator Relationship Management (CRM) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Influencer Discovery, Campaign Management, Creator Outreach & Sponsorship Coordination*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Creator Relationship Management (CRM)**. These tools help brands, agencies, and creators discover influencers, manage campaigns, negotiate sponsorships, and track creator partnerships from outreach through payment.

**Examples** include GRIN, CreatorIQ, Aspire, Modash, Upfluence, LTK, Creator.co, Influencity, Julius, and Tagger (the category leaders).

**Open-source emphasis**: Creator relationship management has an **emerging but fragmented open-source ecosystem**. Unlike adjacent CRM categories with mature platforms like Twenty or SuiteCRM, the influencer/creator space is served primarily by **early-stage research projects and prototypes**. **InfluencerFlow AI** is the most complete concept, with AI-powered creator discovery, email negotiation agents, and contract generation (currently in development) . **InPactAI** (AOSSIE-Org) provides AI-driven sponsorship matchmaking and collaboration hubs . **Influencer-Marketing-bot** demonstrates engagement rate analysis and ML-based recommendation . **Influencer and Trends Discovery Tool** offers API-based creator discovery across TikTok, Instagram, and YouTube . For foundational CRM capabilities, **Twenty** (28k+ stars, AGPL-3.0) provides a customizable open-source CRM that can be adapted for creator relationship management . This section documents these focused solutions honestly.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[GRIN](https://grin.co/)**
  Creator management platform for e-commerce brands. Provides creator discovery, campaign management, product seeding, and payment processing.

- **[CreatorIQ](https://www.creatoriq.com/)**
  Enterprise creator marketing platform. Provides creator discovery, campaign management, and analytics for large brands and agencies.

- **[Aspire](https://www.aspireiq.com/)**
  Creator marketing platform connecting brands with creators. Provides discovery, campaign management, and payment processing.

- **[Modash](https://www.modash.io/)**
  Influencer discovery and analytics platform. Provides search across 250M+ creators with audience demographics and fake follower detection.

- **[Upfluence](https://www.upfluence.com/)**
  Influencer marketing platform. Provides creator discovery, campaign management, and affiliate tracking.

- **[LTK](https://www.shopltk.com/)**
  Creator commerce platform. Connects creators with brands for affiliate partnerships and shoppable content.

- **[Creator.co](https://creator.co/)**
  Creator marketing platform. Provides discovery, campaign management, and analytics.

- **[Influencity](https://influencity.com/)**
  Influencer marketing platform. Provides discovery, campaign management, and reporting.

- **[Julius](https://juliusworks.com/)**
  Influencer marketing platform. Provides discovery, outreach, and campaign management.

- **[Tagger](https://www.taggermedia.com/)**
  Creator marketing platform. Provides discovery, campaign management, and analytics.

## Open-Source GitHub Projects

### Creator Discovery & Matching Platforms

- **[InfluencerFlow AI](https://github.com/AmanGxpta/influencerflow-ai)**
  **The most comprehensive open-source creator relationship management platform concept.** **AI-powered creator database** for finding creators; **campaign management** for creating and managing influencer campaigns; **AI-driven email negotiation system** that automates deal-making through email communication; **contract generation** from negotiated terms; **payment processing** with milestone-based payments (planned) . **Status**: Early-stage. Core application structure, authentication, campaign views, and database schema completed. AI matching, negotiation email integration, and contract generation in progress. Payment processing and e-signature pending. **Tech stack**: Next.js, TypeScript, Tailwind CSS, tRPC, Prisma, PostgreSQL, OpenAI GPT-4, Node Mailer . **Production readiness**: Requires security testing, email system finalization, scalability improvements, and monitoring before production use .

- **[InPactAI (AOSSIE-Org)](https://github.com/AOSSIE-Org/InPactAI)**
  **Open-source AI-powered platform connecting creators, brands, and agencies through data-driven insights.** **AI-Driven Sponsorship Matchmaking**: automatically connects creators with brands based on audience demographics, engagement rates, and content style; **AI-Powered Creator Collaboration Hub**: facilitates partnerships between creators with complementary audiences; **AI-Based Pricing & Deal Optimization**: fair sponsorship pricing recommendations based on engagement, market trends, and historical data; **AI-Powered Negotiation & Contract Assistant**: assists in structuring deals and generating contracts; **Performance Analytics & ROI Tracking** for campaigns . **Tech stack**: ReactJS frontend, FastAPI backend, Supabase database, GenAI integration .

### Influencer Discovery & Analytics

- **[Influencer and Trends Discovery Tool](https://github.com/francisco-carcano/Influencers-and-Trends-Discovery-Tool-TikTok-Instagram-YouTube-API-Integration-)**
  **Automated tool for discovering influencers and trending topics using TikTok, Instagram, and YouTube APIs.** **Features**: Fetch trending creators, hashtags, and challenges; analyze followers, engagement, and video metrics; export processed data to Excel; optional integration with OpenAI's ChatGPT for text analysis . **Tech stack**: Python, social media APIs. **MIT-style open source**.

- **[Influencer Marketing Bot with Django](https://github.com/wende12github/Influencer-Marketing-bot-with-Django)**
  **AI-powered influencer marketing bot using Python, TensorFlow, and Instagram API.** **Core features**: Influencer discovery from Instagram by hashtags and follower count; **engagement rate calculation** (likes + comments / followers × 100); **audience demographics analysis** (age, gender, location); **AI-powered recommendations** using machine learning (Random Forest/KNN) to suggest optimal creators; **reporting dashboard** for campaign criteria input and creator recommendations . **Tech stack**: Django REST Framework, TensorFlow/Scikit-learn, PostgreSQL/SQLite, Bootstrap/Tailwind .

### CRM Foundations (Adaptable for Creator Management)

- **[Twenty](https://github.com/twentyhq/twenty)**
  **The leading open-source CRM and the most viable foundation for a creator relationship management system.** **28,000+ GitHub stars**, **AGPL-3.0 licensed** . **Key features**: Contacts, companies, and opportunities (deals) management; **custom objects** — create custom entities for creators, campaigns, or partnerships with custom fields; **configurable views** (table or Kanban) for tracking creator pipelines; **email synchronization** with contact creation automation; **workflows** for trigger-based automation; **API and webhooks** for integration with social media platforms . **Deployment**: Self-hosted via Docker or SaaS from Twenty . Can be adapted for creator relationship management by modeling creators as contacts, campaigns as opportunities, and partnerships as custom objects.

### Additional Strong Open-Source Options

- **Full Creator Platforms**: **InfluencerFlow AI** (AI negotiation, contract generation, comprehensive concept) , **InPactAI** (AI matchmaking, collaboration hub, pricing optimization) .
- **Discovery Tools**: **Influencer and Trends Discovery Tool** (multi-platform API discovery) , **Influencer Marketing Bot** (engagement analysis, ML recommendations) .
- **CRM Foundations**: **Twenty** (28k+ stars, custom objects, workflows) , **Corteza** (low-code CRM builder) , **Cordys CRM** (open-source AI CRM) .
- **Referral/Affiliate**: **Refferq** (referral and affiliate marketing platform for SaaS, Next.js + Prisma) .

**Frameworks for building custom systems**: Combine **Twenty** as the CRM foundation for managing creator contacts, campaigns, and partnerships, **InfluencerFlow AI** or **InPactAI** for AI-powered discovery and matchmaking concepts, **Influencer and Trends Discovery Tool** for multi-platform API-based creator discovery, and **Influencer Marketing Bot** for engagement analytics and ML-based recommendations. Add **PostgreSQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Creator relationship management platforms handle sensitive creator and brand data; ensure compliance with data protection regulations and platform terms of service.
- **Open-source reality**: The open-source ecosystem for creator relationship management is **emerging and fragmented**. **InfluencerFlow AI** provides the most comprehensive concept with AI negotiation and contract generation, but is early-stage and not production-ready . **InPactAI** offers AI matchmaking and collaboration features . **Influencer and Trends Discovery Tool** and **Influencer Marketing Bot** provide discovery and analytics foundations . **Twenty** is the most viable CRM foundation for adapting to creator management, with 28k+ stars and custom object support . However, **commercial platforms** (GRIN, CreatorIQ, Aspire, Modash, Upfluence) provide **integrated creator databases, campaign workflows, payment processing, and enterprise support** that open-source alternatives cannot match without significant development. The open-source path is most viable for **developers building custom creator management systems, discovery tools, or organizations with strong engineering capacity**.

---

**Made for influencer marketing managers, brand partnership teams, creator agencies, and full-stack developers.**
Let's make creator relationship management more open, transparent, and creator-friendly.
