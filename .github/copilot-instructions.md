## Security

- Validate input sanitization process
- Search for risk that might expose user data
- Prefer loading configuration and content from the database instead of hard coded content. If absolutely necessary, load it from environment variables or a non-committed config file.

## Code Quality
- follow consistent naming conventions in variables
- Try to reduce code duplication
- Prefer maintainability and readability over optimization.
- If a method is used a lot, try to optimize it for performance.
- Prefer explicit error handling over silent failures.
