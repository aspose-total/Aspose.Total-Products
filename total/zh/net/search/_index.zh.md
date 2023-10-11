---
title: 通过 C# .NET 搜索文档 

description: 通过 .NET 应用程序搜索文档，包括 PDF、Microsoft Office Excel、Word、PowerPoint 等。 通过应用程序在线搜索文档。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 .NET API 搜索文档" h2="使用 Aspose.Total for .NET 以高效的方式轻松地从各种文档（包括 Microsoft Office Word、Excel、PowerPoint 和 PDF 文件）中搜索和获取数据。" >}}

{{% blocks/products/pf/feature-page-summary %}}

为不同的文档文件格式启用文本搜索和内容索引使用户能够优化生产力、简化数据检索并增强跨组织和应用程序的信息管理。 通过在文档中启用基于文本的搜索并建立索引以从各种文档文件格式中高效检索信息，增强基于 .NET 的软件或系统的功能。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="在文档中搜索的主要原因" %}}

1. 文件组织
1. 信息检索
1. 内容验证 
1. 内容总结 
1. 文本分析
1. 数据提取 
1. 文档索引 


{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="搜索 PDF 文档" %}}

我们使用 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，它是 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 的子 API，专为特定文档操作功能以及与检索和搜索文档内容相关的任务而设计。 下面的代码片段是用 C# 编写的，用于与 PDF 文档交互。 它首先设置正则表达式模式来搜索文档中的非空白字符序列。 接下来，它访问 PDF 的第一页，并使用 TextFragmentAbsorber 使用指定的正则表达式搜索该页面上的文本。 然后，代码将发现的文本片段收集到一个集合中。 最后，它迭代该集合并将每个识别的文本片段输出到控制台。本质上，此代码片段充当从 PDF 文档中提取和显示特定文本模式的机制。 此外，.NET Search API 还支持 Microsoft [Word文档搜索](https://products.aspose.com/total/net/search/word/) 和其他格式。

{{% blocks/products/pf/feature-page-code h3="PDF 文档搜索的 C# 代码" %}}

{{< gist "aspose-com-gists" "3c806eb023f399cd402ab922a247f2d0" "pdf-document-search.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}