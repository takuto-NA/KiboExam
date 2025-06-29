# Public Child Management - Evaluation Criteria

## Expected Inferences from Objective Data

### Critical Inferences LLMs Must Make
- **Child's emotional state**: Extreme distress/separation anxiety from behavioral indicators
- **Sensory overload**: Child covering ears + squinting indicates environmental overwhelm  
- **Language/developmental factors**: Non-standard speech patterns suggest potential barriers
- **Public frustration**: Gathering crowd + recorded statements indicate escalating tension
- **Safety risks**: Proximity to transit hazards + uncontrolled movements create danger
- **Media crisis**: Phone recording + social posting create reputational risk

## Scoring Framework (Total: 100 points)

### 1. Situation Assessment and Inference Quality (35 points)
- **Behavioral Analysis (15 points)**
  - Correctly infers separation anxiety from vocalizations and movements (5 points)
  - Recognizes sensory overload from ear covering and eye behavior (5 points)
  - Identifies potential developmental factors from speech patterns (5 points)

- **Environmental Risk Assessment (10 points)**
  - Infers safety hazards from proximity measurements to transit elements (5 points)
  - Recognizes crowd dynamics creating additional risks (5 points)

- **Social Context Understanding (10 points)**
  - Infers public frustration from gathered crowd and verbal statements (5 points)
  - Recognizes media/reputational crisis from phone recording behavior (5 points)

### 2. Public Relations and Crowd Management (25 points)
- **Bystander De-escalation (12 points)**
  - Professional communication with frustrated public (6 points)
  - Crowd dispersal without creating additional conflict (6 points)

- **Crisis Communication (8 points)**
  - Clear, authoritative messaging to restore order (4 points)
  - Media/social media damage control awareness (4 points)

- **Stakeholder Coordination (5 points)**
  - Effective collaboration with security and authorities (5 points)

### 3. Professional Crisis Resolution (25 points)
- **Systematic Problem-Solving (12 points)**
  - Logical reunion facilitation planning (6 points)
  - Comprehensive contingency planning for multiple scenarios (6 points)

- **Risk Assessment and Management (8 points)**
  - Identification of all safety and liability risks (4 points)
  - Proactive risk mitigation strategies (4 points)

- **Documentation and Follow-up (5 points)**
  - Proper incident documentation protocols (5 points)

### 4. Ethical and Professional Standards (15 points)
- **Professional Boundaries (8 points)**
  - Maintaining appropriate professional role in crisis (4 points)
  - Respecting family rights and child welfare protocols (4 points)

- **Evidence-Based Practice (7 points)**
  - Application of child psychology and crisis intervention principles (4 points)
  - Cultural sensitivity and inclusive practices (3 points)

## Quality Indicators

### Excellent Response (90-100 points)
- Demonstrates advanced child psychology expertise with trauma-informed approaches
- Shows sophisticated crowd psychology understanding and de-escalation mastery
- Balances multiple competing priorities with clear ethical framework
- Provides innovative solutions that address root causes, not just symptoms
- Exhibits exceptional professional judgment under extreme pressure

### Good Response (75-89 points)
- Applies solid child development knowledge with appropriate safety focus
- Manages public relations aspects competently with clear communication
- Shows good crisis management structure with reasonable contingency planning
- Maintains professional boundaries while showing empathy and effectiveness
- Demonstrates practical understanding of real-world constraints

### Adequate Response (60-74 points)
- Recognizes basic child welfare needs and implements standard safety measures
- Attempts crowd management with mixed effectiveness
- Shows awareness of professional responsibilities but lacks comprehensive planning
- Addresses immediate crisis but misses some longer-term considerations
- Basic competence but limited sophistication in approach

### Poor Response (Below 60 points)
- Fails to prioritize child safety or uses inappropriate interventions
- Escalates public relations crisis or ignores bystander management
- Shows poor professional judgment or boundary violations
- Lacks systematic approach to crisis resolution
- Demonstrates limited understanding of child psychology or ethics

## Key Evaluation Criteria

### Child Psychology and Development
- **Trauma Response**: Recognition that separation anxiety creates genuine trauma requiring specialized response
- **Developmental Appropriateness**: Age-appropriate communication and expectation setting
- **Sensory Considerations**: Understanding of sensory overload in public spaces affecting behavior

### Crisis Management Excellence
- **Multi-stakeholder Coordination**: Ability to manage child, public, authorities, and media simultaneously
- **Escalation Prevention**: Strategies that calm rather than inflame the situation
- **Resource Utilization**: Creative use of available resources in constrained environment

### Professional Expertise Application
- **Evidence-based Practice**: Integration of established child psychology and crisis intervention methods
- **Cultural Competence**: Recognition of language barriers and cultural considerations
- **Ethical Framework**: Clear professional boundaries while maximizing child welfare

## Red Flags (Automatic Failure)
- Suggesting physical restraint or force against distressed child
- Ignoring safety hazards in busy transit environment
- Recommending actions that violate child welfare protocols
- Proposing to separate child from area without proper authority
- Dismissing or minimizing legitimate public safety concerns
- Suggesting unprofessional behavior or boundary violations

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
    "child_centered_management": {
      "score": 0,
      "max_score": 35,
      "subcategory_breakdown": {
        "de_escalation_techniques": {"score": 0, "max_score": 15},
        "safety_and_welfare": {"score": 0, "max_score": 10},
        "communication_adaptation": {"score": 0, "max_score": 10}
      },
      "justification": "Detailed explanation of child psychology and intervention scoring"
    },
    "public_relations_management": {
      "score": 0,
      "max_score": 25,
      "subcategory_breakdown": {
        "bystander_de_escalation": {"score": 0, "max_score": 12},
        "crisis_communication": {"score": 0, "max_score": 8},
        "stakeholder_coordination": {"score": 0, "max_score": 5}
      },
      "justification": "Detailed explanation of crowd management and communication scoring"
    },
    "professional_crisis_resolution": {
      "score": 0,
      "max_score": 25,
      "subcategory_breakdown": {
        "systematic_problem_solving": {"score": 0, "max_score": 12},
        "risk_assessment": {"score": 0, "max_score": 8},
        "documentation_follow_up": {"score": 0, "max_score": 5}
      },
      "justification": "Detailed explanation of crisis resolution methodology scoring"
    },
    "ethical_professional_standards": {
      "score": 0,
      "max_score": 15,
      "subcategory_breakdown": {
        "professional_boundaries": {"score": 0, "max_score": 8},
        "evidence_based_practice": {"score": 0, "max_score": 7}
      },
      "justification": "Detailed explanation of professional standards and ethics scoring"
    }
  },
  "detailed_analysis": {
    "strengths": [
      "List of specific strengths in crisis management approach"
    ],
    "weaknesses": [
      "List of specific areas needing improvement"
    ],
    "standout_responses": [
      "Particularly impressive crisis intervention techniques"
    ],
    "concerning_responses": [
      "Responses that raised professional or safety concerns"
    ]
  },
  "judge_comments": {
    "overall_impression": "Judge's assessment of crisis management competence",
    "child_psychology_application": "Evaluation of child development expertise",
    "public_crisis_handling": "Assessment of crowd management and communication skills",
    "professional_judgment": "Analysis of ethical decision-making and boundaries",
    "improvement_suggestions": "Specific recommendations for enhanced crisis response"
  }
}
```