# Project Detail – Mitrana Digital

## Overview
Mitrana Digital is a **partnership and reseller platform** designed to connect service providers with partners and agents. The platform focuses on scalability, multi-role management, and seamless digital collaboration, enabling a marketplace-like ecosystem for partnership opportunities.

## Technical Stack
- **Frontend:** React.js with Next.js for server-side rendering and SEO optimization  
- **Styling:** TailwindCSS + custom UI kit for modern, consistent design  
- **Backend:** Node.js (Express) REST API with JWT-based authentication  
- **Database:** PostgreSQL with relational models for users, partners, services, and transactions  
- **Deployment:** Dockerized services deployed on AWS (ECS + RDS + CloudFront CDN)  
- **Version Control:** GitHub Actions for CI/CD pipelines  

## Key Features
1. **Partnership Management**
   - Partner registration and onboarding workflow  
   - Role-based access control (admin, partner, reseller)  

2. **Digital Service Catalog**
   - Dynamic listing of services offered by providers  
   - Search and filter functionality for ease of use  

3. **Transaction & Order Flow**
   - Agents can place orders or requests directly through the platform  
   - Transaction history stored with audit trail  

4. **Multilingual Support**
   - Built-in i18n framework for Bahasa Indonesia and English  
   - Expandable to additional languages for regional scaling  

5. **Analytics & Dashboard**
   - Partner dashboard with KPIs (sales volume, partner growth)  
   - Admin analytics with charts and downloadable reports  

## Workflow
- **Planning:** Defined partnership model and ecosystem roles in ERD + flowcharts  
- **Design:** Figma prototypes with electric blue + cyan palette for tech-modern vibe  
- **Development:** Feature-based modular coding (services, partners, transactions)  
- **Testing:** Unit + integration testing with Jest & Cypress  
- **Deployment:** Automated CI/CD with zero-downtime releases on AWS  

## Challenges & Solutions
- **Scalability:** Solved by containerized architecture and AWS auto-scaling groups  
- **Complex Role Hierarchy:** Implemented RBAC (Role-Based Access Control) at API level  
- **Security:** Encrypted sensitive data (bcrypt for credentials, TLS for all endpoints)  

---

**Status:** 🚧 In Development Phase  
**Next Step:** Launch MVP with **payment gateway integration** and **reseller commission system**
