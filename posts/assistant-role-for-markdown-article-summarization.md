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
    "filePath": "=summaries/assistant-role-for-markdown-article-summarization.md",
    "fileContent": "=---\ntitle: Assistant Role for Markdown Article Summarization\nsource_file: posts/2025-05-18-cause-of-brooklyn-bridge-ship-crash-revealed-by-cops-after-two-mexico-navy-sailors-died.md\n---\n\nThe user tasked the assistant with processing Markdown articles by generating a concise 2–3 sentence summary, a short and informative headline, and using the article's frontmatter title if present or the generated headline as a fallback. The assistant's response must be strictly in valid JSON format with the specified keys.",
    "commitMessage": "=Add summary for Assistant Role for Markdown Article Summarization"
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
