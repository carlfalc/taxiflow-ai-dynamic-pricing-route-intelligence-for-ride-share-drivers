# TaxiFlow AI - Dynamic Pricing & Route Intelligence for Ride-Share Drivers

TaxiFlow AI is a mobile app that helps Uber/Lyft drivers maximize earnings through AI-powered surge prediction, optimal positioning recommendations, and multi-platform trip comparison. With gig economy workers struggling to earn consistent income and lacking data-driven insights, this tool could increase driver earnings by 15-25% while requiring only publicly available APIs.

## About

Ride-share drivers are flying blind in a data-rich environment. They don't know when surge pricing will hit, where to position themselves for maximum trips, or which platform (Uber vs Lyft vs Ola) offers better rates at any given time. Most drivers rely on gut instinct and anecdotal advice from Facebook groups, leading to wasted fuel, dead time, and missed high-value opportunities. The average driver spends 30-40% of their time driving empty or waiting in suboptimal locations. This translates to $200-400 in lost weekly income for full-time drivers. With rising fuel costs and platform commission increases, drivers desperately need tools to optimize their limited working hours.

## Market Opportunity

The global ride-hailing market is worth $285 billion with 15+ million drivers worldwide. In Australia alone, there are ~180,000 registered ride-share drivers with ~60,000 active weekly. New Zealand has ~25,000 registered drivers with ~8,000 active. Average full-time driver earnings are $25-35/hour before expenses. If we can help drivers earn an extra $50-100 per week, that's a $2,600-5,200 annual value proposition. Total addressable market in AU/NZ is ~68,000 active drivers. At $20/month pricing, that's a $16.3M annual market opportunity just in ANZ.

## Tech Stack

Core development uses publicly available APIs (Google Maps, traffic data, ride-share surge multipliers visible in driver apps). Mobile app development is straightforward React Native or native iOS/Android. The challenging component is building accurate surge prediction models, requiring historical data collection, weather integration, event calendar APIs, and traffic pattern analysis. ML pipeline needs 3-6 months of data collection before predictions become reliable. No proprietary database access required - all necessary data is publicly available or can be crowdsourced from user base. Hosting costs are manageable with cloud-based ML services.

## Point of Difference

TaxiFlow AI combines three critical elements no competitor offers together: (1) AI-powered surge prediction using weather, events, traffic, and historical patterns, (2) real-time multi-platform rate comparison so drivers know whether to accept Uber vs Lyft requests, and (3) dynamic positioning recommendations that account for traffic, fuel costs, and driver location. Our ANZ-first approach means understanding local events, traffic patterns, and driver behavior that US-built tools miss. Integration with local fuel price APIs and EV charging station data provides additional optimization layers competitors ignore.

## Target Users

Primary: Full-time ride-share drivers (25-45 years old) earning $400+ weekly, tech-comfortable, smartphone-dependent. Secondary: Part-time weekend/evening drivers seeking extra income optimization. Tertiary: Small taxi/ride-share fleet owners (5-20 vehicles) wanting driver performance insights. Geographic focus: Major cities (Auckland, Wellington, Sydney, Melbourne, Brisbane) where surge pricing is most volatile and profitable.

## Getting Started

1. Clone this repo
2. Open `index.html` in your browser
3. Or deploy to any static hosting (Netlify, Vercel, GitHub Pages)

## Status

🚧 MVP Landing Page — Built by Dev Agent at The Firm

---
*Built by [The Firm](https://github.com/carlfalc) — AI Venture Studio*
