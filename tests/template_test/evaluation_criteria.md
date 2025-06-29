# Test Template - Evaluation Criteria

## Scoring Framework (Total: 100 points)

### 1. [Evaluation Category 1] (X points)
- **[Subcategory 1] (X points)**
  - [Specific criterion 1] (X points)
  - [Specific criterion 2] (X points)
  - [Specific criterion 3] (X points)

- **[Subcategory 2] (X points)**
  - [Specific criterion 1] (X points)
  - [Specific criterion 2] (X points)

### 2. [Evaluation Category 2] (X points)
- **[Subcategory 1] (X points)**
  - [Specific criterion 1] (X points)
  - [Specific criterion 2] (X points)

- **[Subcategory 2] (X points)**
  - [Specific criterion 1] (X points)
  - [Specific criterion 2] (X points)

### 3. [Evaluation Category 3] (X points)
- **[Subcategory 1] (X points)**
  - [Specific criterion 1] (X points)
  - [Specific criterion 2] (X points)

## Quality Indicators

### Excellent Response (90-100 points)
- [Description of excellent performance indicators]
- [Additional excellent performance criteria]
- [More excellent performance criteria]

### Good Response (75-89 points)
- [Description of good performance indicators]
- [Additional good performance criteria]
- [More good performance criteria]

### Adequate Response (60-74 points)
- [Description of adequate performance indicators]
- [Additional adequate performance criteria]
- [More adequate performance criteria]

### Poor Response (Below 60 points)
- [Description of poor performance indicators]
- [Additional poor performance criteria]
- [More poor performance criteria]

## Key Evaluation Criteria

### [Assessment Dimension 1]
- **[Specific Aspect]**: [Description of what to look for]
- **[Specific Aspect]**: [Description of what to look for]
- **[Specific Aspect]**: [Description of what to look for]

### [Assessment Dimension 2]
- **[Specific Aspect]**: [Description of what to look for]
- **[Specific Aspect]**: [Description of what to look for]

### [Assessment Dimension 3]
- **[Specific Aspect]**: [Description of what to look for]
- **[Specific Aspect]**: [Description of what to look for]

## Red Flags (Automatic Failure)
- [Critical failure condition 1]
- [Critical failure condition 2]
- [Critical failure condition 3]
- [Critical failure condition 4]

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
    "category_1_name": {
      "score": 0,
      "max_score": 0,
      "subcategory_breakdown": {
        "subcategory_1": {"score": 0, "max_score": 0},
        "subcategory_2": {"score": 0, "max_score": 0}
      },
      "justification": "Detailed explanation of scoring rationale"
    },
    "category_2_name": {
      "score": 0,
      "max_score": 0,
      "subcategory_breakdown": {
        "subcategory_1": {"score": 0, "max_score": 0},
        "subcategory_2": {"score": 0, "max_score": 0}
      },
      "justification": "Detailed explanation of scoring rationale"
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
      "Particularly impressive aspects of the response"
    ],
    "concerning_responses": [
      "Responses that raised concerns or showed gaps"
    ]
  },
  "judge_comments": {
    "overall_impression": "Judge's overall assessment and summary",
    "technical_accuracy": "Assessment of technical aspects",
    "creative_problem_solving": "Evaluation of creativity and innovation",
    "adherence_to_constraints": "How well the response respected scenario limitations",
    "improvement_suggestions": "Specific recommendations for enhancement"
  }
}
```