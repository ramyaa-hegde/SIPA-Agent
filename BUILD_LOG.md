# Build Log

## Iteration 1

Goal:
Build the smallest working version of SIPA using GitHub repositories as live project inputs.

Completed:

* Created SIPA repository
* Defined system prompt
* Defined sample request
* Selected GitHub repositories as the primary external data source

Deferred:

* Automatic repository scanning
* Multi-project indexing
* Resume file generation
* Portfolio auto-publishing

Reason:
Focused on achieving one complete end-to-end workflow before adding automation features.
## Iteration 2

Goal:
Validate the first working version of SIPA using a real GitHub repository as the project input.

Input:
https://github.com/ramyaa-hegde/flyrank-ml-internship-tasks

Result:
SIPA successfully analyzed the repository and generated a technical project summary, resume bullet points, a portfolio description, a LinkedIn-ready summary, and interview preparation questions.

What worked:

* Repository documentation was sufficient for project understanding.
* Outputs remained consistent with the system prompt.
* The workflow completed end-to-end without manual editing during execution.

What I changed:

* Narrowed the agent scope to one job done well: transforming technical projects into recruiter-ready portfolio assets.
* Used a GitHub repository as the primary live data source instead of local filesystem automation.

What I deferred:

* Automatic GitHub API integration
* Multi-project indexing
* Resume export to PDF
* Portfolio auto-publishing

Reason:
Focused on building a reliable MVP before adding automation features.
