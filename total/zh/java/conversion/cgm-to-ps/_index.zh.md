---
title: 用于将 CGM 导出到 PS 的 Java API
description: 使用本地 Java API 将 CGM 转换为 PS
url_ignore: /zh/java/conversion/cgm-to-ps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PS
otherformats: MHTML MARKDOWN ODT DOT WORDML OTT RTF PS FLATOPC DOTM DOTX PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 CGM 转换为 PS" h2="在不使用任何第三方应用程序的情况下，将 CGM 渲染为 PS 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
您可以使用两个简单的步骤将 CGM 转换为 PS。首先，您需要使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) 将 CGM 文件渲染为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/)，您可以将 DOC 转换为 PS。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 包。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API 将 CGM 转换为 PS" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开CGM文件
2. 用[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-将CGM转换为DOC ) 方法
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)类加载DOC文件
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 方法将文档保存为 PS 格式并设置 PS保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 打开受密码保护的 CGM 文档" %}}
在将 CGM 转换为 PS 时，即使您的文档受密码保护，您仍然可以使用 PDF 操作 API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) 打开它。为了打开加密文件，您需要创建一个 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 对象并使用所有者的密码打开 CGM。  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.cgm", "password");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 PS 文档保存到数据库" %}}
在将输入文档保存为 PS 文件格式的同时，您还可以将文档保存到数据库而不是文件系统。您可能需要实现在数据库中存储和检索 Document 对象。如果您正在实施任何类型的内容管理系统，这将是必要的。为了将您的 PS 保存到数据库，通常需要序列化文档以获取字节数组。这可以使用 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API 来完成。获取字节数组后，您可以使用 SQL 语句将其存储在数据库中。 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PS);
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
{{< blocks/products/pf/agp/feature-section >}}
```
将 CGM（计算机图形元文件）转换为 PS（PostScript）是实现精确、高质量印刷和专业出版结果的关键步骤。PostScript 的设备无关格式确保复杂的矢量图形、工程图和技术插图在转移到印刷机或出版系统时保持准确性和保真度。这使得 CGM 转 PS 转换对需要一致、可扩展和印刷就绪输出的行业至关重要。

{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}
- **工业级矢量打印** – 为制造、工程和建筑文档制作清晰、可扩展的技术图表。
- **在基于 PostScript 系统中存档技术插图** – 将矢量资产存储为长期可访问性和打印兼容性优化的格式。
- **为排版准备 CGM 图表** – 确保无缝集成到专业页面布局和排版工作流程中。
- **物理文档制作** – 为手册、目录和大幅面技术图表生成印刷就绪文件。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}
- **基于 Java 的打印流生成器** – 以编程方式将 CGM 文件转换为高分辨率 PS 输出，用于企业打印工作流程。
- **矢量到 PostScript 批量转换器** – 自动化大规模转换过程，高效处理广泛的图形存档。
- **出版流水线集成** – 将 CGM 转 PS 转换嵌入到自动化文档渲染和专业出版系统中，以获得一致、高质量的结果。
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}