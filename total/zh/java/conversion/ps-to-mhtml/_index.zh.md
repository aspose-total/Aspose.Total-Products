---
title: 用于将 PS 导出到 MHTML 的 Java API
description: 使用本地 Java API 将 PS 转换为 MHTML
url_ignore: /zh/java/conversion/ps-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: MHTML
otherformats: WORDML RTF XAMLFLOW MHTML DOTX DOT DOTM PCL FLATOPC ODT OTT MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 PS 转换为 MHTML" h2="在不使用任何第三方应用程序的情况下，将 PS 渲染为 MHTML 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
您可以使用两个简单的步骤将 PS 转换为 MHTML。首先，您需要使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) 将 PS 文件渲染为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/)，您可以将 DOC 转换为 MHTML。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 包。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API 将 PS 转换为 MHTML" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开PS文件
2. 用[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-将PS转换为DOC ) 方法
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)类加载DOC文件
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 方法将文档保存为 MHTML 格式并设置 MHTML保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 打开受密码保护的 PS 文档" %}}
在将 PS 转换为 MHTML 时，即使您的文档受密码保护，您仍然可以使用 PDF 操作 API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) 打开它。为了打开加密文件，您需要创建一个 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 对象并使用所有者的密码打开 PS。  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 MHTML 文档保存到数据库" %}}
在将输入文档保存为 MHTML 文件格式的同时，您还可以将文档保存到数据库而不是文件系统。您可能需要实现在数据库中存储和检索 Document 对象。如果您正在实施任何类型的内容管理系统，这将是必要的。为了将您的 MHTML 保存到数据库，通常需要序列化文档以获取字节数组。这可以使用 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API 来完成。获取字节数组后，您可以使用 SQL 语句将其存储在数据库中。 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MHTML);
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

将PS（PostScript）文件转换为MHTML（MIME HTML）可将完整的PostScript文档（包括文本、图形和图像）保存为单个、便携的网页。MHTML非常适合用于存档、共享和基于网络的展示PostScript内容。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* 将PS报告和手册存档为独立的网页。
* 将PostScript文档转换为离线浏览器访问。
* 在单个文件中共享复杂的PS图表和布局。
* 在与网络兼容的HTML存档中保留原始PS格式。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* 批量进行PS到MHTML的转换以进行存档和记录保存。
* 集成到文档管理系统中以进行网络分发。
* 从PS文件生成可离线查看的HTML的基于云的方式。
* 用于电子邮件报告和视觉内容的自动转换。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}