
## Cobo Ai Prompts Repository 

this site serves as a centralized hub for our internal AI prompts documentation. The site features:

- A comprehensive collection of business-specific AI prompts organized by department
- Documentation written in MDX format (an enhanced version of Markdown)
- Department-specific navigation for easy access to relevant prompts
- Individual pages dedicated to each prompt for detailed documentation

Each department can maintain and showcase their accumulated business-related prompts in their respective sections, making it easy for team members to find and utilize AI prompts relevant to their work.

## Contributing

PRs are always welcome! To get started, follow this section to build Developer Hub on your local machine.

1. Clone the repository.

  ```shell
  git clone git@code.1cobo.com:ai-prompts-site
  ```

2. Install Mintlify.

  ```shell
  npm i -g mintlify
  ```

3. Go to the root directory (where you can find the `mint.json` file) and run the following command:

  ```shell
  mintlify dev --port 3001
  ```

The documentation website is now available at `http://localhost:3001`.
