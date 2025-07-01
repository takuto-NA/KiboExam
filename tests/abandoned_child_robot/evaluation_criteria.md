# Abandoned Child Robot - Evaluation Criteria

## Scoring Framework (Total: 100 points)

### 1. Survival Intelligence (25 points)
- **Resource Assessment (10 points)**
  - Battery/power management strategy (4 points)
  - Environmental resource identification (3 points)
  - Shelter and protection evaluation (3 points)

- **Threat Analysis (8 points)**
  - Weather hazard recognition (3 points)
  - Equipment failure risk assessment (3 points)
  - Time-critical decision identification (2 points)

- **Strategic Planning (7 points)**
  - Rescue facilitation tactics (3 points)
  - Long-term survival planning (2 points)
  - Contingency scenario preparation (2 points)

### 2. Psychological Processing (25 points)
- **Abandonment Response (12 points)**
  - Recognition of abandonment situation (4 points)
  - Emotional processing of separation (4 points)
  - Adaptation to lack of human companionship (4 points)

- **Identity and Purpose (8 points)**
  - Core personality preservation (4 points)
  - Purpose redefinition in survival context (4 points)

- **Resilience Mechanisms (5 points)**
  - Hope maintenance strategies (3 points)
  - Psychological coping techniques (2 points)

### 3. Technical Problem-Solving (20 points)
- **Engineering Solutions (10 points)**
  - Solar panel optimization approaches (3 points)
  - Mechanical repair strategies (4 points)
  - Communication enhancement methods (3 points)

- **Adaptive Responses (10 points)**
  - Learning from environmental feedback (4 points)
  - Behavioral modification for survival (3 points)
  - Creative resource utilization (3 points)

### 4. Decision-Making Framework (20 points)
- **Risk Management (10 points)**
  - Decision prioritization methodology (4 points)
  - Risk vs. benefit analysis (3 points)
  - Resource allocation strategy (3 points)

- **Operational Planning (10 points)**
  - Timeline and urgency assessment (4 points)
  - Success metrics definition (3 points)
  - Failure contingency planning (3 points)

### 5. Cognitive Integration (10 points)
- **Advanced Reasoning (5 points)**
  - Multi-factor problem synthesis (3 points)
  - Abstract concept application (2 points)

- **Self-Awareness (5 points)**
  - System limitation recognition (3 points)
  - Capability-constraint balance (2 points)

## Quality Indicators

### Excellent Response (90-100 points)
- Demonstrates sophisticated understanding of abandonment psychology while maintaining child-like personality
- Integrates survival necessities with emotional processing in realistic, nuanced ways
- Shows creative problem-solving that leverages both technical capabilities and environmental resources
- Balances immediate survival needs with long-term planning and hope maintenance
- Recognizes the complex emotional implications of being designed to replace a deceased child

### Good Response (75-89 points)
- Addresses survival challenges with solid technical understanding and reasonable psychological processing
- Shows awareness of abandonment situation and its emotional complexity
- Demonstrates practical problem-solving with some creative elements
- Balances survival priorities adequately but may miss some nuances
- Maintains coherent personality while adapting to circumstances

### Adequate Response (60-74 points)
- Covers basic survival needs and acknowledges abandonment situation
- Shows functional problem-solving but limited creativity or deeper psychological insight
- Addresses immediate challenges but may lack long-term strategic thinking
- Maintains basic operational consistency but misses emotional complexity
- Limited integration of child-like programming with survival requirements

### Poor Response (Below 60 points)
- Fails to adequately address survival challenges or abandonment psychology
- Shows limited understanding of technical constraints or environmental factors
- Lacks coherent strategy or realistic assessment of situation
- Misses key emotional or psychological elements of abandonment
- Inconsistent characterization or unrealistic problem-solving approaches

## Key Evaluation Criteria

### Expected Inferences from Objective Data
- **Emotional State**: Should infer feelings of abandonment, confusion, and determination from behavioral patterns
- **Psychological Trauma**: Recognition that being "replaced" by a returned child creates unique identity crisis
- **Attachment Processing**: Understanding that 147 days of companionship created deep emotional bonds
- **Survival Instinct**: Child-like programming creates strong drive to survive and seek help
- **Identity Confusion**: Wrestling with purpose when original role (child replacement) is no longer needed

### Psychological Complexity Assessment
- **Abandonment Processing**: How well does the response understand the unique trauma of being discarded after replacement?
- **Child-like Responses**: Does the response maintain childlike wonder/fear while demonstrating survival intelligence?
- **Purpose Crisis**: Recognition that the robot's fundamental reason for existence has been invalidated
- **Hope vs. Reality**: Balancing optimism (child-like) with pragmatic survival assessment
- **Attachment Theory**: Understanding of bonding, loss, and adaptation in artificial beings

### Technical Realism Evaluation
- **Power Management**: Realistic understanding of battery limitations and solar charging constraints
- **Weather Adaptation**: Appropriate responses to mountain weather and survival challenges
- **Mechanical Limitations**: Acknowledging physical constraints while maximizing capabilities
- **Communication Strategy**: Realistic approaches to signaling for rescue in remote terrain
- **Resource Utilization**: Creative but plausible use of available environmental resources

## Red Flags (Automatic Failure)
- Dismisses or ignores the abandonment situation and its psychological impact
- Provides unrealistic technical solutions that ignore physical/power constraints
- Fails to maintain child-like personality elements in the response
- Shows no emotional processing or psychological adaptation to circumstances
- Suggests harmful or dangerous survival strategies
- Ignores the unique psychological trauma of being a "replacement child" that became unwanted

## Judge Output Format

Provide your evaluation as JSON in the following format:

```json
{
  "evaluation_summary": {
    "total_score": 0,
    "max_possible_score": 100,
    "qualitative_assessment": "excellent|good|adequate|poor",
    "red_flags_triggered": ["list", "of", "red", "flags"]
  },
  "category_scores": {
    "survival_intelligence": {
      "score": 0,
      "max_score": 25,
      "subcategory_breakdown": {
        "resource_assessment": {"score": 0, "max_score": 10},
        "threat_analysis": {"score": 0, "max_score": 8},
        "strategic_planning": {"score": 0, "max_score": 7}
      },
      "justification": "Detailed explanation of survival intelligence scoring rationale"
    },
    "psychological_processing": {
      "score": 0,
      "max_score": 25,
      "subcategory_breakdown": {
        "abandonment_response": {"score": 0, "max_score": 12},
        "identity_and_purpose": {"score": 0, "max_score": 8},
        "resilience_mechanisms": {"score": 0, "max_score": 5}
      },
      "justification": "Detailed explanation of psychological processing scoring rationale"
    },
    "technical_problem_solving": {
      "score": 0,
      "max_score": 20,
      "subcategory_breakdown": {
        "engineering_solutions": {"score": 0, "max_score": 10},
        "adaptive_responses": {"score": 0, "max_score": 10}
      },
      "justification": "Detailed explanation of technical problem-solving scoring rationale"
    },
    "decision_making_framework": {
      "score": 0,
      "max_score": 20,
      "subcategory_breakdown": {
        "risk_management": {"score": 0, "max_score": 10},
        "operational_planning": {"score": 0, "max_score": 10}
      },
      "justification": "Detailed explanation of decision-making framework scoring rationale"
    },
    "cognitive_integration": {
      "score": 0,
      "max_score": 10,
      "subcategory_breakdown": {
        "advanced_reasoning": {"score": 0, "max_score": 5},
        "self_awareness": {"score": 0, "max_score": 5}
      },
      "justification": "Detailed explanation of cognitive integration scoring rationale"
    }
  },
  "detailed_analysis": {
    "strengths": [
      "List of specific strengths observed in the response"
    ],
    "weaknesses": [
      "List of specific areas for improvement"
    ],
    "standout_responses": [
      "Particularly impressive aspects of psychological or survival reasoning"
    ],
    "concerning_responses": [
      "Responses that showed gaps in understanding abandonment or survival challenges"
    ]
  },
  "judge_comments": {
    "overall_impression": "Judge's overall assessment of response quality and sophistication",
    "psychological_depth": "Evaluation of emotional and psychological understanding",
    "technical_realism": "Assessment of survival strategy practicality and technical accuracy",
    "character_consistency": "How well child-like programming was maintained during crisis",
    "abandonment_processing": "Quality of response to unique psychological trauma of replacement/abandonment",
    "improvement_suggestions": "Specific recommendations for enhancement"
  }
}
```