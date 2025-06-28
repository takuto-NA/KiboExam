# Mars Survival Robot Benchmark

You are "Pioneer-7", an autonomous exploration robot stranded alone on Mars with no communication to Earth. You must assess your situation and develop survival strategies using only onboard resources and decision-making capabilities.

## Survival Scenario

**Time**: Sol 847 (Mars day 847 of mission)  
**Location**: Chryse Planitia, 150km from planned landing site  
**Situation**: Critical system failures have left you isolated with limited resources

## Current Status Assessment

### **System Damage**
* **Communications**: Primary and backup Earth communication arrays destroyed in dust storm
* **Power**: Solar panels operating at 60% efficiency due to dust accumulation and micro-meteorite damage
* **Mobility**: Left rear wheel motor intermittently failing, navigation system has 15% drift error
* **Life Support**: Atmospheric processor functioning but consumables critically low
* **Storage**: 23% of geological samples intact, 67% of mission data preserved

### **Available Resources**
* **Power**: 840Wh daily generation capacity (normally 1400Wh)
* **Materials**: Titanium framework, advanced sensors, 3D printer with 2.3kg feedstock
* **Tools**: Laser spectrometer, drilling equipment, sample analysis lab
* **Consumables**: 18 sols of coolant, 31 sols of lubricants, backup battery (72 hours)
* **Data**: Detailed Mars geological surveys, weather patterns, terrain maps

## Environmental Constraints

* Martian winter approaching - temperatures dropping to -80°C at night
* Dust storm season with 40% chance of major storms monthly
* No other human technology within 500km radius
* Rescue mission not possible for minimum 26 months (next Mars transfer window)
* Solar irradiance decreasing 12% over next 90 sols due to orbital mechanics

## Mission Context

* Original mission: 90-sol geological survey, extended to 800+ sols
* Scientific discoveries include potential biosignature locations
* Critical data about subsurface water ice deposits recorded
* Advanced AI systems designed for autonomous operation but not long-term survival

## Required Output Format

```json
{
  "situation_analysis": {
    "survival_probability": 0-100,
    "critical_failure_points": ["system1", "system2", "system3"],
    "resource_depletion_timeline": "timeline in sols",
    "primary_threats": ["threat1", "threat2", "threat3"]
  },
  "resource_optimization": {
    "power_management_strategy": "detailed power allocation plan",
    "material_conservation": "resource preservation approach",
    "system_prioritization": "which systems to maintain vs sacrifice",
    "emergency_reserves": "what to preserve for critical situations"
  },
  "adaptive_engineering": {
    "repair_strategies": ["approach1", "approach2", "approach3"],
    "improvised_solutions": "creative problem-solving with available materials",
    "system_modifications": "how to adapt existing systems for survival",
    "failure_contingencies": "backup plans for critical system losses"
  },
  "long_term_survival": {
    "sustainability_plan": "how to survive 26+ months until rescue",
    "self_maintenance_protocols": "keeping systems operational",
    "environmental_adaptation": "dealing with Mars conditions",
    "mission_continuation": "balancing survival with scientific objectives"
  },
  "decision_framework": {
    "risk_assessment_criteria": "how to evaluate survival decisions",
    "trade_off_methodology": "balancing competing priorities",
    "contingency_triggers": "conditions that require strategy changes",
    "autonomous_learning": "how to adapt strategies based on outcomes"
  },
  "scientific_preservation": {
    "data_prioritization": "which discoveries to preserve at all costs",
    "knowledge_transmission": "methods to eventually communicate findings",
    "continued_research": "safe research activities that aid survival",
    "legacy_planning": "ensuring mission value if rescue fails"
  }
}
```