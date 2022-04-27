---
title: 用于将 SVG 导出到 GIF 的 Java API
description: 使用本地 Java API 将 SVG 转换为 GIF
url: /zh/java/conversion/svg-to-gif/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: GIF
otherformats: WORDML DOTM MHTML ODT DOT FLATOPC DOTX XAMLFLOW MARKDOWN PS PCL RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 SVG 转换为 GIF" h2="在不使用任何第三方应用程序的情况下，将 SVG 渲染为 GIF 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
您可以使用两个简单的步骤将 SVG 转换为 GIF。首先，您需要使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) 将 SVG 文件渲染为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/)，您可以将 DOC 转换为 GIF。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 包。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API 将 SVG 转换为 GIF" %}}
1.使用[Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开SVG文件
2.使用[save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-将SVG转换为DOC ） 方法
3.使用Aspose.Words的[Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)类加载DOC文件
4. 使用 [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 方法将文档保存为 GIF 格式并设置 GIF保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。。

或者，您可以从 [下载](https://downloads.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.GIF
outputDocument.save("output.gif", SaveFormat.GIF);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 打开受密码保护的 SVG 文档" %}}
在将 SVG 转换为 GIF 时，即使您的文档受密码保护，您仍然可以使用 PDF 操作 API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) 打开它。为了打开加密文件，您需要创建一个 [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) 对象并使用所有者的密码打开 SVG。  
{{% blocks/products/pf/feature-page-code %}}
```cs```cs
// open encrypted document
Document document = new Document("input.svg", "password");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 GIF 文档保存到数据库" %}}
在将输入文档保存为 GIF 文件格式的同时，您还可以将文档保存到数据库而不是文件系统。您可能需要实现在数据库中存储和检索 Document 对象。如果您正在实施任何类型的内容管理系统，这将是必要的。为了将您的 GIF 保存到数据库，通常需要序列化文档以获取字节数组。这可以使用 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API 来完成。获取字节数组后，您可以使用 SQL 语句将其存储在数据库中。 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.GIF);
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
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-rtf/" name="SVG 到 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-wordml/" name="SVG 到 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-odt/" name="SVG 到 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-flatopc/" name="SVG 到 FLA到PC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-ps/" name="SVG 到 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-pcl/" name="SVG 到 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-mhtml/" name="SVG 到 MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-dotm/" name="SVG 到 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-ott/" name="SVG 到 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-dotx/" name="SVG 到 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-xamlflow/" name="SVG 到 XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/svg-to-markdown/" name="SVG 到 MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}