---
title: Xóa chú thích PPSX trực tuyến hoặc quản lý chú thích bằng ứng dụng di động Android
description: xóa nhận xét khỏi tệp PPSX thông qua ứng dụng trực tuyến miễn phí.Mã API Android để quản lý nhận xét của tệp PPSX.

family: total
platformtag: Android
feature: Annotate
informat: PPSX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Xóa nhận xét từ bản trình bày PPSX trực tuyến hoặc quản lý qua ứng dụng Android" h2="Phát triển ứng dụng tiện ích chú thích bài thuyết trình PPSX dựa trên Android mạnh mẽ.Mã được liệt kê để quản lý nhận xét của tệp PPSX." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Xóa chú thích PPSX trực tuyến" %}}

1. Nhập file PPSX để xóa bình luận bằng cách upload lên
1. Thực hiện bằng cách nhấp vào bên trong vùng thả bằng cách kéo và thả ứng dụng chú thích
1. Tùy thuộc vào kích thước của tệp PPSX và tốc độ internet, hãy đợi trong vài giây
1. Nhấp vào nút 'Xóa' để xóa nhận xét
1. Tải tập tin ngay lập tức

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Xóa nhận xét bản trình bày PPSX qua ứng dụng Android" %}}

1. Thêm tham chiếu thư viện vào dự án Android
1. Tải PPSX qua đối tượng lớp Trình bày
1. Lặp lại qua từng Tác giả thông qua bộ sưu tập Presentation.getCommentAuthors()
1. Gọi phương thức clear() để xóa bình luận của nó
1. Cuối cùng gọi getCommentAuthors().clear() để loại bỏ tất cả tác giả
1. Gọi phương thức save để lưu file
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Mã: Xóa nhận xét và tác giả khỏi bản trình bày PPSX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Thêm nhận xét bản trình bày PPSX qua ứng dụng Android" %}}

1. Thêm tham chiếu thư viện vào dự án Android
1. Tải PPSX qua đối tượng lớp Trình bày
1. Gọi Presentation.getCommentAuthors().addAuthor(String, String) để thêm tác giả
1. Sử dụng ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date) để thêm bình luận
1. Gọi phương thức save để lưu file with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Mã: Thêm bình luận" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Phát triển ứng dụng Android chú thích tài liệu PPSX</h2>

Bạn cần phát triển ứng dụng hoặc tiện ích di động chú thích PPSX để cung cấp phản hồi, đưa ra đề xuất hoặc cộng tác với những người khác trên tài liệu?Với [Aspose.Slides for Android via Java](https://products.aspose.com/slides/vi/android-java/), API con của [Aspose.Total for Android via Java](https://products.aspose.com/total/vi/android-java/), bất kỳ nhà phát triển Android nào cũng có thể tích hợp mã API trên vào ứng dụng chú thích tài liệu của mình.Thư viện android mạnh mẽ cho phép lập trình bất kỳ giải pháp chú thích tài liệu nào.Hơn nữa, nó có thể hỗ trợ nhiều định dạng phổ biến bao gồm định dạng PPSX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Thư viện Android để chú thích các tệp PPSX" %}}

- Chúng tôi lưu trữ các gói Java của mình trong [Kho lưu trữ Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/). 
- Aspose.Slides for Java là một tệp JAR phổ biến chứa mã byte.
- Làm theo [hướng dẫn từng bước một](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository) về cách cài đặt Aspose.Slides for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

- J2SE 6.0 (Java 1.6) trở lên
- Gói Java đa nền tảng và chạy trên tất cả các hệ điều hành có triển khai JVM.

<br />
Để biết thêm chi tiết, vui lòng tham khảo [Tài liệu sản phẩm](https://docs.aspose.com/slides/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}