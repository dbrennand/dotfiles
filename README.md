# Chezmoi Dotfiles

My dotfiles managed via [Chezmoi](https://www.chezmoi.io/).

## Editing .zshrc

```bash
# 1. Edit the file
chezmoi edit ~/.zshrc

# 2. Preview changes
chezmoi diff

# 3. Apply changes
chezmoi -v apply

# 4. Commit changes
chezmoi cd
git add .
git commit -m "Update zshrc"
```
