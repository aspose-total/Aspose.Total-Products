---
title: Chuyển đổi TXT sang PPSX qua C# .NET hoặc với Trình chuyển đổi trực tuyến miễn phí
description: Chuyển đổi tài liệu Word txt sang tệp ppsx PowerPoint bằng C#. Chuyển đổi nhiều tệp trong ASP.NET hoặc các ứng dụng .NET khác.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi TXT sang PPSX bằng C# hoặc trực tuyến" h2="Xây dựng ứng dụng chuyển đổi Microsoft Word TXT sang PowerPoint PPSX trên Nền tảng .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Cách chuyển TXT sang PPSX bằng C#" %}}

Để tự động hóa quy trình chuyển đổi hàng loạt tệp Word txt sang PowerPoint ppsx của bản trình bày, chúng tôi sẽ sử dụng [Aspose. AdWords for .NET](https://products.aspose.com/words/net) và [Aspose.Slides cho các API .NET](https://products.aspose.com/slides/net). Trước đây là một API xử lý văn bản để xử lý hoặc thao tác các tài liệu Microsoft Word. Trong khi, cái thứ hai là một API thao tác trình bày cho phép bạn tạo hoặc sửa đổi các trang trình bày Microsoft PowerPoint. Cả hai API đều là một phần của gói [Aspose.Total cho .NET](https://products.aspose.com/total/net). Bạn có thể trực tiếp [tải xuống](https://releases.aspose.com/) từ Nuget hoặc có thể sử dụng các lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Lệnh Bảng điều khiển Trình quản lý Gói" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi TXT sang PPSX qua C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Thêm tham chiếu của Aspose.Total cho .NET
1. Tải tệp TXT bằng lớp [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Lưu tài liệu TXT thành HTML
1. Tạo đối tượng [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Nhập nội dung HTML trong khung văn bản của bất kỳ hình dạng trang chiếu nào bên trong bản trình bày
1. Lưu tài liệu bằng [Aspose.Slides.Presentation.Save("output.ppsx", SaveFormat.Ppsx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platforms.
- Môi trường phát triển như Microsoft Visual Studio.
- Aspose. AdWords dành cho .NET & amp; Aspose.Slides cho .NET DLL hoặc Aspose.Total cho .NET DLL được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mẫu mã này cho thấy cách chuyển đổi TXT sang PPSX bằng C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word TXT file
Aspose.Words.Document txt = new Aspose.Words.Document("sourceWordFile.txt");

// Save TXT file to HTML 
txt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages TXT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPSX.

using (Presentation ppsx = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the PPSX Presentation
	ppsx.Save("filepath\\pres.ppsx", Aspose.Slides.Export.SaveFormat.Ppsx);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Công cụ chuyển đổi trực tuyến từ TXT sang PPSX</h3>

<iframe title="Công cụ trực tuyến chuyển đổi từ txt sang ppsx" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=ppsx&from=txt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ứng dụng miễn phí để chuyển đổi TXT sang PPSX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPSX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp TXT sang PPSX theo chương trình: Các trường hợp sử dụng" %}}
Tập tin TXT (Text File) được sử dụng để lưu thông tin văn bản thô, khiến chúng trở nên lý tưởng để tạo các tài liệu và dữ liệu cần có tính đọc được bởi con người. Tuy nhiên, khi làm việc với nội dung đa phương tiện, trình diễn PowerPoint của Microsoft trở nên quan trọng để kể chuyện hình ảnh và giao tiếp.

Chuyển đổi các file TXT thành các định dạng PowerPoint là việc cần thiết để khai thác hết khả năng trình diễn và giao tiếp hình ảnh của bạn. Việc này cho phép bạn:

**Ứng dụng:**

*   **Báo cáo công ty**: Chuyển các file TXT thành báo cáo công ty hấp dẫn, biểu đồ thông tin và báo cáo thu hút sự chú ý của khán giả.
*   **Sản phẩm quảng cáo sự kiện**: Sử dụng PowerPoint để thiết kế tờ rơi, poster và hình ảnh social media để quảng bá các sự kiện và mời gọi người đến dự.
*   **Tóm tắt论文 nghiên cứu**: Chuyển các file TXT thành tóm tắt ngắn gọn của các bài论文, nhấn mạnh kết quả quan trọng và khuyến nghị cho các quyết định gia đình.
*   **Chuyện kể hình ảnh tương tác**: Sử dụng PowerPoint để kể chuyện hình ảnh qua các trình diễn multimedia, video và animation thu hút khán giả một cách sâu sắc.
*   **Sản phẩm marketing**: Chuyển các file TXT thành các tài liệu marketing hiệu quả như bảng giá bán, mô tả sản phẩm và đánh giá của khách hàng.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Các câu hỏi thường gặp</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Làm cách nào tôi có thể chuyển đổi TXT sang PPSX trực tuyến?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">App chuyển đổi TXT Online đã được tích hợp bên trên. Để sử dụng ứng dụng này, bạn có thể thêm tệp TXT của mình bằng cách kéo và thả tệp vào vùng màu trắng được chỉ định hoặc bằng cách nhấp vào bên trong khu vực để nhập tài liệu. Tiếp theo, nhấn nút Convert để bắt đầu quá trình chuyển đổi. Sau khi quá trình chuyển đổi TXT sang PPSX hoàn tất, bạn có thể tải xuống tệp mới được chuyển đổi của mình chỉ bằng một cú nhấp chuột và tệp sẽ có sẵn cho bạn ở dạng tệp PPSX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Mất bao lâu để chuyển đổi TXT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Trình chuyển đổi trực tuyến này hoạt động nhanh chóng nhưng chủ yếu phụ thuộc vào kích thước của tệp TXT được chuyển đổi. Đối với các tệp TXT nhỏ, quá trình chuyển đổi sang PPSX có thể được hoàn tất trong vài giây. Tuy nhiên, nếu bạn đã tích hợp mã chuyển đổi trong ứng dụng .NET, tốc độ chuyển đổi sẽ phụ thuộc vào mức độ ứng dụng của bạn đã được tối ưu hóa cho quá trình chuyển đổi.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Có an toàn khi chuyển đổi TXT sang PPSX bằng trình chuyển đổi Aspose.Total miễn phí không?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Tất nhiên rồi! Khi quá trình chuyển đổi TXT sang PPSX hoàn tất, liên kết tải xuống cho tệp PPSX mới được chuyển đổi sẽ khả dụng ngay lập tức. Nó cũng đảm bảo sự an toàn của quá trình chuyển đổi, vì tất cả các tệp đã tải lên, bao gồm cả tệp TXT, đều hoàn toàn an toàn và sẽ bị xóa khỏi hệ thống sau 24 giờ. Hơn nữa, các liên kết tải xuống sẽ ngừng hoạt động sau khoảng thời gian này, đảm bảo quyền riêng tư và bảo vệ các tệp của bạn. Ứng dụng tích hợp được sử dụng miễn phí và được thiết kế cho mục đích thử nghiệm để người dùng có thể đánh giá kết quả trước khi tích hợp mã vào dự án của họ.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Tôi nên sử dụng trình duyệt nào để chuyển đổi TXT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bạn có thể sử dụng bất kỳ trình duyệt web hiện đại nào, chẳng hạn như Google Chrome, Firefox, Opera hoặc Safari để chuyển đổi TXT sang PPSX trực tuyến. Tuy nhiên, nếu bạn đang phát triển ứng dụng dành cho máy tính để bàn, API chuyển đổi Aspose.Total TXT được khuyên dùng để xử lý trơn tru và hiệu quả.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}