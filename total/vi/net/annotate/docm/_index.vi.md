---
title: Xóa chú thích DOCM trực tuyến hoặc quản lý chú thích qua .NET
description: xóa nhận xét khỏi tệp DOCM thông qua ứng dụng trực tuyến miễn phí.Mã .NET API để quản lý nhận xét của tệp DOCM.

family: total
platformtag: net
feature: Annotate
informat: DOCM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Xóa nhận xét từ tài liệu DOCM trực tuyến hoặc quản lý qua .NET" h2="Phát triển ứng dụng tiện ích chú thích tài liệu DOCM dựa trên .NET mạnh mẽ.Mã được liệt kê để quản lý nhận xét của tệp DOCM thông qua .NET." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Xóa chú thích DOCM trực tuyến" %}}

1. Nhập file DOCM để xóa bình luận bằng cách upload lên
1. Thực hiện bằng cách nhấp vào bên trong vùng thả bằng cách kéo và thả ứng dụng chú thích
1. Tùy thuộc vào kích thước của tệp DOCM và tốc độ internet, hãy đợi trong vài giây
1. Nhấp vào nút 'Xóa' để xóa nhận xét
1. Tải tập tin ngay lập tức

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Xóa nhận xét tài liệu DOCM của tác giả cụ thể qua .NET" %}}

1. Thêm tham chiếu thư viện vào dự án .NET
1. Tải tài liệu qua đối tượng lớp Tài liệu
1. Nhận tất cả các nhận xét về nút bằng cách sử dụng GetChildNodes có NodeType.Comment
1. Lặp lại tất cả các nhận xét và khớp với tên tác giả
1. Gọi phương thức Remove để xóa nhận xét của tác giả cụ thể

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Mã C#: Xóa nhận xét của tác giả cụ thể khỏi tệp DOCM" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Thêm nhận xét qua .NET" %}}

1. Tạo đối tượng lớp Tài liệu
1. Sử dụng lớp Bình luận
1. Thêm đoạn mới bằng Paragraphs.Add
1. Sử dụng FirstParagraph.Runs.Thêm phần thêm nhận xét
1. Hoặc cách khác là sử dụng các lớp CommentRangeStart và CommentRangeEnd
1. Gọi phương thức lưu để lưu tệp có thêm nhận xét

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Trích xuất tất cả các bình luận" %}}

1. Tải tài liệu qua đối tượng lớp Tài liệu
1. Tạo một đối tượng ArrayList
1. Nhận tất cả GetChildNodes trong NodeCollection
1. Lặp lại qua từng bộ sưu tập và thêm nhận xét trong ArrayList

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Mã .NET: Thêm nhận xét từ tệp DOCM" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: Trích xuất tất cả các bình luận" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Phát triển ứng dụng chú thích tài liệu DOCM qua .NET</h2>

Bạn cần phát triển ứng dụng hoặc tiện ích chú thích DOCM để cung cấp phản hồi, đưa ra đề xuất hoặc cộng tác với người khác trên tài liệu?Với [Aspose.Words for .NET](https://products.aspose.com/words/net/), API con của [Aspose.Total for .NET](https://products.aspose.com/total/net/), bất kỳ nhà phát triển .NET nào cũng có thể tích hợp mã API trên vào ứng dụng chú thích tài liệu của mình.Thư viện .NET mạnh mẽ cho phép lập trình bất kỳ giải pháp chú thích tài liệu nào.Hơn nữa, nó có thể hỗ trợ nhiều định dạng phổ biến bao gồm định dạng DOCM.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Thư viện .NET để chú thích các tệp DOCM" %}}

Có ba tùy chọn thay thế để cài đặt "Aspose.Words for .NET" hoặc "Aspose.Total for .NET" vào hệ thống của bạn.Vui lòng chọn một cái phù hợp với nhu cầu của bạn và làm theo hướng dẫn từng bước:<br /><br />

- Cài đặt [Gói NuGet](https://www.nuget.org/packages/Aspose.Words/). Xem [Tài liệu](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget)
- Cài đặt thư viện bằng [Bảng điều khiển quản lý gói](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) trong Visual Studio IDE
- Cài đặt thư viện bằng tay bằng [cài đặt cửa sổ](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

Sản phẩm của chúng tôi hoàn toàn đa nền tảng và hỗ trợ tất cả các triển khai .NET chính theo thông số kỹ thuật '.NET Standard 2.0':<br /><br />

- Microsoft .NET Framework, bắt đầu từ phiên bản 2.0 sớm nhất và kết thúc bằng '.NET Framework 4.8' mới nhất
- .NET Core, bắt đầu từ 2.0 sớm nhất và kết thúc bằng '.NET 6' mới nhất
- Đơn sắc >= 2.6.7
<br /><br />
Vì mã .NET không dựa vào phần cứng hoặc hệ điều hành cơ bản mà chỉ dựa trên Máy ảo, nên bạn có thể tự do phát triển bất kỳ loại phần mềm nào cho Windows, macOS, Android, iOS và Linux.Chỉ cần đảm bảo rằng bạn đã cài đặt phiên bản tương ứng của .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin.<br /><br />
Chúng tôi khuyên bạn nên sử dụng Microsoft Visual Studio, Xamarin và MonoDevelop IDE để tạo các ứng dụng C#, F#, VB.NET.
<br /><br />
Để biết thêm chi tiết, vui lòng tham khảo [Tài liệu sản phẩm](https://docs.aspose.com/words/net/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}
Các tệp DOCM (Tài liệu có Macro được kích hoạt) hỗ trợ tích hợp các macro để tự động hóa. Chú thích các tệp DOCM cung cấp ngữ cảnh cần thiết xung quanh các quy trình tự động, theo dõi các thay đổi được thực hiện bởi các macro và hỗ trợ xem xét cộng tác.

#### Chú thích Tệp DOCM cho các Trường Hợp Sử Dụng Cộng Tác với Tài Liệu Có Macro:

- **Tài Liệu Quy Trình Macro**  
  Chú thích các tài liệu có macro để giải thích mục đích của mỗi macro, kết quả dự kiến và vai trò của nó trong việc tự động hóa tài liệu.

- **Hướng Dẫn Người Dùng về Các Chức Năng Macro**  
  Thêm chú thích vào tài liệu để hướng dẫn người dùng về cách tương tác với các macro hoặc đầu vào cần thiết cho các hành động tự động.

- **Gỡ Lỗi và Theo Dõi Lỗi**  
  Chèn bình luận để làm nổi bật các phần mà các macro thất bại hoặc dữ liệu được nhập không chính xác, hỗ trợ trong việc gỡ lỗi.

- **Phản Hồi về Tự Động Hóa**  
  Cung cấp phản hồi về hiệu quả của các macro trong việc tự động hóa các nhiệm vụ tài liệu như tạo bảng, định dạng hoặc điền nội dung.

- **Xem Xét Nội Dung Tạo Bởi Macro**  
  Chú thích các khu vực nơi nội dung được tạo bởi các macro cần xem xét hoặc sửa đổi thủ công.
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="Câu hỏi thường gặp" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Câu hỏi thường gặp</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Tôi có thể sử dụng mã .NET ở trên trong ứng dụng của mình không?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Có, bạn có thể tải xuống mã này và sử dụng nó cho mục đích phát triển ứng dụng chú thích tài liệu dựa trên .NET.Mã này có thể phục vụ như một nguồn tài nguyên có giá trị để nâng cao chức năng và khả năng của các dự án của bạn trong lĩnh vực xử lý và thao tác tài liệu phụ trợ.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ứng dụng chú thích tài liệu trực tuyến này chỉ hoạt động trên Windows phải không?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bạn có thể linh hoạt bắt đầu chú thích tài liệu để xóa nhận xét trên bất kỳ thiết bị nào, bất kể nó chạy trên hệ điều hành nào, cho dù đó là Windows, Linux, Mac OS hay Android.Tất cả những gì cần thiết là một trình duyệt web hiện đại và kết nối Internet đang hoạt động.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Sử dụng ứng dụng trực tuyến để chú thích tài liệu DOCM có an toàn không?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Tất nhiên rồi! Các tệp đầu ra được tạo thông qua dịch vụ của chúng tôi sẽ được xóa khỏi máy chủ của chúng tôi một cách an toàn và tự động trong khung thời gian 24 giờ.Do đó, các liên kết hiển thị được liên kết với các tệp này sẽ ngừng hoạt động sau khoảng thời gian này.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Nên sử dụng App trên trình duyệt nào?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bạn có thể sử dụng bất kỳ trình duyệt web hiện đại nào như Google Chrome, Firefox, Opera hoặc Safari để chú thích tài liệu DOCM trực tuyến.Tuy nhiên, nếu bạn đang phát triển một ứng dụng dành cho máy tính để bàn, chúng tôi khuyên bạn nên sử dụng API xử lý tài liệu Aspose.Total để quản lý hiệu quả.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}