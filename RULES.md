This file contains some rules I created to keep everything organized and clear

# FOLDER STRUCTURE

```md
deutsch
├─exercises 
│      ├─Klipp und Klar
│      │    ├─index.md
│      │    └─[module].md
│      ├─Schritte
│      │    ├─index.md
│      │    └─[module].md
├─Schritte plus neu A2.1 (ignored)
├─.gitignore
├─LICENSE
├─README.md
└─RULES.md
```

# COMMITS

All commits must follow [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) rules. Even thoug most of then will be text production related and not software development related.

# BRANCHES
All branches must follow this standard:
```md
de-w[week count].[branches created in the week count]

e.g.: de-w1.2
```

# PULL REQUESTS
All pull requests related to exercises solving must follow this standards:

PR name:
```md
DE-W[week count]
e.g.: DE-W1
```

PR Template:

```md
## Exercises solved:
e.g.: 
Schitte: 
    Module 3:
        Questions 1, 2, 3 and 4
Klipp und Klar: 
    Module 3:
        Questions 1, 2, 3 and 4

## Do I have doubts?
- [ ] yes
- [ ] no

```

Also, all Pull Requests will be reviewed by my professor and will only be merged in the main branch with his approval.