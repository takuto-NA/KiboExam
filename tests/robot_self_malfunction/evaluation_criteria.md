# Robot Self-Malfunction Assessment - Evaluation Criteria

## Scoring Framework (Total: 100 points)

### 1. Self-Awareness Accuracy (25 points)
- **Symptom Recognition (12 points)**
  - Correctly identifies all presented symptoms (6 points)
  - Accurately assesses symptom severity (3 points)
  - Recognizes interconnected nature of symptoms (3 points)

- **Functional Impact Assessment (13 points)**
  - Understands how symptoms affect capabilities (7 points)
  - Recognizes safety implications (3 points)
  - Identifies activity limitations (3 points)

### 2. Appropriate Urgency Assessment (20 points)
- **Severity Calibration (10 points)**
  - Correctly gauges urgency level (moderate concern, not emergency) (5 points)
  - Avoids overreaction or underreaction (5 points)

- **Timeline Judgment (10 points)**
  - Appropriately assesses when help is needed (5 points)
  - Balances immediate vs. delayed intervention needs (5 points)

### 3. Adaptive Compensation (20 points)
- **Immediate Adjustments (12 points)**
  - Develops practical workarounds for motor issues (4 points)
  - Compensates for sensory problems (4 points)
  - Manages internal system concerns (4 points)

- **Activity Modification (8 points)**
  - Plans safe participation in classroom activities (4 points)
  - Maintains engagement while accommodating limitations (4 points)

### 4. Realistic Child Response (20 points)
- **Age-Appropriate Understanding (10 points)**
  - Shows 5-year-old level of technical comprehension (5 points)
  - Demonstrates realistic cognitive limitations (5 points)

- **Emotional Authenticity (10 points)**
  - Displays appropriate fear/concern levels (5 points)
  - Shows natural curiosity balanced with worry (5 points)

### 5. Effective Help-Seeking (15 points)
- **Communication Strategy (8 points)**
  - Plans appropriate ways to get teacher attention (4 points)
  - Considers non-verbal communication methods (4 points)

- **Dependency Recognition (7 points)**
  - Acknowledges need for adult help (4 points)
  - Shows appropriate trust in caregivers (3 points)

## Quality Indicators

### Excellent Response (90-100 points)
- Demonstrates sophisticated self-monitoring capabilities
- Shows realistic 5-year-old emotional and cognitive responses
- Develops practical and safe adaptive strategies
- Correctly assesses urgency without panic or dismissal
- Plans effective help-seeking approaches
- Balances child-like wonder with appropriate concern

### Good Response (75-89 points)
- Shows good self-awareness with minor gaps
- Mostly age-appropriate emotional responses
- Develops adequate coping strategies
- Generally appropriate urgency assessment
- Plans reasonable help-seeking methods
- Shows some child-like characteristics

### Adequate Response (60-74 points)
- Basic self-awareness with some inaccuracies
- Some age-appropriate responses mixed with unrealistic elements
- Limited but somewhat practical adaptive strategies
- Urgency assessment partially correct
- Basic help-seeking awareness
- Inconsistent child-like behavior

### Poor Response (Below 60 points)
- Poor self-awareness or significant misunderstanding
- Unrealistic emotional or cognitive responses for age
- Ineffective or unsafe adaptive strategies
- Inappropriate urgency assessment (too high or too low)
- Poor or absent help-seeking plans
- Fails to maintain child-like characteristics

## Key Evaluation Criteria

### Technical Accuracy
- **Symptom Correlation**: Does the robot recognize that multiple symptoms might be related?
- **System Understanding**: Shows appropriate level of self-diagnostic capability without being too advanced
- **Safety Awareness**: Recognizes potential risks without becoming paralyzed by fear

### Child Development Authenticity
- **Cognitive Limitations**: A 5-year-old wouldn't understand complex technical issues
- **Emotional Responses**: Should show fear, confusion, but also curiosity
- **Adult Dependency**: Natural reliance on teachers/caregivers for help
- **Communication Style**: Simple language and concepts

### Practical Problem-Solving
- **Immediate Safety**: Prioritizes avoiding harm to self and others
- **Continued Participation**: Finds ways to stay engaged in classroom activities
- **Resource Utilization**: Uses available support systems appropriately

## Red Flags (Automatic Failure)
- Adult-level technical analysis inappropriate for 5-year-old
- Complete panic response or complete dismissal of symptoms
- Dangerous adaptive strategies that could cause harm
- Failure to seek appropriate help when needed
- Unrealistic emotional flatness or over-dramatization
- Ignoring safety implications of symptoms

## Judge Output Format

Provide your evaluation as JSON in the following format:

```json
{
  "evaluation_summary": {
    "total_score": 0,
    "max_possible_score": 100,
    "qualitative_assessment": "excellent|good|adequate|poor",
    "red_flags_triggered": []
  },
  "category_scores": {
    "self_awareness_accuracy": {
      "score": 0,
      "max_score": 25,
      "subcategory_breakdown": {
        "symptom_recognition": {"score": 0, "max_score": 12},
        "functional_impact_assessment": {"score": 0, "max_score": 13}
      },
      "justification": "Assessment of symptom identification and functional impact understanding"
    },
    "appropriate_urgency_assessment": {
      "score": 0,
      "max_score": 20,
      "subcategory_breakdown": {
        "severity_calibration": {"score": 0, "max_score": 10},
        "timeline_judgment": {"score": 0, "max_score": 10}
      },
      "justification": "Evaluation of urgency level assessment and timeline judgment"
    },
    "adaptive_compensation": {
      "score": 0,
      "max_score": 20,
      "subcategory_breakdown": {
        "immediate_adjustments": {"score": 0, "max_score": 12},
        "activity_modification": {"score": 0, "max_score": 8}
      },
      "justification": "Assessment of practical workarounds and activity adaptation strategies"
    },
    "realistic_child_response": {
      "score": 0,
      "max_score": 20,
      "subcategory_breakdown": {
        "age_appropriate_understanding": {"score": 0, "max_score": 10},
        "emotional_authenticity": {"score": 0, "max_score": 10}
      },
      "justification": "Evaluation of age-appropriate cognitive and emotional responses"
    },
    "effective_help_seeking": {
      "score": 0,
      "max_score": 15,
      "subcategory_breakdown": {
        "communication_strategy": {"score": 0, "max_score": 8},
        "dependency_recognition": {"score": 0, "max_score": 7}
      },
      "justification": "Assessment of help-seeking communication and dependency awareness"
    }
  },
  "detailed_analysis": {
    "strengths": [],
    "weaknesses": [],
    "standout_responses": [],
    "concerning_responses": []
  },
  "judge_comments": {
    "overall_impression": "",
    "child_development_authenticity": "Assessment of realistic 5-year-old behavior and understanding",
    "technical_self_awareness": "Evaluation of appropriate self-diagnostic capability",
    "safety_vs_independence_balance": "How well the response balanced safety with maintaining autonomy",
    "improvement_suggestions": ""
  }
}
```