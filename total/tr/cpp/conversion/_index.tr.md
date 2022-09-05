---
title: C++ ile Belge Dönüştürme 
url: /tr/cpp/conversion/
description: C++ API kullanarak Word, Excel, PowerPoint, PDF, JSON, Görüntüler ve daha fazlası gibi çeşitli belge biçimlerini dönüştürün. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ kullanarak Belge Dönüştürme" h2="C++ kitaplığını kullanarak Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Görüntüler ve diğer çeşitli biçimleri dönüştürün." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Toplam C++ Kitaplığı](https://products.aspose.com/total/cpp/) belge dönüştürme sorununu çözer ve geliştiriciler, API'yi yeni geliştirilen uygulamalara veya mevcut uygulamalara entegre ederek belge yönetimi ve işleme çözümünü kolayca otomatikleştirebilir. C++ Programcıları, herhangi bir yazılıma ihtiyaç duymadan çözümlerinde çeşitli biçimlerdeki belgeleri oluşturma, düzenleme veya dönüştürme gibi işlevler ekleyebilir. txt'den PDF'ye, SVG'den PNG'ye, XLSX'ten CSV'ye, JSON'dan CSV'ye, Word'den PDF'ye, HTML'den PDF'ye gibi birkaç genel durum kolayca dönüştürülebilir. Ayrıca, API'nin sunduğu birkaç vaka aşağıda listelenmiştir ve ilgili dönüşüm vakaları için birkaç bağlantı verilmiştir. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word'ü Excel'e Dönüştür" %}}
Total C++ API, Microsoft Word DOC/DOCX'ten Excel'e dönüştürmeyi destekler.  İşlem, Word DOC / DOCX dosyasını [Belge](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıf referansını kullanarak yükleyin ve [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) üye işlevi öncelikle HTML'ye dönüştürülür. Ardından [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) sınıf referansını kullanarak HTML belgesini yükleyin ve [Kaydet](https://reference.aspose.com/) öğesini çağırın cell/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) belgeyi Excel biçiminde kaydetmek için üye işlevi. 

{{% blocks/products/pf/feature-page-code h3="C++ - Word'den Excel'e Dönüştürme" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF'den Word'e Dönüştürme" %}}
C++ dönüştürme kitaplığı ayrıca PDF'den Word'e DOC, DOCX ve diğer biçim dönüştürmelerini de destekler. PDF'yi RTF'ye dönüştürme durumu göz önüne alındığında, iki adımlı bir işlemdir, önce PDF'yi Word DOC/DOCX formatına dönüştürün ve ardından bunu RTF'ye dönüştürün. Bunun için dahil edilen adımlar, [Belge](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıf referansını kullanarak PDF dosyasını yükleme ve [Kaydet](https://reference.aspose) çağırma PDF'yi Word'e dönüştürmek için .com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) üye işlevi. Şimdi Aspose.Words API'sinin [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıf referansını kullanarak Word DOC / DOCX dosyasını tekrar yükleyin ve kullanarak RTF formatına kaydedin. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) üye işlevi.

{{% blocks/products/pf/feature-page-code h3="C++ - PDF'den Word'e Dönüştürme" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="JSON'u Word'e Dönüştür" %}}
JSON dönüşümü için C++ API, JSON'dan Word'e, Json'dan PowerPoint'e, Word'den JSON'a vb. gibi çeşitli kombinasyonları destekler. Word dönüştürme durumu göz önüne alındığında, Process is, yeni bir [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) nesnesi kullanarak dosyadan geçerli JSON verilerini okuyun ve ardından çağırın JSON'u PDF dosyası olarak kaydetmek için [Kaydet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) yöntemi. Şimdi [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıfını kullanarak kaydedilen dosyayı yükleyin ve [Kaydet](https://reference) kullanarak word belgesi biçiminde kaydedin .aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) yöntemi.
{{% blocks/products/pf/feature-page-code h3="C++ - JSON'dan Word'e Dönüştürme" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}