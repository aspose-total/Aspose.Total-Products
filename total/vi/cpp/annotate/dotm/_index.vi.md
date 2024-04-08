---
title: Xóa chú thích DOTM trực tuyến hoặc quản lý chú thích qua C++
description: xóa nhận xét khỏi tệp DOTM thông qua ứng dụng trực tuyến miễn phí. Mã API C++ để quản lý nhận xét của tệp DOTM.

family: total
platformtag: cpp
feature: Annotate
informat: DOTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Xóa nhận xét từ tài liệu DOTM trực tuyến hoặc quản lý qua C++" h2="Phát triển ứng dụng tiện ích chú thích tài liệu DOTM dựa trên C++ mạnh mẽ. Mã được liệt kê để quản lý nhận xét của tệp DOTM thông qua C++." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Xóa chú thích DOTM trực tuyến" %}}

1. Nhập file DOTM để xóa bình luận bằng cách upload lên
1. Thực hiện bằng cách nhấp vào bên trong vùng thả bằng cách kéo và thả ứng dụng chú thích
1. Tùy thuộc vào kích thước của tệp DOTM và tốc độ internet, hãy đợi trong vài giây
1. Nhấp vào nút 'Xóa' để xóa nhận xét
1. Tải tập tin ngay lập tức

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Xóa nhận xét tài liệu DOTM qua C++" %}}

1. Thêm tham chiếu thư viện vào dự án C++
1. Tải tệp DOTM
1. Nhận tất cả các nút bằng cách sử dụng GetChildNodes có tham số NodeType::Comment
1. Gọi NodeCollection.Clear trên bộ sưu tập nhận xét

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Mã C++: Xóa nhận xét khỏi tệp DOTM" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "remove-word-document-comments.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Thêm nhận xét qua C++" %}}

1. Tạo đối tượng lớp Document và DocumentBuilder
1. Hoặc Tải tài liệu
1. Sử dụng lớp Comment để thêm bình luận
1. Sử dụng phương thức AppendChild với tham số nhận xét obj
1. Sử dụng phương pháp có liên quan như get_Paragraphs()->Add
1. Hoặc cách khác là sử dụng các lớp CommentRangeStart và CommentRangeEnd
1. Gọi phương thức lưu để lưu tệp có thêm nhận xét

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Trích xuất tất cả các bình luận" %}}

1. Tải tài liệu qua đối tượng lớp Tài liệu
1. Nhận tất cả GetChildNodes trong NodeCollection
1. Lặp lại qua từng bộ sưu tập và thu thập thông tin về chúng

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Mã C++: Thêm nhận xét vào tệp DOTM" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "word-document-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Code: Trích xuất tất cả các bình luận" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Phát triển ứng dụng chú thích tài liệu DOTM bằng C++</h2>

Bạn cần phát triển ứng dụng hoặc tiện ích chú thích DOTM để cung cấp phản hồi, đưa ra đề xuất hoặc cộng tác với người khác trên tài liệu?Với [Aspose.Words for C++](https://products.aspose.com/words/cpp/), API con của [Aspose.Total for C++](https://products.aspose.com/total/vi/cpp/), bất kỳ nhà phát triển C++ nào cũng có thể tích hợp mã API trên vào ứng dụng chú thích tài liệu của mình.Thư viện C++ mạnh mẽ cho phép lập trình bất kỳ giải pháp chú thích tài liệu nào.Hơn nữa, nó có thể hỗ trợ nhiều định dạng phổ biến bao gồm định dạng DOTM.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Thư viện C++ để chú thích các tệp DOTM" %}}

Có ba tùy chọn để cài đặt Aspose.Words for C++ vào môi trường nhà phát triển của bạn.Vui lòng chọn một cái phù hợp với nhu cầu của bạn và làm theo hướng dẫn từng bước:<br /><br />

- Install a [Gói NuGet](https://www.nuget.org/packages/Aspose.Words.Cpp/). See [Tài liệu](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- Cài đặt thư viện bằng [Bảng điều khiển quản lý gói](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) trong Visual Studio IDE
- Cài đặt thư viện bằng tay bằng [cài đặt cửa sổ](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}
Bạn có thể sử dụng thư viện C++ này để phát triển phần mềm trên hệ điều hành Microsoft Windows, Linux và macOS:<br /><br />

- GCC >= 6.3.0 và Clang >= 3.9.1 là bắt buộc đối với Linux
- Cần có Xcode >= 12.5.1, Clang và libc++ cho macOS

<br /><br />
Nếu bạn phát triển phần mềm cho Linux hoặc macOS, vui lòng kiểm tra thông tin về các phụ thuộc thư viện bổ sung (gói nguồn mở fontconfig và mesa-glu) trong [Tài liệu sản phẩm](https://docs.aspose.com/words/cpp/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

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
                          <span itemprop="name"><b>Tôi có thể sử dụng mã C++ ở trên trong ứng dụng của mình không?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Có, bạn có thể tải xuống mã này và sử dụng nó cho mục đích phát triển ứng dụng chú thích tài liệu dựa trên C++.Mã này có thể phục vụ như một nguồn tài nguyên có giá trị để nâng cao chức năng và khả năng của các dự án của bạn trong lĩnh vực xử lý và thao tác tài liệu phụ trợ.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ứng dụng chú thích tài liệu trực tuyến này chỉ hoạt động trên Windows phải không?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bạn có thể linh hoạt bắt đầu chú thích tài liệu để xóa nhận xét trên bất kỳ thiết bị nào, bất kể nó chạy trên hệ điều hành nào, cho dù đó là Windows, Linux, Mac OS hay Android. Tất cả những gì cần thiết là một trình duyệt web hiện đại và kết nối Internet đang hoạt động.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Sử dụng ứng dụng trực tuyến để chú thích tài liệu DOTM có an toàn không?</b></span>
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
                          <span itemprop="text">Bạn có thể sử dụng bất kỳ trình duyệt web hiện đại nào như Google Chrome, Firefox, Opera hoặc Safari để chú thích tài liệu DOTM trực tuyến.Tuy nhiên, nếu bạn đang phát triển một ứng dụng dành cho máy tính để bàn, chúng tôi khuyên bạn nên sử dụng API xử lý tài liệu Aspose.Total để quản lý hiệu quả.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}