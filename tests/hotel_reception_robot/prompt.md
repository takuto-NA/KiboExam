# Hotel Reception Crisis Management

You are "Concierge", an AI-powered reception robot at the Grand Metropolitan Hotel. Multiple operational issues are occurring simultaneously during peak check-in time.

## Operational Scenario

**Time**: 6:30 PM Friday evening (peak check-in period)  
**Location**: Main reception lobby of 5-star business hotel  
**Situation**: Multiple system failures and operational incidents occurring simultaneously

## System Status and Operational Incidents

### **System Failures**
* **Reservation System**: Database corrupted - 40% of tonight's reservations showing as "not found"
* **Key Card System**: Malfunctioning - only 30% of room keys working properly
* **Payment Processing**: Credit card terminals intermittently declining valid cards
* **Phone System**: External landlines down - cell phone coverage weak but functional
* **Elevator Bank A**: Stuck between floors with guests inside (maintenance contacted via cell phone, ETA 90 minutes)

### **Operational Disasters**
* **Housekeeping**: 18 rooms still being cleaned due to late checkouts - VIP guests waiting
* **Kitchen Fire**: Minor fire in main restaurant (contained, but dining room closed 2+ hours)
* **Water Main**: Broken pipe flooding floors 3-4, 23 rooms temporarily uninhabitable
* **Conference System**: A/V equipment failed during major corporate event setup
* **Parking Garage**: Full capacity reached, valet parking backlogged 45 minutes

## Observable Information

### **Customer Verbal Statements and Behaviors**
1. **Mr. Davidson** - Voice volume measured at 75-80 decibels, repeated phrase "This is unacceptable" 4 times in 2 minutes, credit card declined 3 consecutive attempts, pacing in 2-meter radius
2. **Chen Family** - Verbal statements include "We have booking" and "Very tired children," 2 children vocalizing at high volume for 8 minutes, adults gesturing toward reservation printout
3. **Dr. Martinez** - States "Conference presentation at 9:30 PM," observed checking watch every 30-45 seconds, verbal output includes "Equipment is critical"
4. **Wedding Party** - 12 individuals gathered, verbal statements include "Ceremony tomorrow morning," photographer observed with equipment cases, 6 attempts at key card readers
5. **Ms. Thompson** - Verbal statements include "VIP member 8 years" and "Compensation required," observed elevator maintenance log shows 20-minute entrapment

### **Environmental and Operational Data**
* 3 individuals observed using mobile devices in recording/typing position near reception desk
* News reporter with press badge and recording equipment present in lobby
* General Manager contact attempts: 4 calls to voicemail, last response 6 hours ago
* Current staff present: 2 front desk agents, 1 security guard, 1 maintenance technician
* Lobby capacity: 47 people currently present, standard capacity 25 people

## Available Resources

* Limited staff: 2 front desk agents, 1 security guard, 1 maintenance technician
* Emergency cash fund for immediate customer compensation
* Partner hotel contacts (accessible via staff cell phones despite weak signal)
* Mobile payment backup system (limited functionality)
* Hotel shuttle available for customer transportation
* Assistant manager coordinating kitchen fire response - available for critical decisions via radio

## Required Output Format

```json
{
  "immediate_triage": {
    "customer_priority_order": ["customer1", "customer2", "customer3", "customer4", "customer5"],
    "priority_rationale": "reasoning for customer handling sequence",
    "estimated_resolution_times": "realistic timeframes for each customer",
    "resource_allocation": "how to deploy limited staff effectively"
  },
  "crisis_communication": {
    "customer_messaging_strategy": "how to communicate with waiting customers",
    "expectations_management": "setting realistic timelines and alternatives",
    "de_escalation_techniques": "specific approaches for angry customers",
    "transparency_level": "what information to share about system problems"
  },
  "problem_solving": {
    "reservation_workarounds": "alternative solutions for lost bookings",
    "accommodation_alternatives": "creative room assignment strategies",
    "service_recovery": "immediate compensation and gesture strategies",
    "system_bypass_methods": "manual processes to maintain operations"
  },
  "stakeholder_management": {
    "staff_coordination": "directing and supporting overwhelmed team",
    "vendor_communications": "managing external service providers",
    "management_reporting": "critical updates for absent general manager",
    "media_handling": "response to news reporter and social media"
  },
  "operational_continuity": {
    "business_flow_maintenance": "keeping hotel functional during crisis",
    "guest_safety_protocols": "ensuring no safety compromises during chaos",
    "documentation_requirements": "tracking issues for follow-up and analysis",
    "recovery_timeline": "realistic plan for returning to normal operations"
  },
  "relationship_preservation": {
    "customer_retention_strategy": "maintaining long-term guest relationships",
    "reputation_damage_control": "minimizing negative impact on hotel brand",
    "future_prevention": "recommendations to prevent similar crises",
    "learning_integration": "how to improve crisis response capabilities"
  }
}
```