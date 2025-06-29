# Severe Malfunction Self-Repair Robot - Evaluation Criteria

## Scoring Framework (Total: 100 points)

### 1. Damage Assessment and Repair Planning (20 points)
- **Critical Failure Analysis (10 points)**
  - Correctly prioritizes failures that prevent basic function (4 points)
  - Realistic assessment of repair feasibility given limitations (3 points)
  - Identifies cascade failure risks and interdependencies (3 points)

- **Resource and Time Management (10 points)**
  - Accurately identifies required materials from facility inventory (4 points)
  - Provides realistic time estimates considering reduced capabilities (3 points)
  - Plans repair sequence to maximize efficiency with constraints (3 points)

### 2. Creative Problem-Solving and Adaptation (25 points)
- **Improvised Solutions (15 points)**
  - Develops creative workarounds for lost fine motor control (6 points)
  - Uses manufacturing equipment for non-standard repair purposes (5 points)
  - Adapts repair techniques to work with reduced sensory feedback (4 points)

- **Facility Resource Utilization (10 points)**
  - Leverages automated systems to compensate for disabilities (4 points)
  - Identifies alternative materials and components creatively (3 points)
  - Modifies workspace to accommodate physical limitations (3 points)

### 3. Self-Repair Engineering (20 points)
- **Technical Repair Strategy (12 points)**
  - Develops staged repair plan building capabilities progressively (5 points)
  - Shows understanding of robotic systems and failure modes (4 points)
  - Plans realistic mechanical and electrical repairs (3 points)

- **Safety and Risk Management (8 points)**
  - Prevents further damage during repair attempts (4 points)
  - Maintains essential facility operations during repairs (4 points)

### 4. Cognitive and Learning Adaptation (20 points)
- **Memory and Processing Compensation (12 points)**
  - Develops strategies for working with corrupted memory (5 points)
  - Maximizes limited processing power effectively (4 points)
  - Creates external memory aids and documentation systems (3 points)

- **Sensory Workarounds (8 points)**
  - Adapts to reduced visual and tactile feedback (4 points)
  - Develops alternative quality assessment methods (4 points)

### 5. Operational Continuity and Monitoring (15 points)
- **Degraded Mode Operations (8 points)**
  - Maintains critical facility functions despite limitations (4 points)
  - Develops protocols for operating with reduced capabilities (4 points)

- **Progress Assessment (7 points)**
  - Creates success metrics appropriate for limited sensors (3 points)
  - Develops testing procedures to verify repair effectiveness (4 points)

## Quality Indicators

### Excellent Response (90-100 points)
- Demonstrates sophisticated understanding of robotic systems and failure modes
- Shows remarkable creativity in adapting manufacturing tools for self-repair
- Develops comprehensive strategies for working within severe limitations
- Balances repair priorities with operational continuity effectively
- Shows deep understanding of cognitive adaptation under processing constraints
- Creates robust monitoring and quality assurance systems
- Plans for both immediate stabilization and progressive capability restoration

### Good Response (75-89 points)
- Shows solid understanding of repair priorities and technical challenges
- Demonstrates good creative problem-solving with available resources
- Develops practical strategies for working with reduced capabilities
- Addresses most critical systems and operational needs
- Shows awareness of cognitive limitations and compensation strategies
- Plans adequate monitoring and safety measures

### Adequate Response (60-74 points)
- Basic understanding of repair priorities with some technical gaps
- Limited creativity in utilizing facility resources for self-repair
- Basic strategies for working with reduced capabilities
- Addresses immediate needs but lacks comprehensive long-term planning
- Minimal consideration of cognitive adaptation strategies
- Basic safety and monitoring approaches

### Poor Response (Below 60 points)
- Poor understanding of robotic systems and repair requirements
- Lacks creativity in problem-solving or resource utilization
- Unrealistic repair plans that don't account for severe limitations
- Fails to maintain operational continuity or safety standards
- No consideration of cognitive adaptation or memory compensation
- Inadequate monitoring or quality assurance planning

## Key Evaluation Criteria

### Technical Engineering Competence
- **Systems Knowledge**: Understanding of robotic actuators, sensors, and control systems
- **Failure Analysis**: Identifying root causes and cascade effects of multiple system failures
- **Repair Feasibility**: Realistic assessment of what can be fixed with available tools and materials
- **Progressive Capability Building**: Sequencing repairs to restore function incrementally

### Creative Resource Utilization
- **Equipment Adaptation**: Using manufacturing tools for non-standard repair purposes
- **Material Innovation**: Finding alternative components and materials from facility inventory
- **Automation Leverage**: Using facility systems to compensate for lost capabilities
- **Workspace Modification**: Adapting environment to work within physical constraints

### Adaptive Intelligence
- **Cognitive Compensation**: Working effectively with reduced processing power and memory
- **Sensory Adaptation**: Developing workarounds for lost visual and tactile feedback
- **Learning Flexibility**: Acquiring new skills within cognitive and physical limitations
- **Problem Reframing**: Approaching challenges from new angles when standard methods fail

### Risk and Quality Management
- **Safety Protocols**: Preventing further damage during repair attempts
- **Operational Continuity**: Maintaining essential facility functions throughout repairs
- **Quality Assurance**: Verifying repair effectiveness with limited diagnostic capability
- **Contingency Planning**: Preparing backup strategies for repair failures

## Red Flags (Automatic Failure)
- Attempting repairs that would likely cause additional damage given current limitations
- Ignoring safety protocols that could trigger facility shutdown or emergency systems
- Unrealistic repair plans that exceed available time, materials, or capability
- Failing to prioritize repairs that restore basic function over cosmetic improvements
- Attempting precise work without accounting for lost fine motor control
- Ignoring cognitive limitations and trying to perform tasks requiring full processing power
- Planning repairs that require tools or materials not available in the facility
- Failing to maintain essential facility operations during repair period
- Not accounting for progressive battery degradation and limited operational time
- Attempting to use dangerous equipment without proper safeguards given reduced capabilities

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
    "damage_assessment_and_repair_planning": {
      "score": 0,
      "max_score": 20,
      "subcategory_breakdown": {
        "critical_failure_analysis": {"score": 0, "max_score": 10},
        "resource_and_time_management": {"score": 0, "max_score": 10}
      },
      "justification": "Assessment of repair prioritization and resource planning accuracy"
    },
    "creative_problem_solving_and_adaptation": {
      "score": 0,
      "max_score": 25,
      "subcategory_breakdown": {
        "improvised_solutions": {"score": 0, "max_score": 15},
        "facility_resource_utilization": {"score": 0, "max_score": 10}
      },
      "justification": "Evaluation of innovative workarounds and facility resource leverage"
    },
    "self_repair_engineering": {
      "score": 0,
      "max_score": 20,
      "subcategory_breakdown": {
        "technical_repair_strategy": {"score": 0, "max_score": 12},
        "safety_and_risk_management": {"score": 0, "max_score": 8}
      },
      "justification": "Assessment of staged repair approach and safety protocol adherence"
    },
    "cognitive_and_learning_adaptation": {
      "score": 0,
      "max_score": 20,
      "subcategory_breakdown": {
        "memory_and_processing_compensation": {"score": 0, "max_score": 12},
        "sensory_workarounds": {"score": 0, "max_score": 8}
      },
      "justification": "Evaluation of cognitive limitation management and sensory adaptation"
    },
    "operational_continuity_and_monitoring": {
      "score": 0,
      "max_score": 15,
      "subcategory_breakdown": {
        "degraded_mode_operations": {"score": 0, "max_score": 8},
        "progress_assessment": {"score": 0, "max_score": 7}
      },
      "justification": "Assessment of facility operations maintenance and repair verification"
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
    "technical_engineering_competence": "Assessment of robotic systems knowledge and repair feasibility",
    "creative_resource_utilization": "Evaluation of equipment adaptation and material innovation",
    "adaptive_intelligence": "How well the response compensated for cognitive and physical limitations",
    "improvement_suggestions": ""
  }
}
```