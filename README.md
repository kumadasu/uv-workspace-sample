# Sample mono-repo project using uv workspace

This repository is a sample project to explain, how to create mono-repo using uv workspace for providing multiple small tools.

Explanation is available at blog post [uvでworkspacesを使用するときはuv syncに--all-packagesをつける](https://kumadasu.com/2025/08/09/use-all-packages-for-uv-workspace).

Key point is "When you create multiple packages with dependencies you need to add `--all-packages` option for `uv sync`." as following.

```shell
uv sync --all-packages
```
