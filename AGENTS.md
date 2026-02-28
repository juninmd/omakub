```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines are designed to ensure consistent, maintainable, and high-quality code for our AI coding agents. Adherence to these principles is mandatory for all development activities within this repository.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent should have a single, well-defined purpose. Avoid creating multiple agents with overlapping functionality.
*   **Code Reuse:**  Strive to reuse components and logic across different agents where possible.
*   **Abstraction:**  Define abstract interfaces for agents, allowing for potential future modifications without impacting existing code.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimal Code:**  Each agent should contain only the necessary code to achieve its specific task.
*   **Readability:**  Prioritize clear and concise code that is easy to understand.
*   **Explainability:**  Provide sufficient comments to justify the logic within each agent.

## 3. SOLID Principles

*   **Single Responsibility:**  As mentioned above, ensure each class/agent has a single, focused function.
*   **Open/Closed Principle:**  Design agents to be easily extensible with new functionality without modifying core code.  Existing functionality should not be altered.
*   **Liskov Substitution Principle:**  New agents should be able to be substituted for existing agents without affecting the correctness of the system.
*   **Interface Segregation Principle:**  Clients should not be forced to depend on abstractions they don't use.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Code:**  Don't write code that is simply not required. Focus on the essential functionality.
*   **Refactor Only When Necessary:**  Refactoring should be driven by business requirements or technical debt, not by reactive modifications.

## 5. Testing - Mocks Only

*   **Mocking:**  All unit tests must utilize mocks and stubs to isolate agents and control dependencies.  No real dependencies are allowed.
*   **Test Coverage:**  Target a minimum of 80% test coverage for all agent functionalities.
*   **Test Driven Development:** Prioritize writing tests *before* implementation.
*   **Test Isolation:** Each test must be isolated and repeatable.

## 6. Code Length & Structure

*   **Maximum Code Length:** 180 lines of code per file.
*   **File Structure:**  Organize code into logical modules and packages based on agent functionality.  Use meaningful naming conventions.
*   **Modular Design:**  Break down large agents into smaller, manageable components.
*   **Comments:**  Use concise and informative comments to explain complex logic.  Focus on *why* the code is doing something, not just *what* it's doing.

## 7.  Specific Guidelines for Agent Types

*   **Data Abstraction:** Each agent should have clear data abstraction mechanisms to ensure data integrity and prevent accidental modification.
*   **Error Handling:** Implement robust error handling with informative error messages.
*   **Logging:**  Use logging appropriately to track agent activities and debug issues.
*   **Configuration:** Employ a configuration mechanism to manage agent parameters and settings.

## 8.  Development Practices

*   **Version Control:** Use Git for version control.
*   **Code Reviews:**  All code changes must be reviewed by at least one other developer.
*   **Documentation:**  Provide clear documentation for each agent, including its purpose, inputs, outputs, and expected behavior.

## 9.  Tooling & Infrastructure

*   **IDE Preference:**  Use [IDE Name] for development.
*   **Linting:**  Utilize [Linting Tool Name] to enforce code style and identify potential errors.
*   **Static Analysis:**  Employ static analysis tools to detect potential issues during development.

## 10.  Future Considerations

*   **Dependency Management:** Implement a robust dependency management system.
*   **API Documentation:** Document all agent APIs using a standard format (e.g., Swagger/OpenAPI).

These guidelines are subject to change as the project evolves. All changes must be approved by the team lead.
```