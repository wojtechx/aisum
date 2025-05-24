{
  "parameters": {
    "resource": "file",
    "operation": "create",
    "owner": {
      "__rl": true,
      "value": "wojtechx",
      "mode": "list"
    },
    "repository": {
      "__rl": true,
      "value": "aisum",
      "mode": "list"
    },
    "filePath": "=summaries/your-request-is-missing-the-article-content.md",
    "fileContent": "=---\ntitle: Your request is missing the article content\nsource_file: posts/2025-05-18-gary-lineker-quits-bbc-over-controversial-anti-semitic-post-and-will-miss-2026-world-cup-coverage.md\n---\n\nPlease provide the Markdown article content so I can generate the requested summary and headline.",
    "commitMessage": "=Add summary for Your request is missing the article content"
  },
  "name": "GeneratorMDGH",
  "type": "n8n-nodes-base.github",
  "typeVersion": 1.1,
  "position": [1900, 20],
  "credentials": {
    "githubApi": {
      "id": "your_github_credentials_id",
      "name": "GitHub account 3"
    }
  }
}
