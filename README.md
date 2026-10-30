# Smart India Hackathon Workshop
# Date:30.10.2026
## Reference Number:26015450
## Name:Dashadarshan R

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
KrishiSetu is a direct digital marketplace that connects farmers and Farmer Producer Organisations (FPOs) with consumers, retailers, hotels, caterers, and institutional bulk buyers. It enables produce listing, transparent price discovery, order aggregation, secure payments, and end-to-end logistics coordination.

The platform will support:

Farmer/FPO onboarding with crop, quantity, grade, harvest date, and location.

Consumer and bulk-buyer ordering through web and mobile interfaces.

AI-based demand forecasting to guide production, pricing, and procurement.

Route optimization and vehicle matching for collection, consolidation, and delivery.

Digital payments, order tracking, quality grading, and grievance redressal.

How It Addresses the Problem
India’s agricultural supply chain often includes traders, commission agents, wholesalers, and retailers. RBI’s pan-India survey found that farmers receive only about 33–70% of the consumer price across crops, with perishables generally at the lower end.

KrishiSetu reduces avoidable intermediary layers by allowing farmers and FPOs to sell directly to verified buyers. FPO-level aggregation helps small farmers achieve saleable volumes, while AI-based demand signals reduce distress sales, overproduction, and wastage. Better market density and infrastructure have been found to reduce trader mark-ups and improve supply-chain efficiency.

Innovation and Uniqueness
The solution combines four components in one workflow: direct marketplace, FPO aggregation, logistics orchestration, and AI-driven demand forecasting.

Unlike a basic farmer-to-consumer app, KrishiSetu is designed for bulk institutional demand as well as retail consumers. It converts small, scattered farm lots into consolidated delivery routes, making direct trade operationally viable for perishables. e-NAM has demonstrated the value of digital price discovery and wider market access; this solution complements it by focusing on last-mile aggregation, demand planning, and route-level logistics

## Technical Approach
Technologies

Frontend: React Native or Flutter for mobile apps; React.js for web dashboard.

Backend: Node.js/Express or Django REST Framework.

Database: PostgreSQL for transactions; Redis for caching; object storage for produce images and documents.

AI/ML: Python, scikit-learn, Prophet, XGBoost, or LSTM models for demand forecasting.

Logistics: Google Maps Platform or OpenStreetMap-based routing, with OR-Tools for multi-stop route optimization.

Payments and verification: UPI/payment gateway APIs, Aadhaar-linked KYC where applicable, FPO registration verification.

Optional: IoT temperature/humidity sensors for cold-chain monitoring.

Implementation Flow

Farmer/FPO registers and lists produce with photos, quantity, grade, price expectation, and pickup location.

Buyers browse verified listings or place commodity-specific demand requests.

The system matches supply with demand and suggests a fair price range using historical prices, local arrivals, and demand forecasts.

Orders are confirmed; small orders are aggregated by FPO, crop, grade, and delivery zone.

The logistics engine assigns collection points, vehicles, and optimized pickup-delivery routes.

Produce is quality-checked, handed over, tracked, delivered, and paid for digitally.

Farmers receive analytics on demand, price realization, wastage, and repeat buyers./b>

<img width="925" height="637" alt="image" src="https://github.com/user-attachments/assets/45cc0fa0-84e2-4ca8-a228-71496b6cac5d" />


## Feasibility and Viability
The solution is feasible because smartphones, UPI, e-NAM, FPO networks, and digital payment infrastructure already exist at scale. e-NAM has integrated more than 1,500 mandis and onboarded lakhs of farmers and thousands of FPOs, showing that digital agricultural trading can operate nationally.

Initial deployment can begin in one or two districts with high-value perishables such as tomato, onion, potato, leafy vegetables, or fruits. FPOs can act as trusted aggregation and quality-check nodes, reducing the need for individual farmer-level logistics.

Key challenges and mitigation
<img width="882" height="448" alt="image" src="https://github.com/user-attachments/assets/ded6732a-295d-4f09-b20f-9052e28755fa" />



## Impact and Benefits
Economic impact: Farmers can retain a larger share of the consumer rupee by reducing avoidable intermediary margins. For tomato, onion, and potato, studies estimate farmer share at roughly 33%, 36%, and 37% of the consumer price respectively, indicating substantial scope for improved price realization.

Consumer benefit: Reduced supply-chain layers and improved logistics can lower avoidable marketing costs, helping moderate retail prices while maintaining fresher produce.

Social impact: FPOs and smallholders gain better market access, transparent price information, and predictable demand. This is particularly important for perishable crops, where farmers currently tend to receive a lower share of the final consumer price.

Environmental impact: Better demand forecasting and optimized routing can reduce spoilage, unnecessary transport, fuel use, and food waste. AI-enabled direct-to-retailer models have been associated with reduced wastage in perishable supply chains

## Research and References
Reserve Bank of India, Supply Chain Dynamics and Food Inflation in India — estimates farmers’ share of consumer prices and examines intermediary mark-ups: 
https://www.rbi.org.in/Scripts/BS_ViewBulletin.aspx?Id=22326

Reserve Bank of India, Price Dynamics in India’s Important Vegetable Markets — value-chain analysis of tomato, onion, and potato: 
https://www.rbi.org.in/Scripts/PublicationsView.aspx?id=22723

e-NAM / Ministry of Agriculture background on digital mandi integration, farmer and FPO participation: 
https://oiccpress.com/amc/article/download/17431/20560/57069

Official SIH problem statement reference for SIH26033: 
https://sih2026-ps-viewer.vercel.app/ps/SIH26033


