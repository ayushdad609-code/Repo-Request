# Repo-Request (git-api-client)

**The Postman Killer.**

Offline-first, Git-native API client for executing and testing API requests stored as Markdown files. Use when you need to interact with APIs, document endpoints, or verify contract compliance without using heavy external tools like Postman.

## Key Features
- **Git-Native**: Store API requests in your repository alongside your code.
- **Markdown-Based**: Simple, readable format for defining HTTP requests.
- **Stateless & Fast**: Executes directly from the CLI using Python and Curl.
- **Environment Support**: Substituted variables using `{{VAR_NAME}}` syntax.

## How it works
1. Define a `.md` file with YAML frontmatter for the URL, method, and headers.
2. Put the request body below the frontmatter.
3. Run the execution script.

---
*Developed as part of the "Missing Tools" initiative for Developer Friction 2026.*
