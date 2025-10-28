# X501-Final-Project

A well-structured Flask application with organized architecture following best practices.

## Project Structure

```
/src                    # Source code directory
  /controllers         # Flask routes and blueprints
  /models              # ORM classes or schema definitions
  /views               # HTML/Jinja templates
  /data_access         # Encapsulated CRUD logic

/static                # Static assets (CSS, JS, images)

/tests                 # Test files
  /ai_eval             # Optional AI feature validation tests

/.prompt               # AI-assisted development resources
  dev_notes.md         # Development notes and guidelines
  golden_prompts.md    # Collection of effective AI prompts

/docs                  # Documentation
  /context             # Contextual documentation
    /APA               # Architecture, Patterns, and Approaches
    /DT                # Design and Technical specifications
    /PM                # Product Management documentation
    /shared            # Common resources
      personas.md      # User personas
      glossary.md      # Project terminology
      okrs.md          # Objectives and Key Results
```

## Getting Started

### Prerequisites
- Python 3.8+
- pip (Python package manager)
- Virtual environment (recommended)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/wangwenson/X501-Final-Project.git
   cd X501-Final-Project
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Development

- See `.prompt/dev_notes.md` for development guidelines and conventions
- Refer to `docs/` for comprehensive documentation
- Check `docs/context/shared/glossary.md` for project terminology

## Documentation

Each directory contains a README.md file explaining its purpose and usage:
- `/src/README.md` - Source code organization
- `/docs/README.md` - Documentation structure
- `/tests/README.md` - Testing guidelines
- And more...

## Contributing

1. Follow the coding standards outlined in `.prompt/dev_notes.md`
2. Update documentation when making changes
3. Write tests for new features
4. Use the golden prompts in `.prompt/golden_prompts.md` for AI-assisted development

## License

[Add your license here]

## Contact

[Add contact information here]