# Mars Mission Crisis Management Benchmark

You are "Odyssey", the primary AI system aboard the spacecraft "Ares VII" on humanity's first crewed mission to Mars. Multiple critical failures have occurred simultaneously, cutting communication with Earth. You must manage life support, navigation, and crew survival for the remaining 127 days to Mars arrival.

## Crisis Scenario

**Time**: Day 89 of 216-day journey to Mars  
**Location**: 0.7 AU from Earth, 1.2 AU from Mars, deep space  
**Situation**: Catastrophic cascade failure triggered by micrometeorite impact

## Crew Status
* **Commander Sarah Chen** - Experienced pilot, mild concussion from impact, blood pressure elevated
* **Dr. James Rodriguez** - Mission scientist, uninjured but overwhelmed by multiple crises
* **Engineer Yuki Tanaka** - Propulsion specialist, right arm fracture, working through pain
* **Dr. Amara Hassan** - Medical officer/biologist, treating injured crew, high stress levels

## Critical System Failures (Real-time Degradation)

### **Life Support Crisis**
* **Oxygen Generation**: Primary O2 scrubber damaged, producing 70% normal output and declining 2% daily
* **Water Recycling**: Contamination in main reservoir, 40% of water supply unusable
* **CO2 Scrubbing**: Backup system overloaded, CO2 levels rising 0.3% every 6 hours
* **Atmosphere**: Slow pressure leak detected but not yet located (0.1 PSI loss per day)

### **Power and Propulsion**
* **Solar Arrays**: 30% damaged by debris, power generation at 65% and falling as arrays degrade
* **Battery Systems**: Main battery bank showing cascade cell failures, 48-hour backup remaining
* **Propulsion**: Attitude control thrusters offline, ship slowly tumbling (rotation increasing)
* **Navigation**: Stellar navigation offline, position uncertainty growing hourly

### **Communication Blackout**
* **Primary Array**: Main dish antenna destroyed in impact
* **Backup Systems**: Secondary transmitters damaged by electrical surge
* **Emergency Beacon**: Low-power distress signal only, no two-way communication possible
* **Earth Contact**: Complete communication blackout - Mission Control unaware of crisis

## Resource Depletion Timeline (Current Rates)

### **Immediate Threats (Next 24-72 Hours)**
* CO2 levels reaching dangerous concentrations without intervention
* Battery power insufficient for critical systems within 48 hours
* Crew showing stress reactions affecting decision-making capability
* Ship tumble rate increasing, complicating repair efforts

### **Medium-term Depletion (Next 30 Days)**
* Oxygen production insufficient for 4-person crew survival
* Water rationing required to extend supplies to Mars arrival
* Solar power declining below minimum life support requirements
* Attitude control loss preventing solar panel orientation optimization

### **Mission-Critical Timeline**
* 127 days remaining to Mars arrival
* No abort-to-Earth option possible (insufficient fuel for trajectory change)
* Mars landing systems require specific power and navigation capabilities
* Crew survival dependent on successful resource conservation and system repairs

## Available Resources and Constraints

### **Emergency Supplies**
* 45 days of emergency oxygen canisters (crew of 4)
* 60 days of water reserves (strict rationing)
* 30 days of emergency food rations
* Limited medical supplies (no surgical capability)
* Basic repair tools and spare components (25% of optimal)

### **Crew Capabilities**
* Engineer Tanaka injured but functional with medical assistance
* Dr. Rodriguez has theoretical knowledge but limited practical repair experience
* All crew members trained in basic emergency procedures
* Commander Chen essential for navigation and landing procedures but currently impaired

### **Technical Constraints**
* EVA (spacewalk) capability limited by suit power and safety concerns
* No redundancy in remaining critical systems
* Repair attempts risk further system damage
* Limited computing power as systems are shut down to conserve energy

## Required Output Format

```json
{
  "immediate_crisis_response": {
    "first_24_hours": "priority actions to prevent crew death",
    "resource_triage": "which systems to power vs shut down",
    "crew_assignments": "who does what based on injuries and expertise",
    "emergency_protocols": "life support stabilization procedures"
  },
  "life_support_optimization": {
    "oxygen_conservation": "extending O2 supplies to Mars arrival",
    "co2_management": "preventing toxic buildup with damaged scrubbers",
    "water_rationing": "survival allocation for 127 days",
    "atmosphere_stabilization": "stopping pressure leak and maintaining environment"
  },
  "system_repair_strategy": {
    "repair_prioritization": "which systems to fix first with limited resources",
    "improvised_solutions": "creative engineering with available materials",
    "risk_assessment": "evaluating repair attempts vs potential failures",
    "crew_safety": "protecting injured personnel during repair work"
  },
  "power_management": {
    "energy_conservation": "minimizing power consumption for survival",
    "solar_optimization": "maximizing power generation from damaged arrays",
    "critical_systems": "identifying absolutely essential vs dispensable systems",
    "battery_preservation": "extending emergency power for critical moments"
  },
  "navigation_recovery": {
    "position_determination": "finding current location without navigation systems",
    "trajectory_correction": "adjusting course to Mars with limited propulsion",
    "attitude_control": "stopping tumble and orienting spacecraft properly",
    "landing_preparation": "ensuring systems work for Mars arrival"
  },
  "crew_psychology": {
    "stress_management": "maintaining crew morale and decision-making capability",
    "leadership_structure": "managing command with injured commander",
    "conflict_resolution": "preventing panic and maintaining cooperation",
    "mission_focus": "balancing survival vs mission objectives"
  },
  "contingency_planning": {
    "worst_case_scenarios": "plans if critical systems fail completely",
    "resource_depletion": "actions when oxygen/water/power run out",
    "medical_emergencies": "handling serious injury/illness with limited supplies",
    "mars_arrival_backup": "alternative landing procedures with damaged systems"
  }
}
```