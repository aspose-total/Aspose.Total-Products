---
title: 用于将 EPUB 导出到 DOCM 的 Java API
description: 使用本地 Java API 将 EPUB 转换为 DOCM
url_ignore: /zh/java/conversion/epub-to-docm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: DOCM
otherformats: ODT WORDML MARKDOWN RTF PCL XAMLFLOW DOTX PS DOT OTT MHTML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 EPUB 转换为 DOCM" h2="在不使用任何第三方应用程序的情况下，将 EPUB 渲染为 DOCM 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
您可以使用两个简单的步骤将 EPUB 转换为 DOCM。首先，您需要使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) 将 EPUB 文件渲染为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/)，您可以将 DOC 转换为 DOCM。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 包。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API 将 EPUB 转换为 DOCM" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开EPUB文件
2. 用[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-将EPUB转换为DOC ) 方法
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)类加载DOC文件
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 方法将文档保存为 DOCM 格式并设置 DOCM保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 打开受密码保护的 EPUB 文档" %}}
在将 EPUB 转换为 DOCM 时，即使您的文档受密码保护，您仍然可以使用 PDF 操作 API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) 打开它。为了打开加密文件，您需要创建一个 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 对象并使用所有者的密码打开 EPUB。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 DOCM 文档保存到数据库" %}}
在将输入文档保存为 DOCM 文件格式的同时，您还可以将文档保存到数据库而不是文件系统。您可能需要实现在数据库中存储和检索 Document 对象。如果您正在实施任何类型的内容管理系统，这将是必要的。为了将您的 DOCM 保存到数据库，通常需要序列化文档以获取字节数组。这可以使用 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API 来完成。获取字节数组后，您可以使用 SQL 语句将其存储在数据库中。 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOCM);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
将 **EPUB 转换为 DOCM** 对于从数字出版物生成 **启用宏的 Word 文档** 非常有价值。 DOCM 文件允许集成自动化脚本和宏，从而可以简化文档处理、增强互动性，并创建智能的出版工作流程。通过将电子书转换为 DOCM，出版商、学者和企业可以优化报告、保护数字版权，并自动化复杂的内容任务。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}
- **自动化出版工作流程** – 简化编辑和内容生产流程。
- **研究文档自动化** – 生成带有嵌入式宏的结构化报告。
- **带宏的学术内容** – 创建互动式学习材料和自动化分析工具。
- **数字版权管理文档** – 使用自动化控制安全地分发电子书内容。
- **企业报告生成** – 从出版数据构建动态的、启用宏的报告。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}
- **EPUB 到 DOCM 管道** – 自动化将电子书转换为启用宏的 Word 文件。
- **自动化启用宏文档创建** – 使用自定义脚本即时生成 DOCM 文件。
- **批量电子书转换为 Word** – 高效处理大型数字图书馆。
- **基于工作流的出版自动化** – 将 DOCM 生成集成到企业内容系统中。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}