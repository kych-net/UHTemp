# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

### Changed

### Deprecated

### Removed

### Fixed

### Security

## [1.1.1] - 2026-10-23

### Added

- README 新增配套项目模板 [UHEg](https://github.com/kych-net/UHEg) 的介绍与链接。

### Changed

- README 与模板脚手架中的 `@preview/underhell` 版本引用更新至 `1.1.1`。
- 待办相关 API 改用中文命名:`TODO` → `待办`、`TODO表格` → `待办表格`,编译参数 `隐藏TODO` → `隐藏待办`。

## [1.1.0] - 2026-10-23

### Added

- `#索引` 函数:列出调用文件所在目录的 `.typ` 文件并生成链接列表。网页模式输出可点击链接,PDF 模式输出文件名列表;构建脚本以 JSON 清单(`--input 索引`)注入目录内容。
- 根目录 `Makefile`:支持开发期间将仓库软链进 Typst 本地包缓存。

### Changed

- 六级标题样式移除前置的多余 `—`。
- 调整包内命名。

### Removed

- 模板脚手架中的 `Makefile`、`web.yml` 与 `web_post.sh`;模板 README 相应精简。

### Fixed

- 发布工作流创建 Release 时幂等,避免 Release 已存在时报错。

## [1.0.0] - 2026-10-07

### Added

- 首个 1.0 版本:UnderHell(地狱之下)Typst 文档模板包,含元素系统、属性框 / 人物框 / 法术、多级标题样式、网页输出与 `typst init` 模板脚手架。

<!--
Below are the target URLs for each version
You can link version numbers (in level-2 headings)
to the corresponding tag on GitHub, or the diff
in comparison to the previous release
-->

[Unreleased]: https://github.com/kych-net/UHTemp/compare/v1.1.1...HEAD
[1.1.1]: https://github.com/kych-net/UHTemp/releases/tag/v1.1.1
[1.1.0]: https://github.com/kych-net/UHTemp/releases/tag/v1.1.0
[1.0.0]: https://github.com/kych-net/UHTemp/releases/tag/v1.0.0