# CSL Validator

[![Website](https://img.shields.io/website?url=https%3A%2F%2Ftypst-doc-cn.github.io%2Fcsl-validator%2F)](https://typst-doc-cn.github.io/csl-validator/)

This is a fork of the [official CSL validator](https://validator.citationstyles.org/).

Major [changes](https://github.com/typst-doc-cn/csl-validator/compare/upstream-gh-pages...main):

- Bootstrap CDN is replaced with [jsDelivr](https://www.jsdelivr.com) to make the website load faster.

- [CSL-M extensions](https://citeproc-js.readthedocs.io/en/latest/csl-m/) and [Zotero Chinese Community’s schema](https://github.com/zotero-chinese/csl-m-schema-rng) are added to facilitate debugging styles beyond the [CSL specification](https://docs.citationstyles.org/en/stable/specification.html).

> [!NOTE]
>
> Zotero Chinese Community’s schema might still be helpful even if you are not doing anything related to Chinese.
>
> Their schema is more like an up-to-date description of [citeproc-js](https://citeproc-js.readthedocs.io/) (the engine used by [Zotero](https://www.zotero.org/)). It contains a few undocumented features of citeproc-js. For example, the [term `citation-range-delimiter`](https://github.com/zotero-chinese/styles/discussions/439) and [arbitrary extra fields in `notes`](https://github.com/zotero-chinese/styles/discussions/598#discussioncomment-15125308).

## Relevant links

- [中文 CSL 样式 (Chinese CSL styles) | Zotero 中文社区](https://zotero-chinese.com/styles/)
- [Bibliography Function | Typst Documentation](https://typst.app/docs/reference/model/bibliography/)
- [可用于 Hayagriva 的 CSL 样式——CSL sanitizer for Hayagriva | Typst 中文社区](https://typst-doc-cn.github.io/csl-sanitizer/)

## License

The CSL Validator is released under the MIT license.
