Contributing to Q-Mesh
Thank you for your interest in contributing to Q-Mesh! This document provides guidelines and instructions for contributing to the project.

Code of Conduct
This project adheres to a Code of Conduct that all contributors are expected to follow. By participating, you are expected to uphold this code.

How to Contribute
Reporting Bugs
Use the GitHub issue tracker to report bugs
Describe the bug in detail with steps to reproduce
Include information about your environment (OS, Go version, etc.)
If applicable, provide sample code demonstrating the issue
Suggesting Enhancements
Use the GitHub issue tracker to suggest enhancements
Clearly describe the enhancement and its expected benefits
Provide specific examples of how the enhancement would work
Pull Requests
Fork the repository
Create a new branch for your feature or bugfix
Make your changes
Add or update tests as necessary
Run tests and ensure they pass
Update documentation if needed
Submit a pull request
Development Setup
Install Go 1.20 or higher
Clone your fork of the repository
Install dependencies:
plaintext

Hide
go mod download
Run tests:
plaintext

Hide
go test ./...
Coding Standards
Follow Go best practices and style guidelines
Use gofmt to format your code
Write clear, concise comments
Include tests for new functionality
Maintain backward compatibility unless otherwise discussed
Commit Guidelines
Use clear, descriptive commit messages
Reference issue numbers in commit messages when applicable
Keep commits focused on single changes when possible
Squash multiple commits if they address a single issue
Testing
Add tests for new features
Ensure all tests pass before submitting a pull request
Include both unit and integration tests where appropriate
For QRNG-related functionality, include mock implementations for testing
Documentation
Update README.md with new features or changes to usage
Document new functions, types, and interfaces
Update any relevant examples
Security Considerations
Always consider the security implications of your changes
Discuss potential security issues privately before opening public issues
Be especially careful with cryptographic and entropy-related code
Code Review Process
All submissions require review by project maintainers
Feedback must be addressed before merging
Changes may need to be rebased before merging
Maintainers may request changes or suggest alternatives
Community
Join our [Discord/Slack/etc.] for discussions
Check the issue tracker for tasks labeled "good first issue"
Respect the time and effort of maintainers and other contributors
Thank you for contributing to Q-Mesh!
