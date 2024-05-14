---
title: Xóa chú thích DOTX trực tuyến hoặc quản lý chú thích bằng ứng dụng di động Android
description: xóa nhận xét khỏi tệp DOTX thông qua ứng dụng trực tuyến miễn phí.Mã API Android để quản lý nhận xét của tệp DOTX.

family: total
platformtag: Android
feature: Annotate
informat: DOTX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Xóa nhận xét từ tài liệu DOTX trực tuyến hoặc quản lý qua ứng dụng Android" h2="Phát triển ứng dụng tiện ích chú thích tài liệu DOTX dựa trên Android mạnh mẽ.Mã được liệt kê để quản lý nhận xét của tệp DOTX." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Xóa chú thích DOTX trực tuyến" %}}

1. Nhập file DOTX để xóa bình luận bằng cách upload lên
1. Thực hiện bằng cách nhấp vào bên trong vùng thả bằng cách kéo và thả ứng dụng chú thích
1. Tùy thuộc vào kích thước của tệp DOTX và tốc độ internet, hãy đợi trong vài giây
1. Nhấp vào nút 'Xóa' để xóa nhận xét
1. Tải tập tin ngay lập tức

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Xóa nhận xét tài liệu DOTX qua ứng dụng Android" %}}

1. Thêm tham chiếu thư viện vào dự án Android
1. Tải tài liệu qua đối tượng lớp Tài liệu
1. Nhận tất cả nhận xét từ tất cả các nút bằng cách sử dụng [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) và NodeType.COMMENT
1. Gọi phương thức [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) để xóa tất cả bình luận
1. Gọi phương thức save để lưu file.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Mã: Xóa nhận xét khỏi tệp DOTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Xóa và thêm bình luận DOTX" %}}

1. Thêm tham chiếu thư viện vào dự án Android
1. Tải tài liệu qua đối tượng lớp Tài liệu
1. Nhận bình luận bằng getChild
1. Sử dụng [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) để xóa câu trả lời được chỉ định cho nhận xét này
1. Sử dụng [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) để thêm bất kỳ câu trả lời nào cho nhận xét này
1. Gọi phương thức save để lưu file

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Thêm nhận xét qua ứng dụng Android" %}}

1. Thêm tham chiếu thư viện vào dự án Android
1. Tạo đối tượng lớp Tài liệu
1. Sử dụng [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) để tạo bình luận
1. Sử dụng getParagraphs().add và getFirstParagraph().getRuns().add
1. Gọi phương thức save để lưu file with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Mã: Xóa và thêm phản hồi nhận xét từ tệp DOTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Mã: Thêm bình luận" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Phát triển ứng dụng Android chú thích tài liệu DOTX</h2>

Bạn cần phát triển ứng dụng hoặc tiện ích di động chú thích DOTX để cung cấp phản hồi, đưa ra đề xuất hoặc cộng tác với những người khác trên tài liệu?Với [Aspose.Words for Android via Java](https://products.aspose.com/words/vi/android-java/), API con của [Aspose.Total for Android via Java](https://products.aspose.com/total/vi/android-java/), bất kỳ nhà phát triển Android nào cũng có thể tích hợp mã API trên vào ứng dụng chú thích tài liệu của mình.Thư viện android mạnh mẽ cho phép lập trình bất kỳ giải pháp chú thích tài liệu nào.Hơn nữa, nó có thể hỗ trợ nhiều định dạng phổ biến bao gồm định dạng DOTX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Thư viện Android để chú thích các tệp DOTX" %}}

- Chúng tôi lưu trữ các gói Java của mình trong [Kho lưu trữ Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Aspose.Words for Java là một tệp JAR phổ biến chứa mã byte.
- Làm theo [hướng dẫn từng bước một](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) về cách cài đặt Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

- Java SE 7 và các phiên bản Java mới hơn được hỗ trợ.
- Gói riêng cho Java SE 6 trong trường hợp một gói bắt buộc phải sử dụng JRE đã lỗi thời.
- Gói Java đa nền tảng và chạy trên tất cả các hệ điều hành có triển khai JVM.
- Các hệ điều hành bao gồm Microsoft Windows, Linux, macOS, Android và iOS.

<br />
Để biết thêm chi tiết về các gói phụ thuộc tùy chọn, chẳng hạn như JogAmp JOGL, công cụ phông chữ Harfbuzz, JAI hình ảnh nâng cao Java, vui lòng tham khảo [Tài liệu sản phẩm](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}