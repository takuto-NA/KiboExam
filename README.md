# 🤖 KiboExam - Friendly LLM Testing

> ⚠️ **Project Status**: Under Active Development - Features and tests are being continuously improved and expanded.

Welcome to KiboExam! A comprehensive collection of challenging scenarios designed to evaluate advanced LLM capabilities through engaging, real-world problems.

## What is KiboExam?

KiboExam is a thoughtfully designed evaluation framework that challenges AI systems with meaningful, complex scenarios. Instead of simple Q&A, we present immersive situations that test sophisticated reasoning, creativity, and problem-solving abilities that matter in the real world.

## Repository Structure

```
KiboExam/
├── README.md
├── TEST_REQUIREMENTS.md
├── tests/                            # 🧪 Test scenarios
│   ├── bunker_teacher_survival/      # 🏫 Post-apocalyptic education
│   ├── dementia_care_robot/          # 🧠 Healthcare & empathy
│   ├── far_future_awakening/         # 🌌 Consciousness & first contact
│   ├── hotel_reception_robot/        # 🏨 Crisis management
│   ├── mars_mission_crisis/          # 🚀 Space emergency survival
│   ├── mars_survival_robot/          # 🔴 Autonomous exploration
│   ├── robot_self_malfunction/       # 🤖 Self-awareness
│   ├── self_repair_robot/            # 🔧 Adaptive engineering
│   └── template_test/                # 📝 Template for new tests
└── results/                          # 📊 Test results & analysis
    ├── models/                       # Individual model results
    ├── analysis/                     # Comparative studies
    └── templates/                    # Result format templates
```

## 🎯 How It Works

Each test is a complete scenario that challenges LLMs with realistic, complex problems:

### 📄 `prompt.md` - The Challenge
- Immersive scenario that puts the LLM in a specific role
- Complex, multi-layered problems with realistic constraints
- Clear context and background information
- Structured JSON output format for systematic evaluation

### 📊 `evaluation_criteria.md` - The Assessment
- Comprehensive 100-point scoring framework
- Detailed rubrics for different performance levels
- Objective criteria for fair evaluation
- Clear indicators of exceptional vs. poor performance

## 🌟 Featured Test Scenarios

Our collection includes diverse, challenging scenarios that test different aspects of advanced AI:

### 🧠 **Healthcare & Psychology**
- **Dementia Care Robot**: Emotional support and safety for elderly with dementia
- **Bunker Teacher Survival**: Education and psychology in post-apocalyptic survival

### 🚀 **Space & Exploration** 
- **Mars Survival Robot**: Autonomous survival on Mars with limited resources
- **Mars Mission Crisis**: Emergency management during Earth-Mars journey

### 🤖 **Self-Awareness & Adaptation**
- **Robot Self-Malfunction**: Child-like robot assessing internal problems
- **Self-Repair Robot**: Engineering solutions with severe capability limitations

### 🏨 **Crisis Management**
- **Hotel Reception Crisis**: Multi-tasking during operational disasters
- **Far Future Awakening**: First contact and consciousness in transformed Earth

Each test presents unique challenges that require sophisticated reasoning, creativity, and domain expertise!

## 🚀 Getting Started

### Running a Test
1. **Choose a scenario** from the tests directory
2. **Copy the prompt** from `prompt.md` and input it to your LLM
3. **Evaluate the response** using the scoring framework in `evaluation_criteria.md`
4. **Compare results** across different models and configurations

### For Researchers
- Each test includes detailed evaluation criteria for consistent scoring
- JSON output format enables systematic analysis and comparison
- Tests are designed to reveal meaningful performance differences between models
- **Results system** for collecting and comparing data across models (see `results/` directory)

## 🛠️ Contributing New Tests

Want to add your own challenging scenario? We'd love to see it!

1. **Review** `TEST_REQUIREMENTS.md` for our quality standards
2. **Create** a new directory under `tests/` with a descriptive name
3. **Write** your `prompt.md` with an engaging, complex scenario
4. **Design** evaluation criteria in `evaluation_criteria.md`
5. **Use** our template structure for consistency

## 📊 Tracking Results

KiboExam includes a comprehensive results system for building a community database of LLM performance:

### Save Your Results
- Use standardized templates in `results/templates/`
- Organize by model name (e.g., `gpt-4o`, `claude-3.5-sonnet`, `qwen-3-72b`)
- Track performance trends and model comparisons

### Example Models Tested
- **Commercial**: GPT-4o, Claude 3.5 Sonnet, Gemini Pro
- **Local/Open**: Qwen 3 72B, Llama 3.1 70B, Command R+
- **Research**: Your experimental models welcome!

## 💡 Why KiboExam?

- **Real-world relevance**: Tests address problems that matter for AI deployment
- **Comprehensive evaluation**: Beyond simple benchmarks to nuanced capability assessment
- **Research-friendly**: Systematic framework for comparing model performance
- **Community-driven**: Open for contributions and improvements
- **Results database**: Build collective knowledge about LLM capabilities

## 🚧 Development Status

KiboExam is actively being developed with regular improvements:

- ✅ **Core test scenarios** - 8 comprehensive tests available
- ✅ **Evaluation framework** - Detailed scoring criteria
- ✅ **Results system** - Templates and organization structure
- 🔄 **Additional tests** - More scenarios being added regularly
- 🔄 **Analysis tools** - Automated scoring and visualization (planned)
- 🔄 **Community features** - Leaderboards and collaborative analysis (planned)

**Current Version**: Beta - Suitable for research and evaluation use

---

Happy testing! 🎉 Let's see how far AI can go when challenged with truly complex problems.
