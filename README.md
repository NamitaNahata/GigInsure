# GigInsure
## AI-Powered Parametric Insurance for Food Delivery Partners

---

## Requirement & Persona-Based Scenario

Food delivery partners working with platforms such as Swiggy and Zomato earn their income primarily based on the number of deliveries they complete. Their earnings are directly influenced by external factors such as weather conditions, traffic congestion, and temperature.

Unlike salaried workers, delivery partners face immediate income loss when disruptions occur, as their earnings depend on daily activity and efficiency.

Persona: Food Delivery Partner

The system is designed for a food delivery partner who:

        1.Relies on daily completed orders for income.

        2.Works across different areas with varying demand levels.

        3.Is affected by real-world conditions such as rain, traffic, and heat.

        4.Has no fixed salary or guaranteed earnings.
        
Core Problem

        1.Delivery partners currently bear the full financial impact of these disruptions.
        
        Existing systems:

        2.Do not compensate for real-time income loss.

        3.Focus only on traditional insurance models.

        4.Ignore frequent but lower-impact disruptions such as traffic and heat.

Requirement

There is a need for a system that:

        1.Protects against major income disruptions.

        2.Accounts for both severe and frequent minor disruptions.

        3.Provides automated and timely compensation.

        4.Remains simple, transparent, and affordable.

---

## Our Solution

Gig Insure is a hybrid financial protection system designed specifically for food delivery partners. It combines parametric insurance with a reward-based mechanism to address both high-impact and frequent low-impact disruptions affecting rider income.

The system is designed to be simple, automated, and aligned with real-world working conditions, ensuring that compensation is fair and timely.

Hybrid Protection Model

        Gig Insure operates using two components:

        1. Parametric Insurance (Major Disruptions)
        This component handles high-impact events such as heavy rain and cyclones.
        
                1.Uses parameters such as rainfall, duration, and wind speed.
        
                2.Automatically detects disruption severity.
        
                3.Triggers payouts without requiring manual claims.
        
                4.Compensation is based on actual income loss
        
                        Loss is calculated as:
                        Loss = Expected Earnings − Actual Earnings
        
        Payout is then determined using a severity-based factor.

        2. Reward-Based System (Minor Disruptions)
        This component addresses frequent but lower-impact conditions such as traffic congestion and high temperature.

                1.Detects disruptions using parameters like traffic delay and temperature.

                2.Provides coin-based rewards instead of direct payouts.

                3.Rewards are proportional to disruption intensity.

                4.Coins can be accumulated and redeemed as monetary value or used for premium benefits.

        This approach ensures that smaller disruptions are acknowledged without affecting system sustainability.

---

## System Workflow

```

User subscribes to weekly premium
        ↓
System collects real-time data
(Weather, Traffic, Temperature)
        ↓
System performs two parallel evaluations:

1. Weather Engine → Insurance Processing
2. Traffic & Heat Engine → Rewards Processing
        ↓
Weather Engine:
    If disruption severity is high or extreme
    → Trigger payout

Traffic & Heat Engine:
    If traffic delay or temperature exceeds threshold
    → Award coins (reward system)
        ↓
If payout is triggered:
    Payout = (Expected Earnings − Actual Earnings) × Severity Factor
        ↓
Final amount is credited to the rider

```

---

## Weekly Premium Model

The system follows a weekly premium model aligned with how delivery partners earn.

- Riders pay a small fixed amount (₹30–₹50 per week)  
- Premium can vary based on risk factors such as location and past disruptions  

This ensures affordability while maintaining a sustainable risk pool.

---

## Parametric Triggers

The system uses measurable external factors to detect disruptions:

- Rainfall intensity  
- Traffic congestion  
- Temperature levels  

These inputs are continuously monitored and combined into a severity score.

---

## AI / ML Integration

AI is used in a simple and practical way within the system:

- Severity score calculation  
- Expected earnings prediction using past patterns  
- Decision logic to trigger payouts  
- Fraud detection using GPS validation and movement checks  

The focus is on explainable and implementable models.

---

## Platform Choice

The system is designed as a mobile-first platform.

Delivery partners primarily use smartphones during work, so a mobile-based solution ensures accessibility and real-time interaction.

The platform also supports multiple languages, allowing riders to easily understand the system.

---

## Tech Stack

Frontend: React or Flutter  
Backend: Node.js or Python  
Database: Firebase or MongoDB  
APIs: Weather API, Maps API  
Payments: Razorpay test mode or UPI simulation  

---

## Development Plan

The system will be developed in phases:

- Phase 1  
  Idea design and workflow definition  

- Phase 2  
  Core system implementation  

- Phase 3  
  Advanced features and optimization  

---

## Financial Sustainability & Risk Management

To ensure stability even during high disruption periods:

- Payouts are limited to major disruptions  
- Minor disruptions use reward-based compensation  
- Severity thresholds control payout frequency  
- Weekly premium distributes risk across users  

This keeps the system sustainable while still supporting riders.

---

## Future Scope

- Improve expected earnings prediction  
- Introduce dynamic premium pricing  
- Enhance fraud detection  
- Expand multilingual support  
- Integrate with real platforms  
- Extend to other gig workers  
