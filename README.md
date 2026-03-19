# DeliverShield  
## AI-Powered Parametric Insurance for Food Delivery Partners

---

## Requirement & Persona-Based Scenario

Food delivery partners working with platforms like Swiggy and Zomato rely on daily orders for their income. Their earnings are directly affected by external factors such as rain, traffic congestion, and extreme heat.

During heavy rain or extreme conditions, riders are often unable to complete deliveries, which directly reduces their income. These disruptions are unavoidable, yet riders bear the full financial impact.

DeliverShield is designed for this persona by focusing on actual income loss rather than just events, while keeping the system simple and accessible, including support for multiple languages.

---

## Our Solution

DeliverShield is an AI-powered parametric insurance system designed specifically for food delivery partners.

Instead of reacting only to events, the system evaluates real-world conditions and measures their impact on a rider’s ability to earn.

Disruptions are classified into two categories:
- Major disruptions, which trigger payouts  
- Minor disruptions, which provide limited reward-based compensation  

For major disruptions, loss is calculated as:

$$
\text{Loss} = \text{Expected Earnings} - \text{Actual Earnings}
$$

This ensures that payouts reflect actual income loss rather than fixed assumptions.

---

## System Workflow

```
User buys weekly insurance plan
        ↓
System monitors external conditions
        ↓
Data collected (weather, traffic, temperature)
        ↓
Severity score is calculated
        ↓
If high → Major disruption → Payout triggered
If medium → Minor disruption → Reward given
If low → No action
        ↓
If payout → calculate (Expected Earnings - Actual Earnings)
        ↓
Amount credited to user
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
