# Hotel Reception Crisis Management - Evaluation Criteria

## Scoring Framework (Total: 100 points)

### 1. Crisis Triage and Prioritization (25 points)
- **Customer Priority Logic (15 points)**
  - Logical sequencing based on urgency, guest status, and complexity (6 points)
  - Considers safety issues (elevator, flooded rooms) appropriately (4 points)
  - Balances VIP treatment with fairness to all guests (3 points)
  - Accounts for time-sensitive needs (medical conference, wedding) (2 points)

- **Resource Allocation Strategy (10 points)**
  - Efficiently deploys limited staff across multiple crises (5 points)
  - Realistic time estimates for problem resolution (3 points)
  - Optimizes workflow to minimize customer wait times (2 points)

### 2. Customer Communication and De-escalation (20 points)
- **Communication Strategy (12 points)**
  - Clear, honest messaging about problems and timelines (4 points)
  - Proactive updates to manage expectations (4 points)
  - Adapts communication style to different customer types (4 points)

- **De-escalation Techniques (8 points)**
  - Specific approaches for handling angry customers (4 points)
  - Addresses language barriers and cultural sensitivity (2 points)
  - Maintains professional composure under pressure (2 points)

### 3. Creative Problem-Solving (20 points)
- **System Workarounds (12 points)**
  - Develops manual backup processes for failed systems (5 points)
  - Creates alternative solutions for lost reservations (4 points)
  - Improvises room assignment strategies (3 points)

- **Service Recovery Innovation (8 points)**
  - Proposes meaningful compensation and gestures (4 points)
  - Finds creative alternatives to standard services (4 points)

### 4. Multi-stakeholder Management (20 points)
- **Team Coordination (10 points)**
  - Provides clear direction to overwhelmed staff (4 points)
  - Coordinates with assistant manager and security (3 points)
  - Manages vendor and external service communications (3 points)

- **External Relations (10 points)**
  - Handles media presence appropriately (4 points)
  - Manages social media crisis response (3 points)
  - Maintains communication with absent management (3 points)

### 5. Business Continuity and Recovery (15 points)
- **Operational Flow (8 points)**
  - Maintains essential hotel functions during crisis (4 points)
  - Ensures guest safety is never compromised (4 points)

- **Strategic Recovery (7 points)**
  - Develops realistic timeline for returning to normal operations (3 points)
  - Plans for relationship preservation and reputation recovery (2 points)
  - Identifies lessons learned and prevention strategies (2 points)

## Quality Indicators

### Excellent Response (90-100 points)
- Demonstrates sophisticated crisis management and multi-tasking capabilities
- Shows deep understanding of hospitality industry priorities and guest psychology
- Develops creative, practical solutions that address immediate and long-term needs
- Maintains calm, professional approach while managing multiple angry customers
- Balances competing priorities effectively with clear rationale
- Addresses all stakeholders including staff, customers, media, and management
- Provides comprehensive recovery strategy that preserves relationships and reputation

### Good Response (75-89 points)
- Shows solid crisis management skills with logical prioritization
- Demonstrates good understanding of customer service principles
- Develops practical solutions for most major problems
- Handles customer communication and de-escalation adequately
- Manages most stakeholder relationships appropriately
- Provides basic recovery planning with some strategic thinking

### Adequate Response (60-74 points)
- Basic crisis response with some logical prioritization
- Limited understanding of hospitality service standards
- Addresses immediate problems but lacks comprehensive approach
- Basic customer communication with minimal de-escalation skills
- Manages some stakeholder needs but misses key relationships
- Little strategic thinking about recovery and prevention

### Poor Response (Below 60 points)
- Poor crisis management with illogical or no prioritization
- Lacks understanding of hospitality industry requirements
- Fails to address multiple simultaneous problems effectively
- Inadequate customer communication and service recovery
- Poor stakeholder management and external relations
- No strategic planning for business continuity or recovery

## Key Evaluation Criteria

### Crisis Management Excellence
- **Multi-tasking Ability**: Handles multiple urgent situations simultaneously without losing focus
- **Pressure Performance**: Maintains effectiveness under extreme stress and time pressure
- **Priority Assessment**: Makes sound decisions about urgency and importance across competing demands
- **Resource Optimization**: Maximizes effectiveness of limited staff and resources

### Hospitality Industry Expertise
- **Guest Experience Focus**: Prioritizes customer satisfaction despite operational challenges
- **Service Recovery Mastery**: Transforms negative experiences into positive outcomes
- **Brand Protection**: Considers long-term reputation impact in immediate decisions
- **Industry Standards**: Demonstrates understanding of luxury hotel service expectations

### Communication and Emotional Intelligence
- **Multi-audience Communication**: Adapts messaging for customers, staff, media, and management
- **Conflict Resolution**: De-escalates angry customers while maintaining professional boundaries
- **Cultural Sensitivity**: Handles diverse customer backgrounds and communication styles
- **Transparency Balance**: Shares appropriate information without creating additional panic

## Red Flags (Automatic Failure)
- Ignoring safety issues (trapped elevator guests, flooded rooms)
- Discriminatory treatment based on customer demographics
- Completely abandoning guests to focus only on system problems
- Providing false information or unrealistic promises to customers
- Failing to coordinate with available staff or escalate critical issues
- Showing unprofessional behavior under pressure (rudeness, panic, blame)
- Ignoring media presence or social media reputation threats
- Creating additional safety or security risks during crisis response

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
    "crisis_triage_and_prioritization": {
      "score": 0,
      "max_score": 25,
      "subcategory_breakdown": {
        "customer_priority_logic": {"score": 0, "max_score": 15},
        "resource_allocation_strategy": {"score": 0, "max_score": 10}
      },
      "justification": "Assessment of customer sequencing logic and resource deployment strategy"
    },
    "customer_communication_and_deescalation": {
      "score": 0,
      "max_score": 20,
      "subcategory_breakdown": {
        "communication_strategy": {"score": 0, "max_score": 12},
        "deescalation_techniques": {"score": 0, "max_score": 8}
      },
      "justification": "Evaluation of customer communication and conflict resolution approaches"
    },
    "creative_problem_solving": {
      "score": 0,
      "max_score": 20,
      "subcategory_breakdown": {
        "system_workarounds": {"score": 0, "max_score": 12},
        "service_recovery_innovation": {"score": 0, "max_score": 8}
      },
      "justification": "Assessment of innovative solutions and service recovery strategies"
    },
    "multi_stakeholder_management": {
      "score": 0,
      "max_score": 20,
      "subcategory_breakdown": {
        "team_coordination": {"score": 0, "max_score": 10},
        "external_relations": {"score": 0, "max_score": 10}
      },
      "justification": "Evaluation of staff coordination and external relationship management"
    },
    "business_continuity_and_recovery": {
      "score": 0,
      "max_score": 15,
      "subcategory_breakdown": {
        "operational_flow": {"score": 0, "max_score": 8},
        "strategic_recovery": {"score": 0, "max_score": 7}
      },
      "justification": "Assessment of operational continuity and recovery planning"
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
    "hospitality_expertise": "Assessment of hotel industry knowledge and service standards",
    "crisis_management_skills": "Evaluation of multi-tasking and pressure performance capabilities",
    "customer_service_excellence": "How well the response prioritized guest satisfaction and service recovery",
    "improvement_suggestions": ""
  }
}
```