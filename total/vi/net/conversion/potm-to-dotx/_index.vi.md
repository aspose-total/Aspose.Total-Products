---
title: Chuyển đổi POTM sang DOTX qua C# .NET 
url: /vi/net/conversion/potm-to-dotx/ 
description: Chuyển đổi tài liệu potm PowerPoint sang tệp Word dotx bằng C#. Chuyển đổi nhiều tệp trong ASP.NET hoặc các ứng dụng .NET khác.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi POTM sang DOTX bằng C#" h2="Xây dựng Microsoft PowerPoint POTM Presentation sang các ứng dụng chuyển đổi tài liệu Word DOTX trên .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platforms." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTM" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOTXM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" dotxsLink="https://dotxs.aspose.com/total/net" installationsDotxsLink="https://dotxs.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://dotxs.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển đổi POTM sang DOTX bằng C#" %}}

Để tự động hóa quy trình chuyển đổi hàng loạt tệp PowerPoint potm sang tệp Word dotx, chúng tôi sẽ sử dụng [Aspose.Slides cho .NET](https://products.aspose.com/slides/net) và [Aspose.Words cho các API .NET](https://products.aspose.com/words/net). Trước đây là một API thao tác trình bày PowerPoint cho phép bạn tạo hoặc sửa đổi các trang trình bày Microsoft PowerPoint. Trong khi, cái sau là một API xử lý văn bản để xử lý hoặc thao tác các tài liệu Microsoft Word. Cả hai API đều là một phần của gói [Aspose.Total cho .NET](https://products.aspose.com/total/net). Bạn có thể trực tiếp [tải xuống](https://downloads.aspose.com/) từ Nuget hoặc có thể sử dụng các lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Lệnh Bảng điều khiển Trình quản lý Gói" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi POTM sang DOTX qua C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Thêm tham chiếu của Aspose.Slides cho .NET và Aspose.Words cho .NET
1. Tải bản trình bày PowerPoint POTM bằng lớp [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Lưu tài liệu vào [MemoryStream](https://dotxs.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) Đối tượng
1. Tạo [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) và phức tạp hóa nó bằng MemoryStream Object
1. Lưu tài liệu bằng [Aspose.Words.Document.Save ("output.dotx", SaveFormat.Dotx)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platforms.
- Môi trường phát triển như Microsoft Visual Studio.
- Aspose.Slides cho .NET và Aspose.Words cho .NET DLL được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mẫu mã này cho thấy cách chuyển đổi POTM sang DOTX bằng C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint POTM file
Aspose.Slides.Presentation potm = new Aspose.Slides.Presentation("source.potm");

var stream = new MemoryStream();

potm.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var dotx = new Aspose.Words.Document(stream);
      
// Save the Word DOTX document
dotx.Save("output.dotx", Aspose.Words.SaveFormat.Dotx);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ứng dụng miễn phí để chuyển đổi POTM sang DOTX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOTXM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POTM file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-dotx" name="POTM Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-dotx" name="POTM Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-rtf" name="POTM Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-dot" name="POTM Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-dotx" name="POTM Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-dotm" name="POTM Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-dotxm" name="POTM Đến DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-flatopc" name="POTM Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-odt" name="POTM Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-ott" name="POTM Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-wordml" name="POTM Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potm-to-txt" name="POTM Đến TXT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}