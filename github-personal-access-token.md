# Github Personal Access Token (PAT)

A GitHub Personal Access Token (PAT) is a secure way to authenticate and access your GitHub account or repositories programmatically. PATs are used in place of passwords for GitHub API, Git operations, and third-party integrations.

## When to Use a PAT
- Access the GitHub API via scripts or tools
- Use Git on the command line to push/pull to private repos
- Connect CI/CD tools (like GitHub Actions, Jenkins, etc.)
- Integrate third-party services with GitHub

## How to Create a PAT
1. Go to GitHub Settings > Developer settings > Personal access tokens.
2. Click Generate new token.
3. Set a descriptive name and expiration date.
4. Select the desired scopes (permissions).
   - Like - Contents: read and write 
6. Click Generate token and copy the token.
> Note: You won't be able to see the token again. Store it securely.

## Best Practices
- **Use fine-grained tokens:** Choose only the permissions you need.
- **Set an expiration date:** Avoid long-lived tokens.
- **Keep tokens secure:** Never commit tokens to your repositories.
- **Regenerate/revoke if compromised:** If you suspect exposure, revoke and create a new one.

## Using a PAT
```bash
git clone https://github.com/username/repo.git
# When prompted for password, paste your PAT
```
## Documentation
- [GitHub Docs: Managing your personal access tokens](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) 
