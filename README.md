# Professional CV & Job Application Workspace

## Description

This workspace is designed for creating, maintaining, and managing professional CVs, resumes, and job application materials. It includes LaTeX-based CV generation, AI-powered cursor rules for CV writing and job application letters, and comprehensive tracking systems for job applications.

## Features

### 📄 CV Generation
- **LaTeX-based CV**: Professional CV compiled from `main.tex`
- **PDF Output**: High-quality PDF generation with proper formatting
- **ATS-Optimized**: Structured for Applicant Tracking System compatibility
- **Version Control**: Track changes and maintain multiple CV versions

### 🤖 AI-Powered Writing Assistance
- **CV Writer Expert**: World-class HR strategist rules for crafting elite CVs
- **Job Application Letters**: Automated generation of customized, concise application letters
- **Market Research**: Bangladesh job market salary data and guidelines
- **Application Tracking**: Organized tracking system for all job applications


## Structure

```
CV/
├── .cursor/
│   └── rules/                          # AI cursor rules
│       ├── conventional-commits.mdc    # Commit message standards
│       ├── cv-writer-expert.mdc        # CV writing guidelines
│       └── job-application-letter-writer.mdc  # Job application automation
│
├── applications/                       # Job applications tracking
│   └── application.md                  # Application records and tracking
│
├── src/                                # LaTeX CV source files
│   ├── main.tex                        # Main CV document
│   ├── preamble.tex                    # LaTeX preamble and packages
│   ├── header.tex                      # CV header and contact info
│   ├── summary.tex                     # Professional summary section
│   ├── education.tex                   # Education history
│   ├── experience.tex                  # Work experience section
│   ├── projects.tex                    # Projects and achievements
│   ├── technologies.tex                # Technical skills and tools
│   ├── softskills.tex                  # Soft skills section
│   ├── certificate.tex                 # Certifications and training
│   ├── publications.tex                # Publications and research
│   └── information.md                  # CV content notes
│
└── README.md                           # Overview and instructions
```

## Quick Start

### Building CV
```bash
# Compile LaTeX CV
pdflatex src/main.tex
```

### Creating Job Application Letter

Provide job details to the AI:
```
Job Title: Software Engineer
Advertised On: LinkedIn
Company: Tech Corp
Key Requirements: Python, React, teamwork
Experience: 2 years full-stack development
Salary Required: Yes
```

You'll receive:
1. Email subject line
2. Professional application letter
3. Tracking table entry

## Best Practices

1. **Keep CV Updated**: Regularly update with new skills and achievements
2. **Customize Applications**: Tailor each letter to the specific job requirements
3. **Track Applications**: Use the tracking table to manage follow-ups
4. **Version Control**: Commit changes with conventional commit messages
5. **Proofread Everything**: Zero tolerance for errors in professional documents

## Technologies

- **LaTeX**: Professional CV compilation and typesetting
- **Git**: Version control and change tracking
- **AI Cursor Rules**: Intelligent writing assistance and optimization
- **Markdown**: Documentation and note-taking

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

<div align="center">
Made with ❤️ by <a href="https://rajubepary.com" target="_blank">Raju</a>.
</div>

