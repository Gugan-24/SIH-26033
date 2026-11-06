# Smart India Hackathon Workshop
# Date: 06/11/2026
## Reference Number: 26017494
## Name: GUGAN U

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
Our proposed solution, KrishiDirect, is an AI-powered B2B and B2C direct-trade ecosystem built as a mobile-first progressive web and native app. It bridges the gap between individual farmers/Farmer Producer Organizations (FPOs) and buyers (end-consumers, restaurants, retail chains, and food processors).

Direct Buyer-Seller Matching Engine: Provides dynamic, transparent pricing using real-time mandi prices and AI demand scoring. FPOs and farmers list produce batches with transparent quality grading, bypassing traditional multi-tier APMC middlemen (arhatiyas).

AI-Driven Logistics Aggregation: Rather than managing physical fleets, the platform aggregates local third-party logistics (3PL) providers, rural hyper-local truckers, and cold-storage partners in a unified Uber-style dispatch mesh.

Smart Contracts & Quality Verification: Integrates AI image-based produce quality assessments and smart escrow payments to guarantee payout security upon delivery verification

## Technical Approach
1. Technology Stack
Frontend: Flutter / React Native (Mobile App supporting multi-lingual voice/text interfaces), React.js (Web Dashboard for bulk buyers & FPO admins).

Backend: Node.js / Go (Microservices architecture), FastAPI (AI/ML inference microservices).

Database: PostgreSQL (Primary structured relational store), Redis (Caching & real-time pricing feeds).

AI & Machine Learning: Python, PyTorch / TensorFlow (Time-series Forecasting with Prophet/LSTM for demand prediction; YOLOv8/ResNet for visual fruit/vegetable grading).

Logistics & Routing: Google Maps Platform / OpenStreetMap, OR-Tools (Vehicle Routing Problem optimization).

Cloud Infrastructure: Google Cloud Platform (GCP) / AWS, Docker, Kubernetes.

2. Implementation Methodology
Phase 1 (Data Ingestion & Forecasting): Train time-series models on historical Agmarknet daily crop prices, regional weather patterns, and seasonal consumption cycles to build real-time pricing and crop demand prediction APIs.

Phase 2 (Marketplace Core): Construct localized multi-lingual user journeys featuring voice-assisted crop listing for farmers and bulk-ordering UI for commercial buyers.

Phase 3 (Route & Batch Optimization): Implement dynamic vehicle routing heuristics to aggregate partial loads across neighboring farms into unified regional logistics runs, minimizing transit time and cold-chain costs.

## Feasibility and Viability
1. Feasibility Analysis
Technical: High. Standard open APIs for Agmarknet data, established VRP (Vehicle Routing Problem) solvers, and lightweight edge-ML models make mobile deployment smooth even on budget devices.

Operational: Strong alignment with government-backed FPO digitization drives, ensuring high initial onboarding rates via agricultural extension hubs.

2. Potential Challenges & Risks
Digital Literacy & Adoption: Farmers may struggle with manual app data entry or complex navigation.

Intermittent Connectivity: Poor internet access in deep rural farming pockets.

Quality Standard Dispute: Variations between listed crop quality and actual delivered batch quality.

3. Risk Mitigation Strategies
Voice-First & Vernacular UI: Interactive multi-lingual voicebots (using Speech-to-Text in regional dialects) to allow screen-free crop listings.

Offline-First Architecture: Local storage sync allowing offline draft creation; updates auto-sync when network reconnects.

AI Visual Grading & Quality Escrow: Standardized visual grading scans at collection centers, paired with escrow-backed buyer approvals to settle disputes automatically.
<img width="1408" height="768" alt="img" src="https://github.com/user-attachments/assets/9aff9c06-b77f-4eab-8435-2868bcdd89b1" />


## Impact and Benefits
Economic Impact: Increases net farmer margins by 20% to 35% by eliminating commission charges and unnecessary handling fees, while offering consumers/bulk buyers 10% to 15% cost savings.

Social Impact: Empowers FPOs with collective bargaining power, standardizes quality grading, and builds financial transparency in rural communities.

Supply Chain Efficiency: Reduces farm-to-door transit time by 30%, drastically cutting post-harvest agricultural wastage (currently sitting at ~15-20% for perishables) through AI-optimized routing.

## Research and References

Ministry of Consumer Affairs, Food & Public Distribution Annual Reports: Data on agricultural supply chain price spreads and consumer price inflation dynamics.

NITI Aayog Strategy for Agriculture Transformation: Frameworks on FPO aggregation models and digital agri-marketplaces in India.

Agmarknet Portal (agmarknet.gov.in): Real-time commodity arrival and price trends across Indian wholesale mandis.

Operations Research Literature: Vehicle Routing Problems with Time Windows (VRPTW) applied to perishable food supply chains.
