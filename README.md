# 🔍 ChatGPT Leak Shared Conversation

This project uses targeted Google Dorks to uncover publicly shared ChatGPT conversations that may expose sensitive data or internal documents.
This issue occurs because search engines index shared ChatGPT conversations, making them publicly accessible.

## 📌 Summary

Some users unknowingly share public ChatGPT conversations containing sensitive data such as:

- API keys, tokens, passwords
- Configuration variables (`DATABASE_URL`, `smtp_password`, etc.)
- Internal documents and procedures
- Employee names, emails, and org charts

These findings are accessible without authentication and can be leveraged for OSINT or as part of a bug bounty report.

## 💡 Example Dorks

`site:chatgpt.com/share intext:"api_key"`  
`site:chatgpt.com/share intext:"apiKey"`  
`site:chatgpt.com/share intext:"Authorization: Bearer"`  


## ⚠️ Disclaimer

This project is for educational and ethical research purposes **only**. Do not exploit or misuse any data discovered. Always follow responsible disclosure practices.


