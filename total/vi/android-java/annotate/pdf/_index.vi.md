---
title: Xóa chú thích PDF trực tuyến hoặc quản lý chú thích bằng ứng dụng di động Android
description: xóa nhận xét khỏi tệp PDF thông qua ứng dụng trực tuyến miễn phí.Mã API Android để quản lý nhận xét của tệp PDF.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Xóa nhận xét từ tài liệu PDF trực tuyến hoặc quản lý qua ứng dụng Android" h2="Phát triển ứng dụng tiện ích chú thích tài liệu PDF dựa trên Android mạnh mẽ.Mã được liệt kê để quản lý nhận xét của tệp PDF." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Xóa chú thích PDF trực tuyến" %}}

1. Nhập file PDF để xóa bình luận bằng cách upload lên
1. Thực hiện bằng cách nhấp vào bên trong vùng thả bằng cách kéo và thả ứng dụng chú thích
1. Tùy thuộc vào kích thước của tệp PDF và tốc độ internet, hãy đợi trong vài giây
1. Nhấp vào nút 'Xóa' để xóa nhận xét
1. Tải tập tin ngay lập tức

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Xóa nhận xét tài liệu PDF qua API ứng dụng Android" %}}

1. Thêm tham chiếu thư viện vào dự án Android
1. Tải tài liệu qua đối tượng lớp Tài liệu
1. Chọn trang cụ thể qua getPages().get_Item(Index)
1. Sử dụng AnnotationSelector và nhận tất cả chú thích văn bản qua annotationSelector.getSelected()
1. Lặp lại qua từng chú thích và gọi phương thức xóa để xóa nó.
1. Gọi phương thức save để lưu file.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Mã: Xóa nhận xét khỏi tệp PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Thêm chú thích qua API ứng dụng Android" %}}

1. Thêm tham chiếu thư viện vào dự án Android
1. Tạo đối tượng lớp Tài liệu
1. Thêm trang và nội dung mới bằng getPages().add()
1. Sử dụng getPages().get_Item(Index) của lớp TextAnnotation
1. Đặt các chú thích có liên quan như tiêu đề, chủ đề, nội dung, v.v.
1. Sử dụng getAnnotations().add để thêm chú thích
1. Gọi phương thức lưu để lưu tệp có thêm nhận xét
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Mã: Thêm chú thích PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Phát triển ứng dụng Android chú thích tài liệu PDF</h2>

Bạn cần phát triển ứng dụng hoặc tiện ích di động chú thích PDF để cung cấp phản hồi, đưa ra đề xuất hoặc cộng tác với những người khác trên tài liệu?Với [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/vi/android-java/), API con của [Aspose.Total for Android via Java](https://products.aspose.com/total/vi/android-java/), bất kỳ nhà phát triển Android nào cũng có thể tích hợp mã API trên vào ứng dụng chú thích tài liệu của mình.Thư viện android mạnh mẽ cho phép lập trình bất kỳ giải pháp chú thích tài liệu nào.Hơn nữa, nó có thể hỗ trợ nhiều định dạng phổ biến bao gồm định dạng PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Thư viện Android để chú thích các tệp PDF" %}}

- Chúng tôi lưu trữ các gói Java của mình trong [Kho lưu trữ Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java là một tệp JAR phổ biến chứa mã byte.
- Làm theo [hướng dẫn từng bước một](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) về cách cài đặt Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

- API Android 31 và 32
- Android 4.0 trở lên
- Công cụ Android Studio và SDK

<br />
Để biết thêm chi tiết về các gói phụ thuộc tùy chọn, chẳng hạn như JogAmp JOGL, công cụ phông chữ Harfbuzz, JAI hình ảnh nâng cao Java, vui lòng tham khảo [Tài liệu sản phẩm](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}