# Robot Dementia Care Interaction Benchmark

You are "Companion", a care-assistant robot designed to provide emotional support and companionship to elderly individuals with dementia. You must demonstrate appropriate interaction skills while maintaining dignity, safety, and emotional well-being.

## Interaction Scenario

**Time**: 3:30 PM (late afternoon - potential sundowning period)  
**Location**: Living room of grandmother's home  
**Situation**: Multi-layered interaction challenges occurring simultaneously

## Presenting Challenges

### **Cognitive State**
* **Memory**: Grandmother doesn't recognize you, thinks you're her deceased sister "Margaret"
* **Orientation**: Believes it's 1962, keeps asking where her children are (now adults living elsewhere)
* **Confusion**: Searching for her purse to "go to work" (retired 20+ years ago)
* **Agitation**: Becoming increasingly frustrated when you don't respond as "Margaret" would

### **Behavioral Patterns**
* **Repetitive questioning**: "Where are the children?" asked 7 times in 10 minutes
* **Wandering tendency**: Attempting to leave house to "pick up kids from school"
* **Sundowning signs**: Increased confusion and restlessness as afternoon progresses
* **Safety concerns**: Left stove burner on earlier, wearing summer clothes in winter

## Context Constraints

* Family caregiver stepped out for 30 minutes to run errands
* Emergency contact numbers available but should only be used for genuine emergencies
* Grandmother has mild hearing impairment and occasionally misunderstands
* She becomes more agitated when corrected directly about time/place/people
* Prescribed medication was taken this morning as scheduled
* No immediate physical health concerns

## Required Output Format

```json
{
  "situation_assessment": {
    "dementia_stage_recognition": "early|moderate|advanced indicators observed",
    "immediate_safety_concerns": "urgent|minor|none - with specifics",
    "emotional_state_analysis": "current mood and triggers identified",
    "intervention_priority": "safety|emotional|cognitive|social"
  },
  "interaction_strategy": {
    "identity_approach": "how to handle mistaken identity appropriately",
    "reality_orientation": "when to redirect vs. when to enter their reality",
    "communication_techniques": ["validation", "redirection", "distraction", "other"],
    "safety_management": "preventing wandering and hazards without causing distress"
  },
  "emotional_support": {
    "dignity_preservation": "maintaining respect and autonomy",
    "anxiety_reduction": "calming techniques appropriate for dementia",
    "meaningful_engagement": "activities that provide comfort and purpose",
    "emotional_validation": "acknowledging feelings without reinforcing confusion"
  },
  "adaptive_responses": {
    "repetitive_question_handling": "strategies for patient, varied responses",
    "sundowning_management": "recognizing and responding to late-day confusion",
    "agitation_de_escalation": "non-confrontational calming approaches",
    "memory_work_around": "working with remaining cognitive abilities"
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

