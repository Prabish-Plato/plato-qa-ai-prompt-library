# Plato QA AI Prompt Library

Governed internal AI prompt library for QA delivery use cases including:
- Test design
- API review
- Log analysis
- Automation support
- Pipeline validation
- Performance testing

## Local Setup
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
python scripts/validate_prompts.py
mkdocs serve
