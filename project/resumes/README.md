# CV and Resume Management

This directory contains all CV and resume files for the project. The structure is designed to be flexible to accommodate different LaTeX CV organizations.

## Directory Structure

```
resumes/
├── base/                   # Your main, uncustomized CV
│   └── [your_cv_project]/ # Your complete LaTeX project with its own structure
│
├── versions/              # Customized versions for specific jobs
│   └── [company_role]/   # Each version maintains its original structure
│
└── archive/               # Old or unused versions
    └── [old_version]/    # Archived versions with their original structure
```

## Agent System Capabilities

The AI agent system is designed to:

1. **Analyze LaTeX Structure**
   - Identify main document file
   - Map document structure and dependencies
   - Understand section organization
   - Track file relationships

2. **Content Understanding**
   - Parse LaTeX content
   - Identify key sections (education, experience, skills, etc.)
   - Understand content relationships
   - Track cross-references

3. **Modification Management**
   - Locate relevant sections for changes
   - Understand impact of modifications
   - Maintain document consistency
   - Handle complex LaTeX structures

## Usage Guidelines

### Base CV
- Place your complete LaTeX project in `base/`
- Maintain your original file structure
- The agent will analyze and understand your specific organization

### Customized Versions
- Create new versions in `versions/`
- Each version maintains its original structure
- The agent will track changes across versions

### Archived Versions
- Move old versions to `archive/`
- Original structure is preserved
- Can be used for reference and comparison

## Best Practices

1. **File Organization**
   - Keep your original LaTeX structure
   - Document any special compilation requirements
   - Maintain clear file relationships

2. **Version Control**
   - Use descriptive names for versions
   - Document major structural changes
   - Keep track of compilation requirements

3. **Agent Interaction**
   - Provide clear job descriptions
   - Specify target sections for modification
   - Review agent suggestions carefully 