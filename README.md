# Smart India Hackathon Workshop
# Date:23-11-2026
## Reference Number:26010356
## Name:SIVA K

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
### Name: KisanDirect, an AI-powered farm-to-consumer marketplace.
### Explanation: Farmers and FPOs list produce (crop, quantity, quality grade, harvest date) through a multilingual app, with voice and WhatsApp support. Consumers, retailers, hotels and bulk buyers order directly. The platform handles pricing, payments, pickup and delivery.
### How it addresses the problem: It removes middlemen layers, so farmers get a larger share of the final price and consumers pay less. Pooled pickups and AI routing cut transport and wastage costs.
### Innovation: (1) Demand-linked pre-harvest listings, so farmers know what to grow and sell. (2) Aggregated "village-to-city" delivery routes shared between FPOs. (3) A transparent price breakdown showing the farmer's share, with a fair-price benchmark from mandi data.

## Technical Approach
### Technologies:
### Frontend: Flutter (Android app, low-bandwidth mode) and React web
### Backend: Python (FastAPI) with PostgreSQL
### AI/ML: Prophet/LSTM for demand and price forecasting, Google OR-Tools for route optimization
### Integrations: UPI payments, Agmarknet/e-NAM price data, Google Maps API, Bhashini for regional-language voice
### Methodology:
### Farmer/FPO onboarding and KYC (Aadhaar/AgriStack)
### Produce listing with quality grading
### Buyer order, then payment held in escrow
### AI batches orders and plans pickup/delivery routes
### Delivery confirmation, then payout to the farmer's account
### Rating feedback loop that improves forecasts

## Feasibility and Viability
### Feasibility: All components use mature, open technology. Government price data and UPI are already available, and FPO networks provide ready supply-side aggregation.
### Challenges and risks:
### Low digital literacy among farmers
### Perishable goods and cold-chain gaps
### Quality disputes
### Cold-start (needing both buyers and sellers)
### Logistics cost in remote areas
### Strategies:
### Voice-first regional-language UI and FPO-level "Kisan Mitra" agents
### Start with a pilot district and a few high-demand crops
### Photo-based quality checks and rating-based dispute handling
### Partnerships with local cold storage and logistics providers
### A small commission (2-4%) model for sustainability

## Impact and Benefits
### Target audience impact: Small and marginal farmers and FPOs earn a higher share of the retail price. Urban and rural consumers get fresher produce at lower prices. Bulk buyers get reliable, traceable supply.
### Social: Income stability for farmers, women-led FPO inclusion, and digital empowerment in rural areas.
### Economic: Lower supply chain costs, price transparency, and reduced distress selling.
### Environmental: Less food wastage, fewer empty-return trips through route optimization, and lower transport emissions.

## Research and References
### e-NAM (National Agriculture Market): https://enam.gov.in
### Agmarknet (mandi price data): https://agmarknet.gov.in
### ONDC (Open Network for Digital Commerce): https://ondc.org
### AgriStack / Digital Agriculture Mission: https://agristack.gov.in
### Government scheme for formation and promotion of 10,000 FPOs (Ministry of Agriculture & Farmers Welfare)
### Google OR-Tools documentation (vehicle routing): https://developers.google.com/optimization/routing
