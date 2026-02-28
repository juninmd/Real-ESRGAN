```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure consistent, maintainable, and high-quality code for the AGENTS repository. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   All logic, data structures, and utility functions should be encapsulated within reusable components or modules.
*   Avoid duplicating code across multiple files.
*   When a functionality is reused, it should be abstracted and extended, not simply copied.
*   Use functions, classes, and modules to promote modularity and reduce redundancy.

## 2. KISS (Keep It Simple, Stupid)

*   Strive for clear and concise code.
*   Avoid unnecessary complexity.
*   Prioritize readability – code should be easily understood by others (and yourself in the future).
*   Use appropriate data structures and algorithms for the task.
*   Minimize the amount of code required to achieve a specific result.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have a single, well-defined responsibility.
*   **Open/Closed Principle:**  The code should be extensible without modifying the existing implementation.  New functionality should be added through new classes or modules, not by modifying the core code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be required to implement interfaces they do not use.
*   **Dependency Inversion Principle:**  High-level modules should be dependent on low-level modules, and low-level modules should be independent of high-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement functionality that is currently required.  Avoid premature implementation.
*   Focus on delivering value incrementally.  Don’t introduce features that aren’t essential at this stage.
*   Refactor later when appropriate, rather than trying to implement functionality that may not be needed.

## 5. Code Length Limits

*   Each file must be a maximum of 180 lines of code.

## 6. Test Coverage Requirements

*   All development activities must achieve at least 80% test coverage.
*   Unit tests should cover all critical code paths and edge cases.
*   Integration tests should validate interactions between components.
*   End-to-end tests should simulate real-world scenarios.
*   Automated testing should be prioritized.

## 7. File Structure & Organization

*   **Configuration:**  All configuration settings should be managed separately, using a configuration file (e.g., JSON, YAML).
*   **Data:**  Data models (classes or structs) should be clearly defined and documented.
*   **Utilities:**  Helper functions and utilities should be organized into modules.
*   **Error Handling:**  Robust error handling should be implemented with appropriate logging.
*   **Versioning:** Utilize versioning systems (e.g., Git) for all code.

## 8.  Coding Standards & Style

*   Follow PEP 8 style guide for Python (or the language of the AGENTS repository).
*   Use consistent naming conventions.
*   Write clear and concise comments to explain complex logic.
*   Avoid magic numbers and variables.

## 9.  Documentation

*   Document all classes, functions, and modules with clear and concise documentation using docstrings.
*   Provide a README file detailing the purpose of the AGENTS repository and key components.

## 10.  Development Process

*   Code should be reviewed by at least one other developer before merging.
*   Implement unit tests for every significant function/module.
*   Adhere to a consistent branching strategy (e.g., Gitflow).

## 11.  Specific Considerations for AGENTS (Example - adjust as needed)

*   **Agent Management:**  Define clear interfaces for agent creation, configuration, and lifecycle management.
*   **Data Storage:**  Implement a standardized approach to data storage, considering consistency and integrity.
*   **Communication Protocols:**  Document the communication protocols used between agents (e.g., message formats, data exchange).

## 12.  Continuous Improvement

*   Regularly review these guidelines and update them as needed.
*   Encourage collaboration and feedback among team members.
```