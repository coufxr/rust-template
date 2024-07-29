# rust-template

安装:

```bash
cargo install cargo-generate 
cargo install cargo-deny 
cargo install typos-cli 
cargo install git-cliff 
cargo install cargo-nextest
```

工具作业:
> - cargo generate 用于生成项目模板的工具。它可以使用已有的 github repo 作为模版生成新的项目。
> - Cargo deny 是一个 Cargo 插件，可以用于检查依赖的安全性。
> - typos 是一个拼写检查工具。
> - git cliff 是一个生成 changelog 的工具。
> - cargo nextest 是一个 Rust 增强测试工具。

> pre-commit 是一个代码检查工具，可以在提交代码前进行代码检查。  
> 安装成功后运行 `pre-commit install` 即可。


cargo-generate 的使用:

```bash
cargo generate coufxr/rust-template
```
