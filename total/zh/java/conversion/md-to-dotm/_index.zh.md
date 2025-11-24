---
title: 用于将 MD 导出到 DOTM 的 Java API
description: 使用本地 Java API 将 MD 转换为 DOTM
url_ignore: /zh/java/conversion/md-to-dotm/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOTM
otherformats: PS DOTM FLATOPC MHTML PCL MARKDOWN RTF DOT OTT ODT WORDML DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 MD 转换为 DOTM" h2="在不使用任何第三方应用程序的情况下，将 MD 渲染为 DOTM 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
您可以使用两个简单的步骤将 MD 转换为 DOTM。首先，您需要使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) 将 MD 文件渲染为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/)，您可以将 DOC 转换为 DOTM。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 包。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API 将 MD 转换为 DOTM" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开MD文件
2. 用[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-将MD转换为DOC ) 方法
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)类加载DOC文件
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 方法将文档保存为 DOTM 格式并设置 DOTM保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 打开受密码保护的 MD 文档" %}}
在将 MD 转换为 DOTM 时，即使您的文档受密码保护，您仍然可以使用 PDF 操作 API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) 打开它。为了打开加密文件，您需要创建一个 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 对象并使用所有者的密码打开 MD。  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 DOTM 文档保存到数据库" %}}
在将输入文档保存为 DOTM 文件格式的同时，您还可以将文档保存到数据库而不是文件系统。您可能需要实现在数据库中存储和检索 Document 对象。如果您正在实施任何类型的内容管理系统，这将是必要的。为了将您的 DOTM 保存到数据库，通常需要序列化文档以获取字节数组。这可以使用 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API 来完成。获取字节数组后，您可以使用 SQL 语句将其存储在数据库中。 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOTM);
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



MD（Markdown）转换为DOTM（启用宏的模板）将轻量级文本编辑与嵌入宏增强的Word模板相结合。DOTM模板使团队能够自动化重复的文档任务，并立即创建标准化的、准备好宏的文档。



{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}



* 从Markdown手册构建带宏的入职模板。

* 创建从MD内容获取的自动化发票或表单模板。

* 具有以编程方式插入字段的企业文档框架。

* 从技术文档生成可重复使用的自动化友好模板。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}



* 为大规模报告周期自动构建DOTM模板。

* 与触发MD到DOTM生成的工作流引擎集成。

* 一键创建分布式部门的启用宏模板。

* 在模板重新生成期间自动插入动态内容。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}