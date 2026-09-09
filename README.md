Social Pulse
AI-Powered Social Intelligence Platform

See the signal. Understand the story.

Social Pulse is a social intelligence platform that helps analysts track emerging narratives, understand how information spreads, identify possible coordination, and review the evidence behind risk assessments.

It brings together content, timing, platforms, engagement, and relationships in one place so analysts can understand what is happening without manually reviewing thousands of posts.

Live Demo https://socialpulse-black.vercel.app/

Launch Social Pulse

This is a working prototype.

The Problem

Information can spread across platforms within minutes. When a story starts gaining attention, analysts need to understand:

Where it started
How quickly it is spreading
Which platforms are involved
How the narrative is changing
Which accounts and posts are connected
Whether there are signs of coordinated activity
Why the system marked it as high risk
Whether the evidence can be verified later

Doing this manually is slow and difficult.

Our Solution

Social Pulse turns social-media activity into a clear, structured view.

The platform helps users:

Detect emerging narratives
Trace how information moves across platforms
Analyze content, timing, engagement, and relationships
Identify possible coordination patterns
Understand risk scores
Review the evidence behind each assessment
Key Features
Intelligence Dashboard

The dashboard provides an overview of the current information environment, including:

Posts analyzed
Active narratives
High-risk narratives
Coordination clusters
Platform reach
Narrative growth
Sentiment
Engagement
AI confidence
Narrative Detection

Social Pulse groups related posts into a common narrative. For example, several posts about a possible water problem may be grouped into a single “Contaminated Water Supply” narrative instead of being treated as unrelated posts.

Narrative Growth

The platform tracks how quickly activity around a narrative is increasing. A sudden spike can help analysts decide what needs further investigation.

A spike does not prove manipulation. It simply shows that something has changed and may need attention.

Cross-Platform Analysis

Social Pulse compares activity across:

X
Telegram
Instagram
Facebook

This helps analysts understand how a narrative moves between platforms.

Timeline

The timeline shows how a narrative develops over time, from the first discussion to later amplification and engagement spikes.

Network and Coordination Analysis

The platform maps relationships between accounts, posts, URLs, narratives, and platforms.

It looks at signals such as:

Similar content
Shared links
Reposts
Similar posting times
Repeated activity across platforms

These signals can highlight possible coordination patterns. They are indicators, not proof of malicious intent.

Risk Scoring

Social Pulse combines several signals into a prototype risk score, including:

Signal	Weight
Narrative growth	30%
Coordination indicators	25%
Cross-platform spread	20%
Engagement	15%
Sentiment intensity	10%

The score is used to prioritize investigations. It does not determine whether information is true or false.

AI Investigation Assistant

The AI assistant helps answer questions such as:

Why is this narrative high risk?
How did it spread?
Which accounts appear connected?
What changed recently?
What evidence supports the score?

The goal is to explain the assessment instead of showing only a number.

Evidence Integrity

Social Pulse uses SHA-256 hashing to create a digital fingerprint of captured evidence. If the evidence changes, the hash changes as well.

The prototype demonstrates this process using:

Evidence capture
Hash generation
Timestamps
A prototype evidence ledger
Verification
Live Monitoring

The Live Monitor displays social activity with details such as:

Platform
Author
Timestamp
Content
Engagement
Sentiment
Risk score
Related narrative

The prototype uses controlled or synthetic data to demonstrate the workflow.

Demonstration Scenario

The prototype includes a fictional “Contaminated Water Supply” scenario. It shows how a narrative can be detected, tracked across platforms, analyzed for possible coordination, assigned a risk score, and reviewed through the AI assistant.

This scenario is fictional and does not represent a real-world allegation.

Technology Stack
Frontend
Next.js
React
TypeScript
Tailwind CSS
UI and Visualization
shadcn/ui
Lucide Icons
Recharts
Network visualization
AI and Analytics
Narrative analysis
Sentiment analysis
Content similarity
Risk scoring
Explainable AI summaries
Evidence Integrity
SHA-256 hashing
Prototype evidence ledger
Timestamp verification
Deployment
Vercel
Project Structure
social-pulse/
│
├── app/
│   ├── dashboard/
│   ├── monitor/
│   ├── timeline/
│   ├── network/
│   ├── investigation/
│   ├── evidence/
│   └── sources/
│
├── components/
│   ├── dashboard/
│   ├── charts/
│   ├── timeline/
│   ├── network/
│   ├── investigation/
│   └── ui/
│
├── public/
│   └── assets/
│
├── package.json
├── tsconfig.json
├── tailwind.config.*
└── README.md
Getting Started
Prerequisites
Node.js 18 or later
npm
Git
Installation
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd social-pulse
npm install
npm run dev

Open the application at:

http://localhost:3000
Production Build
npm run build
npm start
Deployment

The application is deployed on Vercel.

Live application:

https://socialpulse-black.vercel.app/

To publish updates:

git add .
git commit -m "Update Social Pulse"
git push
Responsible Use

Social Pulse is a decision-support tool. It should not be used to automatically label people as malicious, criminals, or sources of misinformation.

Important points:

AI results should always be reviewed by a person.
A risk score does not prove intent or truth.
Coordination indicators do not automatically mean malicious behavior.
Data should be collected through lawful and authorized sources.
Personal information should be handled responsibly.
AI should support human judgment, not replace it.
Future Plans

Possible future improvements include:

Real-time platform integrations
Better narrative clustering
Multilingual analysis
Image, video, audio, and meme analysis
More advanced network analysis
Scalable streaming infrastructure
Stronger evidence storage and verification
Collaboration tools for analysts
Impact

Social Pulse helps turn large amounts of social-media activity into useful intelligence.

It gives analysts a way to:

Find emerging narratives
Follow how stories develop
Understand cross-platform spread
Identify possible coordination
Prioritize important cases
Review why something was flagged
Verify captured evidence
Smart India Hackathon

Project: Social Pulse
Category: Software
Domain: AI, Social Intelligence, Cybersecurity, and Data Analytics

Built as a prototype for Smart India Hackathon 2026.

Team
CyberPookies

Building practical tools that turn information noise into useful intelligence.

Disclaimer

Social Pulse is a prototype created for demonstration and research purposes.

The data shown may be simulated, synthetic, or illustrative. Platform access, data permissions, and production capabilities may differ from the prototype.

The system does not independently determine whether content is true or whether a person acted with malicious intent.

Human review remains essential.

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
