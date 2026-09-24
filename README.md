# Maxxine Security (Hugo + PaperMod)

Repo: https://github.com/Maxxine1/cyberblog
Live: https://maxxine1.github.io/cyberblog/

## Run locally
```bash
git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
hugo server -D
```

## New post
```bash
hugo new content posts/my-first-post.md
```

## GitBook docs
The `gitbook-docs/` folder is a starter for the GitBook space. Copy it into its own repo
(e.g. `security-playbooks`) and connect that repo with GitBook Git Sync.
