---
title: 用于将 CGM 导出到 MHTML 的 Java API
description: 使用本地 Java API 将 CGM 转换为 MHTML
url_ignore: /zh/java/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: XAMLFLOW DOTX WORDML OTT FLATOPC DOTM PCL ODT PS MHTML MARKDOWN DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 CGM 转换为 MHTML" h2="在不使用任何第三方应用程序的情况下，将 CGM 渲染为 MHTML 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
您可以使用两个简单的步骤将 CGM 转换为 MHTML。首先，您需要使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) 将 CGM 文件渲染为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/)，您可以将 DOC 转换为 MHTML。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 包。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API 将 CGM 转换为 MHTML" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开CGM文件
2. 用[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-将CGM转换为DOC ) 方法
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)类加载DOC文件
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 方法将文档保存为 MHTML 格式并设置 MHTML保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 打开受密码保护的 CGM 文档" %}}
在将 CGM 转换为 MHTML 时，即使您的文档受密码保护，您仍然可以使用 PDF 操作 API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) 打开它。为了打开加密文件，您需要创建一个 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 对象并使用所有者的密码打开 CGM。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 MHTML 文档保存到数据库" %}}
在将输入文档保存为 MHTML 文件格式的同时，您还可以将文档保存到数据库而不是文件系统。您可能需要实现在数据库中存储和检索 Document 对象。如果您正在实施任何类型的内容管理系统，这将是必要的。为了将您的 MHTML 保存到数据库，通常需要序列化文档以获取字节数组。这可以使用 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API 来完成。获取字节数组后，您可以使用 SQL 语句将其存储在数据库中。 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
将**计算机图形元文件（CGM）**文件转换为**MHTML（MIME HTML）**格式对于保留嵌入式图形的复杂工程和技术文档至关重要，使其成为一个单一的、自包含文件。在**基于Java的Web存档系统**中，这种转换使组织能够将完整文档（包括CGM图形、样式和资源）存储在便于离线查看和内部部署的便携式存档中。MHTML确保设计规范、报告和图纸能够长期保持完整，以便进行访问和分发。

---

## ✅ 主要用例

- **捆绑带有嵌入式图形的工程文档**  
  将CGM图表和相关内容打包到MHTML中，形成一致、自包含的技术记录。

- **内部门户网站的离线查看**  
  为企业网络提供以CGM增强的文档，以MHTML格式实现无缝的离线访问。

- **存档设计规范**  
  存储基于CGM的规范的MHTML版本，用于合规性、参考和项目文档。

---

## ⚙️ 自动化场景

- **具有MHTML支持的Java库**  
  使用诸如**Aspose.Words for Java**之类的API或自定义Java导出器从基于CGM的文档生成MHTML文件。

- **基于Web的导出工具**  
  将CGM转换为MHTML集成到基于Java的Web应用程序中，实现即时文件打包。

- **基于Servlet的转换工作流**  
  部署处理CGM输入并输出MHTML存档以进行安全分发的Java servlet。

- **自动化存档流水线**  
  在基于Java的文档管理或ETL系统中包含CGM到MHTML的步骤，用于定期存档。
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}