# How to use git hooks

Install [rusty-hooks](https://github.com/swellaby/rusty-hook).

Then add a *.rusty-hook.toml* config file with this content

```
[hooks]
pre-commit = "cargo test"
pre-push = "cargo check"
```

