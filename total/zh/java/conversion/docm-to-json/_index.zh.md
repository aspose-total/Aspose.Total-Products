---
title: 通过 Java 将 DOCM 转换为 JSON 格式
description: 通过 Java 将 DOCM 转换为 JSON 格式，而不使用 Microsoft Word 或 Microsoft Excel
url_ignore: /zh/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 DOCM 转换为 JSON 格式" h2="无需使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel 即可将 DOCM 转换为 JSON 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将 DOCM 转换为 JSON 格式是一个简单的两步过程。通过使用功能丰富的文档操作和转换 API [Aspose.Words for Java](https://products.aspose.com/words/java/)，您可以将 DOCM 导出为 HTML。之后，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 HTML 转换为 JSON。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 DOCM 转换为 JSON 格式" %}}
1. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类打开 DOCM 文件
2. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将 DOCM 转换为 HTML ) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 HTML 文档
4. 使用 [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.) 将文档保存为 JSON 格式方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将受保护的 DOCM 转换为 JSON 格式" %}}
使用 API，您还可以打开受密码保护的文档。如果您的输入 DOCM 文档受密码保护，则您无法在不使用密码的情况下将其转换为 JSON 格式。 API 允许您通过在 LoadOptions 对象中传递正确的密码来打开加密的文档。以下代码示例显示了如何尝试使用密码打开加密文档：  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 DOCM 转换为 Range 中的 JSON" %}}
在将 DOCM 转换为 JSON 时，您还可以将范围设置为输出 JSON 格式。为了设置范围，您可以使用 Workbook 类打开转换后的 HTML，使用 Cells.createRange 方法创建要导出的数据范围，使用 Range 和 ExportRangeToJsonOptions 的引用调用 JsonUtility.exportRangeToJson 方法并将字符串 JSON 数据写入文件通过BufferedWriter.write 方法。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## 将 **DOCM（Word宏启用文档）** 转换为 **JSON（JavaScript对象表示法）** 对于将静态文档内容、表格和表单字段转换为 **结构化、可机器读取的数据** 至关重要。JSON 是轻量级的、易读的，在 **API、分析、Web 应用程序和自动化工作流** 中被广泛使用。通过将数据从 DOCM 提取为 JSON，组织可以解锁跨现代平台的互操作性，实现更快的集成，并确保数据准备好用于 **实时处理、验证和可扩展分发**。  

## ✅ 主要用例  

- **将文档数据发布到 REST/GraphQL API**  
  将提取的 DOCM 内容作为 JSON 提供，以便在 Web 和移动应用程序中直接使用 API。  

- **向 NoSQL 数据库和数据湖提供数据**  
  将基于 DOCM 的结构化数据加载到 MongoDB、Elasticsearch 或基于云的数据湖中。  

- **通过实时 JSON 数据源为仪表板提供动力**  
  将基于文档的关键绩效指标和指标流式传输到 BI 仪表板和监控工具中。  

- **根据 JSON 模式验证输入**  
  通过将 DOCM 字段数据与 JSON 模式规则对齐，确保一致性和完整性。  

- **启用无头 CMS 或微服务架构**  
  将 DOCM 内容集成到分布式、以 API 为先的系统中，其中 JSON 是通用语言。  

## ⚙️ 自动化场景  

- **具有字段映射的 DOCM 到 JSON 提取**  
  定义映射以将表格、标题和字段转换为结构化的 JSON 对象。  

- **转换并发出 JSON 事件的无服务器函数**  
  在文件上传时触发转换，将 JSON 负载发送到事件驱动系统。  

- **规范化类型和键的 ETL 作业**  
  将 DOCM 导出标准化为一致的 JSON 结构，以供下游分析使用。  

- **将 JSON 推送到下游系统的 Webhooks**  
  自动化将 DOCM 转换为 JSON 导出，以供 CRM、ERP 工具或第三方应用程序使用。  

- **在导出 JSON 之前剥离宏和 PII 的治理规则**  
  应用合规性检查，以确保从启用宏的文件中获得安全、经过清理的 JSON 输出。  
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}