# Contributing to GitHub Copilot Chat

## Creating Good Issues
Before opening a new issue, search [open issues](https://github.com/microsoft/vscode/issues) to check for duplicates.  
If it exists, upvote 👍 or comment with new info — avoid “+1” comments.

If you file a new issue, include:
- VS Code + Copilot Chat versions  
- OS and LLM model  
- Repro steps  
- Expected vs actual behavior  
- Screenshots or videos  
- Minimal reproducible code snippet  
- Errors from **Help → Toggle Developer Tools**

Use one issue per bug or feature. Don’t append unrelated problems to existing issues.

---

## Developing

### Requirements
- Node 22.x  
- Python 3.10–3.12  
- Windows users: `Set-ExecutionPolicy Unrestricted`  
- Install: `npm install`, then `npm run get_token`

Run:
```bash
npm run test:unit
npm run test:extension
npm run simulate
