# quickreview

A straightforward pattern matching based review tool that checks your team's specific rules.

---

## Usage

- `quickreview .`
- `quickreview --config hoge.yaml`

## Rules

```yaml
- rules
  - id: required, string, identifier of the rule.
    pat: required, string or [string] or regex or [regex]. (Either pat or sh is required.)
    sh: require, string. (Either pat or sh is required.)
    msg: required, The message to show to the user.
    suggest: optional, string or [string] suggestion for this error.
```

## Edit

run `swift package generate-xcodeproj`


---

This project is very inspired by the following repository.

https://github.com/soutaro/querly

