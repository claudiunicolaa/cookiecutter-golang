# cookiecutter-golang

## Generate project
```bash
cookiecutter https://github.com/claudiunicolaa/cookiecutter-golang
```

## Structure

```bash
.
├── .github
│   ├── dependabot.yml
│   └── workflows
│       └── go.yml
└── go.mod


```

## Includes

- dependabot integration `.github/dependabot.yml`
- github actions workflows `.github/workflows/go.yml`
    - lint
    - security (gosec)
    - test
- `go.mod`