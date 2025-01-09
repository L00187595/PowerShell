# PowerShell Exercises Repository

This repository contains PowerShell scripts and configurations. It adheres to best practices in PowerShell development and Git/GitHub usage, following the recommended directory structure and coding standards.

## Table of Contents

1. [Overview](#overview)
2. [Repository Structure](#repository-structure)
3. [Topics Covered](#topics-covered)
4. [Setup and Usage](#setup-and-usage)
5. [Understanding and Configuring DSC](#understanding-and-configuring-dsc)
6. [Contributing](#contributing)
7. [License](#license)

---

## Overview

This repository demonstrates my knowledge of PowerShell scripting and Desired State Configuration (DSC). It includes exercises, scripts, and configurations aimed at automating tasks and managing system states effectively.

## Repository Structure

The repository follows the recommended structure for PowerShell projects:

```
Powershell/
├── scripts/            # Directory containing PowerShell scripts
├── DSC/                # DSC configurations and resources
├── docs/               # Documentation and additional notes
├── tests/              # Unit tests for PowerShell scripts
├── .gitignore          # Git ignore file
├── README.md           # This file
└── LICENSE             # License for the project
```

### Key Files and Directories

- `scripts/`: Contains PowerShell scripts categorized by functionality or topic.
- `DSC/`: Includes configurations and resources for Desired State Configuration.
- `docs/`: Supplementary information, such as detailed instructions or explanations.
- `tests/`: Unit tests to ensure the correctness of scripts and configurations.
- `.gitignore`: Specifies files and directories to exclude from version control.

## Topics Covered

- **Basic PowerShell Scripting**: Variables, loops, conditionals, and functions.
- **Advanced Scripting**: Error handling, modules, and custom cmdlets.
- **System Administration**: Automating administrative tasks and managing resources.
- **Desired State Configuration (DSC)**: Writing, testing, and applying configurations.
- **Testing**: Writing and executing unit tests for scripts and DSC configurations.

## Setup and Usage

1. Clone the repository:
   ```powershell
   git clone https://github.com/yourusername/Powershell.git
   ```
2. Navigate to the repository:
   ```powershell
   cd Powershell
   ```
3. Execute a script:
   ```powershell
   .\scripts\example_script.ps1
   ```
4. Apply a DSC configuration:
   ```powershell
   Start-DscConfiguration -Path .\DSC\ExampleConfig -Verbose
   ```
5. Run tests:
   ```powershell
   Invoke-Pester -Script .\tests\example_test.ps1
   ```

## Understanding and Configuring DSC

Desired State Configuration (DSC) is a PowerShell feature used for declarative configuration management. Below is an example of a simple DSC configuration:

# Generate and apply the configuration
ExampleConfig
Start-DscConfiguration -Path .\ExampleConfig -Wait -Verbose
```
This example ensures the presence of a file with specified contents on the target node.

## Contributing

JOR

## License

GNU V3
