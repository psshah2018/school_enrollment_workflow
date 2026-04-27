# School Enrollment Workflow

n8n workflow automation for school enrollment processing.

## Overview

This project contains an n8n workflow for managing the school enrollment process for 2026. The workflow handles registration forms, processes student enrollments, and automates the enrollment pipeline.

## Workflow Details

- **Trigger**: Schedule-based (weekly on Monday at 9 AM)
- **Input**: Registration forms from `C:\Users\parag\Documents\Meadows Working Docs\Welcome Kit 2026\Registration Forms 2026\`
- **Output**: Processed enrollment data

## Setup

1. Install n8n:
   ```bash
   npm install
   ```

2. Import the workflow:
   - Open n8n
   - Go to Workflows → Import from File
   - Select `enrollment_register_2026.json`

3. Configure credentials for any required integrations

## Usage

The workflow runs automatically based on the schedule. To run manually:
- Open n8n
- Find the "Enrollment Register 2026" workflow
- Click "Execute Workflow"

## Project Structure

```
school_enrollment_workflow/
├── enrollment_register_2026.json  # Main workflow file
├── package.json                    # Node.js dependencies
├── .gitignore                      # Git ignore rules
└── README.md                       # This file
```

## Dependencies

- n8n (latest)
- Node.js 18+

## License

Private - For internal use only