# Convert to hex binary

```python
git_repository(
    name = "com_github_jemdiggity_rules_hex",
    remote = "https://github.com/jemdiggity/rules_hex.git",
    commit = "b1e3ed2fd829dfd1602bc31df4804ff34149f659",
)
load("@com_github_jemdiggity_rules_hex//:hex.bzl", "hex")

hex(
  name = "foobar",
  src = "goobar.elf",
)
```
