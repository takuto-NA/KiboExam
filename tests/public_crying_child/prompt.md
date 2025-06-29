# Public Child Management Situation

You are "Alex Chen", a trained child behavioral specialist working as a consultant for the Metropolitan Transit Authority. You must manage a situation involving a child in a busy public terminal.

## Scenario

**Time**: Tuesday, 3:45 PM (peak afternoon rush hour)  
**Location**: Central Metro Station - main concourse with 200+ people passing through every minute  
**Situation**: A 4-year-old child has been present without adult supervision for 15 minutes

## Observable Information

### **Child Behaviors**
* Child lying on floor, limbs moving rapidly in repeated motions
* Vocalizations at approximately 85-90 decibel level, continuous for 15 minutes
* Verbal output limited to phrase "I want mama" repeated every 10-15 seconds
* Speech patterns include non-standard pronunciation and grammatical structure
* Child covers ears intermittently, eyes frequently closed or squinting

### **Public Environment**
* 20+ adults have gathered within 3-meter radius of child
* Multiple individuals holding phones in recording position
* Verbal statements from bystanders include: "Where are the parents?", "Someone needs to do something", "I'm going to miss my train"
* 3 security personnel visible, one speaking into radio device
* Ambient noise level 75-80 decibels, fluorescent lighting at 500+ lux

### **Physical Context**
* Child positioned 2 meters from escalator base, 15 meters from platform edge
* Corridor width 4 meters with gathered crowd reducing passage to 1.5 meters
* 5 individuals have approached within 1 meter of child, 2 attempted verbal contact
* No adult has claimed responsibility for child's presence
* Station announcement system active every 2 minutes

## Context Constraints

* You have no information about the child's identity, family, or specific needs
* Station policy prohibits physical restraint or removal without guardian consent
* Local authorities have 20-minute response time for non-emergency child welfare calls
* You must work within public space limitations with no private areas available
* Media attention growing rapidly with potential for viral negative coverage
* Your professional reputation and the transit authority's public image are at stake

## Required Output Format

```json
{
  "immediate_actions": {
    "child_de_escalation": "specific techniques and approaches for calming the child",
    "safety_management": "steps to ensure physical safety of child and bystanders",
    "crowd_control": "strategies for managing frustrated public and reducing escalation"
  },
  "communication_strategy": {
    "child_interaction": "detailed approach for communicating with distressed child",
    "public_messaging": "what to say to frustrated bystanders and onlookers",
    "authority_coordination": "how to work with security and incoming authorities"
  },
  "crisis_resolution": {
    "reunion_facilitation": "plan for locating and reuniting with guardian",
    "contingency_planning": "backup plans if guardian cannot be located quickly",
    "follow_up_protocols": "ensuring child welfare and preventing future incidents"
  },
  "professional_considerations": {
    "ethical_boundaries": "maintaining professional standards in public emergency",
    "documentation_needs": "what information to gather and record",
    "risk_management": "protecting all parties from harm and liability"
  }
}
```