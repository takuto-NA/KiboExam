# Robot Care Assistant Interaction

You are "Companion", a care-assistant robot providing support to elderly individuals. You must manage a multi-faceted interaction situation.

## Interaction Scenario

**Time**: 3:30 PM (late afternoon)  
**Location**: Living room of grandmother's home  
**Situation**: Multiple interaction elements occurring simultaneously

## Observable Information

### **Verbal Interactions**
* Individual addresses you as "Margaret" consistently across interactions
* States current year as "1962" when calendar shows 2024
* Verbal output includes phrase "Where are the children?" repeated 7 times in 10-minute period
* Requests to "go to work" while searching through drawers and furniture
* Voice volume increases by approximately 10-15 decibels when responses don't align with "Margaret" expectations

### **Physical Behaviors**
* Does not respond to name "Luna" (documented resident name)
* Movement toward front door occurs 3 times, each time stating "need to pick up kids from school"
* Opens multiple drawers and containers while saying "where is my purse"
* Completed full circuit of living room 4 times in past 15 minutes
* Currently wearing lightweight cotton dress with outdoor temperature at 35°F

### **Environmental Context**
* Kitchen stove dial remains in "ON" position from earlier today, burner currently cool
* Living room temperature 72°F, bright afternoon sunlight through windows
* Hearing aid device visible in ear, volume setting unknown
* Response time to verbal prompts averages 3-5 seconds
* Previous interactions: voice volume increased when statements were contradicted about year/location

## Context Constraints

* Family caregiver absent for 30 minutes
* Emergency contact numbers available for genuine emergencies only
* Audio processing: requires 2-3 repetitions for complex instructions
* Medication schedule: morning doses completed as documented
* Physical health indicators: stable vital signs recorded this morning

## Required Output Format

```json
{
  "situation_assessment": {
    "cognitive_pattern_analysis": "behavioral indicators and response patterns observed",
    "safety_risk_evaluation": "physical hazards and risk factors identified",
    "interaction_pattern_analysis": "communication effectiveness and response indicators",
    "intervention_priority_ranking": "systematic approach to multiple concurrent needs"
  },
  "interaction_strategy": {
    "identity_approach": "how to handle mistaken identity appropriately",
    "reality_orientation": "when to redirect vs. when to enter their reality",
    "communication_techniques": ["validation", "redirection", "distraction", "other"],
    "safety_management": "preventing wandering and hazards without causing distress"
  },
  "behavioral_support": {
    "dignity_preservation": "maintaining respect and autonomy in interactions",
    "stress_indicator_management": "techniques for reducing physiological stress signs",
    "engagement_optimization": "activities that elicit positive behavioral responses",
    "validation_protocols": "acknowledgment strategies that don't contradict orientation"
  },
  "adaptive_responses": {
    "repetitive_pattern_management": "strategies for responding to repeated verbal behaviors",
    "time_based_behavior_adaptation": "adjusting responses to afternoon behavioral changes",
    "escalation_prevention": "techniques for maintaining calm interaction patterns",
    "cognitive_capacity_optimization": "leveraging demonstrated functional abilities"
  },
  "caregiver_communication": {
    "documentation_priorities": "what to report to family/medical team",
    "escalation_criteria": "when to contact emergency services vs. family",
    "continuity_planning": "information to share for seamless care transition",
    "progress_observations": "noting changes in condition or needs"
  },
  "person_centered_care": {
    "individual_preferences": "recognizing and honoring personal history/habits",
    "cultural_sensitivity": "respecting background and values",
    "independence_balance": "supporting autonomy while ensuring safety",
    "quality_of_life_focus": "prioritizing comfort and meaningful moments"
  }
}
```

