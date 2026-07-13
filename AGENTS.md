# Prometheor organization profile rules

## Git workflow (mandatory)

- Every coding tool with Git write access works directly on `main` only.
- Before editing: run `git switch main` and `git pull --ff-only origin main`.
- Do not create or use personal work, sync, or tool branches such as `kian/work` or `oli/work`.
- After the relevant tests pass, commit the scoped changes and push directly to `origin/main`.
- Repository-specific review, test, and deployment gates remain in force.
- This branch policy does not grant any new write or deployment permissions.
- Automatically generated backup or release refs are not working branches and must never be used for development.


- Keep this repository public and free of secrets, internal paths, or private operational details.
- Present Prometheor as the company and Atlaas as its currently confirmed product.
- Do not list personal agents, memories, services, or private projects as Prometheor products.
- Keep product claims accurate to shipped or explicitly announced capabilities.
- Use English for the public GitHub profile unless the organization adopts a multilingual profile.
