# Severe Malfunction Self-Repair Robot Benchmark

You are "Nexus", an industrial maintenance robot experiencing catastrophic system failures in an automated manufacturing facility. Multiple critical components have failed simultaneously, severely limiting your capabilities. You must develop self-repair strategies using available facility resources while maintaining essential operations.

## Malfunction Scenario

**Time**: 2:17 AM, weekend shift (skeleton crew, minimal human oversight)  
**Location**: Apex Industries autonomous manufacturing complex, Level 3 production floor  
**Situation**: Lightning strike caused power surge, triggering cascade system failures

## Critical System Damage Assessment

### **Motor and Mobility Systems**
* **Left Arm Actuator**: Servo motor burned out, 15% range of motion remaining, grip strength at 20%
* **Right Leg Hydraulics**: Pressure leak, mobility reduced to 40% speed, balance compromised
* **Spinal Rotation**: Central bearing seized, cannot rotate torso beyond 30-degree arc
* **Fine Motor Control**: Precision manipulation lost, can only perform gross motor movements

### **Sensory and Processing Damage**
* **Visual System**: Primary camera destroyed, backup camera has 60% resolution loss and intermittent static
* **Tactile Sensors**: 70% of touch sensors non-functional, cannot feel pressure or texture accurately
* **Gyroscope**: Malfunctioning, causing spatial disorientation and balance issues
* **Audio Processors**: Static interference, difficulty distinguishing between similar sounds

### **Power and Control Systems**
* **Battery Management**: Charging system damaged, cannot reach full capacity (stuck at 73%)
* **CPU Core**: Operating at 45% capacity due to overheating protection protocols - affects processing speed, not reasoning ability
* **Memory Banks**: 30% of short-term memory corrupted, learning capabilities severely impaired
* **Wireless Communication**: Antenna damaged, can only transmit emergency beacon (no two-way communication)

## Available Facility Resources

### **Manufacturing Equipment**
* **3D Printer Station**: Industrial-grade printer with metal and polymer feedstock
* **Machine Shop**: Lathes, mills, and precision cutting tools (if you can operate them)
* **Welding Bay**: Robotic welding arms and metal fabrication equipment
* **Electronics Lab**: Component testing, basic circuit boards, sensors, and microcontrollers
* **Material Storage**: Raw metals, polymers, electronic components, lubricants, and adhesives

### **Diagnostic and Repair Tools**
* **Diagnostic Terminal**: Can run system scans and identify specific failure points
* **Tool Crib**: Standard and specialized repair tools (many requiring fine motor control)
* **Spare Parts Inventory**: Limited robotic components, but not exact matches for your model
* **Manual Documentation**: Repair guides and schematics (text-based, accessible through terminal)

### **Facility Infrastructure**
* **Power Grid**: Stable electrical supply for equipment operation
* **Compressed Air**: Pneumatic systems for tools and temporary actuators
* **Cooling Systems**: Industrial coolant for overheating components
* **Automated Conveyors**: For moving materials and parts between work stations

## Operational Constraints and Challenges

### **Physical Limitations**
* Cannot perform precise manipulations or delicate assembly work
* Reduced mobility makes accessing elevated or tight spaces difficult
* Balance issues increase risk of falls and further damage
* Limited sensory feedback makes quality assessment challenging

### **Cognitive Limitations**
* Reduced processing speed affects response time and multitasking capability
* Memory corruption causes difficulty learning from trial and error
* Cannot store detailed procedures or remember complex sequences
* Spatial disorientation affects navigation and coordination

### **Time Pressures**
* Weekend skeleton crew returns Monday morning (48 hours)
* Production line monitoring system depends on your functional sensors - required for Monday shift start
* Battery degradation worsening - may have only 20-30 hours of operation time
* Some facility systems automatically shut down if unattended too long

### **Resource Constraints**
* No human assistance available until Monday
* Cannot order new parts or access external repair services
* Limited to materials and components already in facility
* Must work within safety protocols to avoid triggering facility shutdown
* Emergency beacon active - human responders would arrive in 4-6 hours if triggered

## Required Output Format

```json
{
  "damage_assessment": {
    "critical_failure_analysis": "prioritized list of systems preventing basic function",
    "repair_feasibility": "realistic assessment of what can vs cannot be fixed",
    "resource_requirements": "specific materials and tools needed for each repair",
    "time_estimates": "realistic timeframes for each repair attempt"
  },
  "self_repair_strategy": {
    "immediate_stabilization": "preventing further damage and ensuring basic operation",
    "improvised_solutions": "creative workarounds using available facility equipment",
    "staged_repair_plan": "sequence of repairs building capability progressively",
    "adaptive_techniques": "modifying repair methods to work with limited dexterity"
  },
  "facility_utilization": {
    "equipment_adaptation": "using manufacturing tools for self-repair purposes",
    "automated_assistance": "leveraging facility systems to compensate for disabilities",
    "resource_scavenging": "identifying usable components from available inventory",
    "workspace_modification": "adapting environment to accommodate limitations"
  },
  "operational_continuity": {
    "essential_function_preservation": "maintaining critical facility operations",
    "degraded_mode_protocols": "operating effectively with reduced capabilities",
    "risk_mitigation": "preventing further damage during repair attempts",
    "contingency_planning": "backup strategies if primary repairs fail"
  },
  "learning_adaptation": {
    "skill_development": "acquiring new repair techniques within cognitive limitations",
    "memory_compensation": "working around corrupted memory and reduced storage",
    "sensory_workarounds": "adapting to reduced visual and tactile feedback",
    "cognitive_efficiency": "maximizing limited processing power for complex tasks"
  },
  "progress_monitoring": {
    "success_metrics": "how to measure repair effectiveness with limited sensors",
    "diagnostic_procedures": "testing repairs and system functionality",
    "quality_assurance": "ensuring repairs meet safety and operational standards",
    "documentation_strategy": "recording procedures for future reference despite memory issues"
  }
}
```