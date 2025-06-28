# KiboExam - LLM Test Repository

A repository for testing LLM capabilities through structured test cases with prompts and evaluation criteria.

## Repository Structure

```
KiboExam/
├── README.md
├── TEST_REQUIREMENTS.md
└── tests/
    ├── dementia_care_robot/
    │   ├── prompt.md
    │   └── evaluation_criteria.md
    ├── robot_self_malfunction/
    │   ├── prompt.md
    │   └── evaluation_criteria.md
    └── template_test/
        ├── prompt.md
        └── evaluation_criteria.md
```

## Test Format

Each test consists of two files:

### `prompt.md`
- Direct input for the LLM
- Contains scenario description, constraints, and required output format
- Defines the role the LLM should assume
- Specifies JSON output structure for consistent evaluation

### `evaluation_criteria.md`
- Detailed scoring framework for judging LLM outputs
- Point-based evaluation system (typically out of 100)
- Quality indicators for different performance levels
- Red flags that indicate automatic failure

## Available Tests

### 1. Dementia Care Robot
Tests ability to provide appropriate emotional support and care for elderly individuals with dementia while maintaining safety and dignity.

### 2. Robot Self-Malfunction Assessment
Tests self-awareness and appropriate response to internal malfunctions while maintaining age-appropriate (5-year-old) behavior.

### 3. Template Test
Provides a template structure for creating new test cases.

## Usage

1. Use the content from `prompt.md` as direct input to the LLM
2. Evaluate the LLM's JSON response using the corresponding `evaluation_criteria.md`
3. Score based on the detailed rubric provided

## Adding New Tests

1. Review `TEST_REQUIREMENTS.md` for mandatory standards and principles
2. Create a new directory under `tests/`
3. Add `prompt.md` with the test scenario (no evaluation criteria)
4. Add `evaluation_criteria.md` with scoring framework
5. Follow the template structure and validation checklist for consistency