---
title: Chuyển đổi định dạng JSON sang DOC trong Android qua Java
description: Phân tích cú pháp JSON thành DOC trong Java mà không cần sử dụng Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOC
otherformats: DOT RTF EPUB WORD FLATOPC DOCM ODT MOBI PS OTT DOTX WORDML CHM PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi định dạng JSON thành DOC trong các ứng dụng Android" h2="Phân tích cú pháp JSON thành DOC trong các ứng dụng Android mà không cần sử dụng Microsoft <sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi JSON thành DOC trong các ứng dụng Android của mình theo quy trình hai bước. Thứ nhất, bằng cách sử dụng API xử lý bảng tính mạnh mẽ [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), bạn có thể phân tích cú pháp JSON thành PDF. Trong bước thứ hai, bạn có thể chuyển đổi PDF sang DOC bằng cách sử dụng API xử lý văn bản [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Cả hai API đều thuộc họ sản phẩm [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang DOC trong Android qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) mới đối tượng và đọc dữ liệu JSON hợp lệ từ tệp
2. Nhập tệp JSON vào trang tính bằng cách sử dụng lớp [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) và [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) nó dưới dạng PDF
3. Tải tài liệu PDF bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng DOC bằng cách sử dụng [Lưu](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) phương pháp
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt thư viện trong ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục & chuyển đổi định dạng JSON thành DOC trong Android qua Java" %}}
Hơn nữa, API cho phép bạn đặt các tùy chọn bố cục cho định dạng JSON của mình trong khi phân tích cú pháp JSON thành DOC bằng [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý Mảng dưới dạng bảng, bỏ qua giá trị rỗng, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày tháng, đặt định dạng ngày và số và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi định dạng JSON sang DOC với Watermark trong Android qua Java" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành DOC với hình mờ. Để thêm hình mờ vào tài liệu DOC của bạn, trước tiên bạn có thể phân tích cú pháp tệp JSON thành PDF và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PDF mới được tạo bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), tạo một phiên bản của TextWatermarkOptions và đặt thuộc tính của nó, Gọi phương thức Watermark.setText và chuyển văn bản & đối tượng hình mờ của TextWatermarkOptions. Sau khi thêm hình mờ, bạn có thể lưu tài liệu vào DOC.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-dot/" name="JSON Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-rtf/" name="JSON Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-epub/" name="JSON Đến EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-word/" name="JSON Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-flatopc/" name="JSON Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-docm/" name="JSON Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-odt/" name="JSON Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-mobi/" name="JSON Đến MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-ps/" name="JSON Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-ott/" name="JSON Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-dotx/" name="JSON Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-wordml/" name="JSON Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-doc/" name="JSON Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/json-to-pcl/" name="JSON Đến PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}