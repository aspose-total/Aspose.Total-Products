---
title: 在线或使用 .NET 删除 Excel 密码保护
description: 通过在线应用程序免费删除 Excel 文档的密码。用于解锁受密码保护的 Excel 文件的 .NET C# API 代码。

family: total
platformtag: net
feature: Unlock
informat: Excel
otherformats: PDF Word DOC DOCX ODT Powerpoint PPT PPTX ODP Excel XLS XLSX ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在线或通过 .NET 解锁 Excel 文档密码" h2="开发强大的基于 .NET 的 Excel 文档锁定和解锁实用程序。列出用于通过 .NET 从 Excel 文件中删除密码限制的代码。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在线解锁Excel密码" %}}

1. 导入Excel文件通过上传来解锁。
1. 通过拖放应用程序在放置区域内单击来完成此操作。
1. 根据 Excel 文件的大小和互联网速度，等待几秒钟。
1. 输入要删除的密码。
1. 单击“解锁”按钮解锁文档。
1. 立即下载文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过 .NET 删除 Excel 密码" %}}

1. 使用 Workbook 类加载受密码保护的 Excel 文件
1. 选择相关工作表
1. 调用 Unprotect() 方法删除密码
1. 调用Save方法保存文档

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title=".NET 代码：从 Excel 文档中删除密码" offSpacer="" %}}

{{< gist "aspose-com-gists" "a5f6deeb0f825bbb2a2c921be72e3c9f" "unlock-excel-spreadsheet.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>通过.NET开发Excel保护管理应用程序</h2>

需要开发 Excel 保护管理应用程序或实用程序？借助 [Aspose.Cells for .NET](https://products.aspose.com/cells/zh/net/)（[Aspose.Total for .NET](https://products.aspose.com/total/zh/net/) 的子 API），任何 .NET 开发人员都可以将上述 API 代码集成到其文档保护或取消保护应用程序中。强大的.NET 库允许对任何文档保护解决方案进行编程。而且它可以支持许多流行的格式，包括Excel格式。<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于管理 Excel 保护的 .NET 实用程序" %}}

可以通过三个替代选项将“Aspose.Cells for .NET”或“Aspose.Total for .NET”安装到您的系统上。请选择符合您需求的一项并按照分步说明进行操作：<br /><br />

- 安装 [NuGet 包](https://www.nuget.org/packages/Aspose.Cells/)。参见 [文档](https://docs.aspose.com/cells/net/installation/)
- 在 Visual Studio IDE 中使用 [包管理器控制台](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-package-manager-gui) 安装库
- 使用 [Windows安装程序](https://docs.aspose.com/cells/net/installing-aspose-cells-on-windows/) 手动安装库

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}
我们的产品完全跨平台，支持遵循“.NET Standard 2.0”规范的所有主要 .NET 实现：<br /><br />

- Microsoft .NET Framework，从最早的2.0版本开始，到最新的“.NET Framework 4.8”结束
- .NET Core，从最早的2.0开始，到最新的“.NET 6”结束
- 单声道 >= 2.6.7
<br /><br />
由于 .NET 代码不依赖于底层硬件或操作系统，而仅依赖于虚拟机，因此您可以自由地为 Windows、macOS、Android、iOS 和 Linux 开发任何类型的软件。只需确保您已安装相应版本的 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin。<br /><br />
我们建议使用 Microsoft Visual Studio、Xamarin 和 MonoDevelop IDE 创建 C#、F#、VB.NET 应用程序。
<br /><br />
欲了解更多详情，请参阅[产品文档](https://docs.aspose.com/cells/net/system-requirements/)。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}
To unlock a Microsoft Excel file, consider the following structured approach based on various protection mechanisms:

1. **Understand Protection Types**:
   - **Cell Protection**: Individual cells may be locked; use functions like `UNLOCKED` to make them editable.
   - **Sheet Protection**: Entire worksheets might be locked; check if you can edit or unprotect sheets.
   - **Workbook Protection**: All data within the workbook is locked; seek permission from the owner to remove this protection.

2. **Handle Password Protection**:
   - If a file is password-protected, attempt to open it with the correct password. If forgotten, consider ethical and legal implications before bypassing.

3. **Request Editing Rights**:
   - For read-only files, contact the owner to request editing rights if necessary modifications are required.

4. **Access Hidden Data**:
   - Use Excel functions or tools to unhide sheets or ranges that might be locked or hidden by previous users.

5. **Automate Tasks with Scripts**:
   - Utilize Python or Excel macros to automate unlocking processes, especially for handling large datasets or repetitive tasks.

6. **Adjust Sharing Permissions**:
   - Modify file sharing settings to allow multiple users access and editing rights as needed.

7. **Troubleshoot Corrupted Files**:
   - Unlock files to gain better access for identifying and resolving issues like errors or corrupted data.

8. **Ethical Considerations**:
   - Always ensure unlocking is done with proper authorization, especially for sensitive data, respecting others' work and privacy.

By addressing each type of restriction methodically, you can effectively unlock Excel files while maintaining ethical practices and ensuring smooth collaboration.
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="常见问题解答" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>常见问题解答</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我可以在我的应用程序中使用上述 .NET 代码吗？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">是的，欢迎您下载此代码并将其用于开发基于 .NET 的文档保护或解锁应用程序。该代码可以作为宝贵的资源来增强您的项目在后端文档处理、操作和保护领域的功能和能力。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>此在线文档解锁应用程序仅适用于 Windows 吗？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以灵活地在任何设备上启动文档解锁以删除密码，无论其运行何种操作系统，无论是 Windows、Linux、Mac OS 还是 Android。所需要的只是一个现代的网络浏览器和一个活跃的互联网连接。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用在线应用程序取消 Excel 文档的保护是否安全？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">当然！通过我们的服务生成的输出文件将在 24 小时内安全地自动从我们的服务器中删除。因此，与这些文件关联的显示链接将在此期限后停止运行。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>App应该用什么浏览器？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以使用任何现代网络浏览器（例如 Google Chrome、Firefox、Opera 或 Safari）进行在线 Excel 文档解锁。但是，如果您正在开发桌面应用程序，我们建议使用 Aspose.Total 文档处理 API 进行高效管理。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}