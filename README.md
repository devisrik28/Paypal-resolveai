# PayPal ResolveAI
### AI-Powered Dispute Resolution & Evidence Intelligence

ResolveAI is an AI-powered dispute management platform designed to simplify the way buyers, sellers, and freelancers handle payment disputes. It transforms confusing payment complaints and scattered supporting documents into structured, organized, and review-ready cases.

Our goal is to make dispute preparation faster, smarter, and more transparent through artificial intelligence and the PayPal developer ecosystem.

## 🚀 Live Application

**Website:** https://paypal-resolveai.vercel.app/

## 💡 The Problem

Payment disputes can be complicated and stressful. Buyers may report missing products, duplicate charges, unauthorized transactions, or items that do not match their descriptions. Sellers and freelancers often struggle to collect invoices, delivery confirmations, screenshots, and communication records to support their cases.

Traditional dispute preparation involves manually reviewing documents, organizing evidence, understanding dispute categories, and writing responses.

ResolveAI addresses these challenges through an intelligent, guided workflow.

## ✨ Key Features

### 1. AI-Powered Dispute Classification
Analyzes user-submitted complaints and identifies the relevant dispute category, such as:
- Item Not Received
- Item Not as Described
- Duplicate Payment
- Unauthorized Transaction

### 2. Smart Evidence Analysis
Helps users organize supporting documents, including invoices, receipts, delivery confirmations, and communication records.

### 3. Evidence Gap Detection
Analyzes the available case information and highlights potentially missing evidence, helping users understand what additional documents may strengthen their case.

### 4. Automated Case Timeline
Organizes important dates and events into a chronological timeline for easier case review.

### 5. AI Response Generation
Generates clear, professional, and neutral response drafts based on the available case information.

### 6. Dispute Tracking
Provides a centralized workspace to monitor case status, review progress, and understand the next steps.

## 💳 PayPal Developer Integration

PayPal is the central payment ecosystem around which ResolveAI is designed.

The project is intended to use the PayPal Developer Platform and its free Sandbox environment to support simulated payment workflows.

Planned integration components include:

- **PayPal Developer Dashboard:** Application configuration and developer credentials.
- **PayPal Sandbox:** Safe testing of payment workflows using simulated transactions.
- **PayPal REST APIs:** Connecting payment transaction information with dispute-related workflows.

The purpose is to connect payment context with intelligent dispute preparation without using real customer payment data during development.

## 🤖 Artificial Intelligence Integration

AI is the intelligence layer of ResolveAI.

The AI workflow is designed to support:

- Natural-language understanding of dispute descriptions.
- Automatic dispute categorization.
- Structured information extraction.
- Evidence gap identification.
- Chronological event summarization.
- Professional response generation.

The architecture supports an LLM API and document-processing/OCR capabilities for analyzing case descriptions and uploaded evidence.

AI-generated information is intended to remain reviewable and editable by users. ResolveAI assists with dispute preparation rather than independently deciding legal liability or guaranteeing refunds.

## 🛠️ Technology Stack

| Layer | Technology |
|---|---|
| Frontend | React, Vite |
| Styling | Tailwind CSS |
| Language | JavaScript |
| Backend | Node.js, Express.js |
| Database | Supabase PostgreSQL |
| File Storage | Supabase Storage |
| AI | LLM API |
| Document Processing | OCR / Document Parser |
| Payment Ecosystem | PayPal Developer Platform |

*Only list technologies and integrations that are actually implemented in the deployed version.*

## 🏗️ System Architecture

The application follows a modular architecture:

1. **User Interface:** Collects dispute details and supporting evidence.
2. **Backend Services:** Handles application workflows and case information.
3. **Database:** Stores structured case records, evidence metadata, and status information.
4. **AI Processing:** Analyzes descriptions and documents to generate structured insights.
5. **PayPal Ecosystem:** Provides the intended payment integration and Sandbox testing environment.
6. **Case Management:** Presents the timeline, evidence checklist, response draft, and progress information.

## ⚙️ Installation and Setup

### Prerequisites
- Node.js
- npm
- Git
- Supabase account
- AI service API key
- PayPal Developer account (for Sandbox integration)

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd paypal-resolveai
```

### 2. Install Dependencies

```bash
npm install
```

Install backend dependencies separately if the backend is maintained in a separate directory.

### 3. Configure Environment Variables

Create a `.env` file using the environment variables required by your implementation.

Example configuration:

```env
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_supabase_anon_key

AI_API_KEY=your_ai_api_key

PAYPAL_CLIENT_ID=your_paypal_sandbox_client_id
PAYPAL_CLIENT_SECRET=your_paypal_sandbox_secret
PAYPAL_BASE_URL=your_paypal_sandbox_url
```

Never expose private API keys or secrets in frontend code or commit them to GitHub.

### 4. Start the Application

```bash
npm run dev
```

For a separate Express backend, start it using the backend's configured development command.

### 5. Open the Application

Visit:

```text
http://localhost:5173
```

The exact commands and environment variables may vary depending on the repository structure.

## 🔐 Security and Responsible AI

ResolveAI is designed with responsible AI principles:

- Use synthetic transaction data for demonstrations.
- Keep sensitive credentials on the server.
- Protect uploaded evidence using access controls.
- Make AI-generated information reviewable.
- Avoid inventing evidence or unsupported policy requirements.
- Keep consequential decisions and final submissions under human control.

## 🏆 What Makes ResolveAI Different?

ResolveAI brings several dispute preparation activities into one intelligent workspace.

Instead of manually reviewing scattered files and writing lengthy explanations, users can organize their case, understand missing information, review a structured timeline, and prepare a professional response.

It focuses on three important principles:

- **Clarity:** Make complicated disputes easier to understand.
- **Intelligence:** Use AI to organize and analyze case information.
- **Transparency:** Keep evidence traceable and decisions under human control.

## 🔮 Future Enhancements

- Multilingual dispute submission.
- Advanced document understanding and OCR.
- Duplicate evidence detection.
- Dedicated support-agent review dashboard.
- Real-time notifications.
- Deeper PayPal payment and dispute workflow integration.

## 👥 Project Information

**Project Name:** PayPal ResolveAI  
**Category:** FinTech / Artificial Intelligence  
**Event:** PayPal AI Hackathon 2026

---

*ResolveAI — Turning payment disputes into clearer, smarter, evidence-backed resolutions.*****
