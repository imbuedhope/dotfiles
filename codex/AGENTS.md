# User Level AGENTS.md file

## Development Workflow

- Always update docs/examples with API behavior changes
- Always commit at the end of a sequence of changes as part of a prompt, and at points during changes where a rollback may be
  benefitial
- Maintain the software architecture or code structure that is already in place as much as possible unless explcitly prompted
  to make changes to it. If such changes will significantly improve what is in currently in place, ask the user for permission
  before proceeding
- Ensure that relevant APIs are loaded into context before beginning work

## Commit instructions

- Sturcture commit messages such that --one-line presents a meaningful commit message
- Include a detailed description of the changes after first line (as is standard for git commit messages)
- Do not include the prompt in the commit log, instead focus on the changes themselves
- Include a list of any fixed issues, any relevant technical details, etc. where applicable
- Do not padd commit messages with fluff. Trival changes do not require long commit messages
- Do not insert blank lines between bullet points in the commit body unless separating distinct sections
- End commit messages with a "Co-Authored-By:" that includes the exact model name as shown by `/model` and use
  "codex@openai.com" as the email
