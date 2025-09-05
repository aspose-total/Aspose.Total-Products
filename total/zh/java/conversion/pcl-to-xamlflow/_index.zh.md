---
title: 在线将 PCL 转换为 XAMLFLOW 或开发基于 Java 的应用程序来转换 PCL 文件
description: 免费在线应用程序将 PCL 文件转换为 XAMLFLOW 文件。PCL 文档的 Java 转换库代码。 

family: total
platformtag: Java
feature: conversion
informat: PCL
outformat: XAMLFLOW
otherformats: RTF OTT DOTX FLATOPC ODT PS DOTM MHTML WORDML MARKDOWN DOT XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在线 PCL 到 XAMLFLOW 转换应用程序和 Java 代码来转换 PCL 文件" h2="开发强大的基于 Java 的 PCL 转换和导出应用程序。 通过 Java 自动化 API 将单个或多个 PCL 文件转换为 XAMLFLOW 和其他格式。 通过应用程序在线自由转换 PCL 文件并即时下载。" >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="免费在线 PCL 至 XAMLFLOW 转换应用程序" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=xamlflow&from=pcl" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="使用应用程序在线将 PCL 文件转换为 XAMLFLOW 文件" %}}

1. 上传 PCL 文件进行转换
1. 等待几秒钟或更长时间，具体取决于 PCL 大小
1. 留意上传状态栏
1. 点击“转换”按钮
1. PCL 将转换为 XAMLFLOW 文档
1. 下载转换后的XAMLFLOW文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 自动化 API 将 PCL 转换为 XAMLFLOW" %}}


1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开PCL文件
2. 用[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-将PCL转换为DOC ) 方法
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)类加载DOC文件
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 方法将文档保存为 XAMLFLOW 格式并设置 XAMLFLOW保存格式



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}


```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.XAML_FLOW
outputDocument.save("output.xaml_flow", SaveFormat.XAML_FLOW);   
```



{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

使用其他功能（如 通过 Java 打开受密码保护的 PCL 文档, 通过 Java 将 XAMLFLOW 文档保存到数据库）将 PCL 保存为 XAMLFLOW 的情况较少。

{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.pcl", "password");
// save PCL as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.XAML_FLOW);
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


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>使用 Java 开发 PCL 文件转换应用程序</h2>

需要开发基于 Java 的软件应用程序来轻松保存和导出 PCL 文件到 XAMLFLOW 文档吗？ 通过[Aspose.Total for Java](https://products.aspose.com/total/zh/java/)，任何Java开发人员都可以集成上述API代码来编写跨多种格式的转换应用程序，包括Microsoft Word（DOC、DOCX）、Excel（XLS、XLSX）、Powerpoint（PPT、PPTX）、PDF、电子邮件文件、图像（JPG、PNG、BMP、GIF）和其他格式。 强大的 Java 文档转换库，支持许多流行格式，包括 PCL 格式。 将文档导出和渲染为其他格式，程序员可以使用 Aspose.Total for Java 子 API，包括 [Aspose.Words for Java](https://products.aspose.com/words/zh/java/)、[Aspose.Cells for Java](https://products.aspose.com/cells/zh/java/)、[Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/)、[Aspose.PDF for Java](https://products.aspose.com/pdf/zh/java/)、[Aspose.Imaging for Java](https://products.aspose.com/imaging/zh/java/) 等。<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PCL Java 转换库" %}}

还有其他选项可以将 Aspose.Total for Java 集成到您的系统中。 请选择一个符合您需求的方案并按照分步说明进行操作：<br /><br />

- 直接从基于 Maven 的项目中使用 Aspose.Total for Java，并在 pom.xml 中包含相关子 API。
- 或者，可以从 [下载](https://releases.aspose.com/total/java) 获取一个 ZIP 文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="正在将 PCL 保存至 XAMLFLOW 应用要求" %}}

任何可以运行 Java 运行时环境 (JRE) 的操作系统都可以运行 Aspose.Total for Java。 以下列出了大多数（但不是全部）受支持的操作系统。 <br /><br />
- 微软 Windows
- Linux：Ubuntu、OpenSUSE、CentOS 等
- macOS ：10.9 (Mavericks) 及更高版本
- 移动设备：Android、iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}