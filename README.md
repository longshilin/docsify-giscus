# docsify-giscus-new
docsify giscus plugin，集成giscus评论插件！

[![npm](https://img.shields.io/npm/v/docsify-plugin-toc.svg?style=flat-square)](https://www.npmjs.com/package/docsify-giscus)

![示例](demo.png)


## Usage
1. [Applay giscus](https://giscus.app/zh-CN) ，申请 giscus

2. Configure docsify-giscus:(配置值详情请参考 https://giscus.app/zh-CN ）

    ```html
    <script>
    window.$docsify = {
      giscus:{
        repo: "longshilin/w",
        repoId: "R_kgDOwvLA",
        categoryId: "DIC_kwDOKAwv4CYMOU",
        mapping: "pathname",
        strict: "0",
        reactionsEnabled: "1",
        emitMetadata: "1",
        inputPosition: "top",
        theme: "preferred_color_scheme",
        lang: "zh-CN",
        loading: "lazy",
      },
    }
    </script>
    ```

3. Insert script into docsify document:

    ```html
    <!-- giscus评论  -->
    <link rel="stylesheet" href="https://unpkg.com/docsify-giscus-new@1.1.0/dist/giscus.css">
    <script src="https://unpkg.com/docsify-giscus-new@1.1.0/dist/docsify-giscus.min.js"></script>
    ```
