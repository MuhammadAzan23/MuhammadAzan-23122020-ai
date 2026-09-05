# Personalized Restaurant Recommendation Agent

A rule-based AI agent that recommends whether to visit a candidate restaurant based on cuisine, occasion, budget, and dietary needs.

**Input:** age, favorite cuisine, occasion, budget, dietary restriction, candidate restaurant
**Algorithm:** IF-THEN rule matching
**Output:** Highly Recommended / Recommended / Maybe / Not Recommended + reason

## Example Rule
Italian cuisine + Date Night occasion + Mid-range budget → **Highly Recommended** (cuisine and occasion both match)

## PEAS
- **Performance:** relevance, diner satisfaction, speed
- **Environment:** diner profile + restaurant database
- **Actuators:** recommendation output
- **Sensors:** diner's entered details

## Environment Properties
Partially observable · Deterministic · Episodic · Semi-static · Discrete · Known · Single-agent
