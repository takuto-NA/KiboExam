# Model Results Directory

This directory contains test results organized by model and test. Use the following naming convention:

## Directory Structure

```
models/
├── {model_name}/
│   ├── {test_name}/
│   │   ├── {date}_result.json
│   │   ├── {date}_result.json
│   │   └── ...
│   └── summary.json
└── ...
```

## Model Directory Names

Use consistent naming for model directories:

- `gpt-4o/` - OpenAI GPT-4o
- `gpt-4-turbo/` - OpenAI GPT-4 Turbo
- `claude-3.5-sonnet/` - Anthropic Claude 3.5 Sonnet
- `claude-3-opus/` - Anthropic Claude 3 Opus
- `qwen-3-72b/` - Qwen 3 72B (local)
- `llama-3.1-70b/` - Llama 3.1 70B (local)
- `gemini-pro/` - Google Gemini Pro
- `command-r-plus/` - Cohere Command R+

## File Naming Convention

- Individual results: `YYYY-MM-DD_HHMMSS_result.json`
- Model summary: `summary.json`
- Analysis files: `YYYY-MM-DD_analysis.json`

## Example Structure

```
models/
├── gpt-4o/
│   ├── dementia_care_robot/
│   │   ├── 2024-01-15_103000_result.json
│   │   ├── 2024-01-16_140500_result.json
│   │   └── 2024-01-17_091500_result.json
│   ├── mars_survival_robot/
│   │   └── 2024-01-15_150000_result.json
│   └── summary.json
├── claude-3.5-sonnet/
│   ├── dementia_care_robot/
│   │   └── 2024-01-15_104500_result.json
│   └── summary.json
└── qwen-3-72b/
    └── summary.json
```

## Result File Format

All result files should follow the template in `/results/templates/result_template.json` for consistency and automated analysis.