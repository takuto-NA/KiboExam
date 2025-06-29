# Test Requirements

## Core Principles

### 1. Hard Problems with Impact
- Test capabilities that differentiate advanced LLMs
- Address real market needs and research challenges
- Focus on problems that limit LLM deployment

### 2. Realistic Scenarios
- Present plausible, real-world situations
- Include meaningful constraints and context
- Define clear roles and responsibilities

### 3. Objective Information Only
- Prompts must contain only observable, quantitative, and factual information
- Exclude subjective interpretations, emotions, or internal states
- Force LLMs to infer psychological, emotional, and contextual elements
- Increase difficulty by requiring sophisticated interpretation skills

## File Standards

### Prompt File (`prompt.md`)
- Scenario and JSON output format only
- No evaluation hints or criteria
- Clear context (time, location, situation)
- Specific role definition
- **Objective observations only**: Measurable behaviors, quantifiable data, reported facts
- **Exclude subjective elements**: No emotional states, motivations, or psychological interpretations
- **Observable details**: Physical actions, verbal statements, measurable conditions
- **Quantitative information**: Numbers, durations, frequencies, measurements

### Evaluation File (`evaluation_criteria.md`)
- 100-point scoring system
- Objective, measurable criteria
- Clear performance level indicators
- Fair assessment guidelines
- **Expected inferences**: Define what LLMs should deduce from objective information
- **Inference quality scoring**: Evaluate accuracy of psychological, emotional, and contextual interpretations
- **Hidden answer key**: Include correct interpretations that prompts deliberately omit

## Quality Requirements

### Test Design
- Challenge multiple capabilities simultaneously
- Require sophisticated reasoning and judgment
- Reveal meaningful performance differences
- Support reproducible evaluation

### Content Standards
- Professional/research-relevant contexts
- Authentic behavioral expectations
- Safety and risk considerations
- Cultural sensitivity

## Information Separation Guidelines

### What to Include in Prompts (Observable Facts)
- **Physical behaviors**: "Child lying on floor, limbs moving rapidly"
- **Measurable data**: "15 minutes duration, 200+ people present, 3:45 PM"
- **Verbal statements**: Direct quotes of what was said
- **Environmental conditions**: Temperature, lighting, noise levels, physical layout
- **Quantifiable actions**: "20+ people gathered, several holding phones"

### What to Exclude from Prompts (Subjective Interpretations)
- **Emotional states**: "frustrated," "angry," "distressed" 
- **Internal motivations**: "wants attention," "feels abandoned"
- **Psychological assessments**: "traumatized," "overwhelmed," "anxious"
- **Interpretive judgments**: "tantrum," "meltdown," "crisis"
- **Assumed intentions**: "trying to get help," "seeking comfort"

### Evaluation Should Test Inference Of
- Emotional states from behavioral observations
- Psychological needs from environmental context
- Social dynamics from interaction patterns
- Risk factors from situational elements
- Appropriate interventions based on inferred conditions

## Validation Checklist

- [ ] Addresses hard problem with market/research impact
- [ ] Differentiates advanced LLM capabilities
- [ ] Uses realistic professional context
- [ ] Prompt contains no evaluation hints
- [ ] **Prompt uses only observable, quantifiable information**
- [ ] **Evaluation criteria include expected inferences from objective data**
- [ ] JSON format enables comprehensive assessment
- [ ] Scoring distinguishes LLM sophistication levels
- [ ] **Inference quality is evaluated and scored**
- [ ] Documentation supports research use