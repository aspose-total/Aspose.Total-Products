---
title: Android API ile Belge Dönüştürme 

description: Android dönüştürme API'sini kullanarak Word, Excel, PowerPoint, HTML, PDF ve Görüntü formatlarını dönüştürün. Android, Office docx, xlsx, pptx'i PDF'ye dönüştürür. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android API kullanarak Belge Dönüştürme" h2="Java aracılığıyla Aspose.Total for Android kullanarak Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Görüntüler ve diğer çeşitli formatları dönüştürün." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/), Android uygulamaları için başka bir yazılıma ihtiyaç duymadan belge dönüştürme ve yönetim çözümü sağlar. Programcılar, API'yi yeni geliştirilen uygulamalara veya mevcut uygulamalara entegre ederek belge yönetimi ve manipülasyon çözümünü kolayca otomatikleştirebilir. Programcı, API'yi entegre ederek, uygulama içinde çeşitli biçimlerdeki belgeleri oluşturmak, düzenlemek veya dönüştürmek için kolayca işlevsellik ekleyebilir. Android'deki PDF Converter API, Office DOCX, XLSX, PPTX'ten PDF'ye veya tam tersi gibi dönüştürme durumlarını işler. Ayrıca, API'nin sunduğu birkaç vaka aşağıda listelenmiştir ve ilgili dönüşüm vakaları için birkaç bağlantı verilmiştir. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PDF'yi CSV'ye Dönüştür" %}}
Total Android API, PDF'den Excel'e XLSX ve CSV dönüştürmeyi destekler. Bu iki aşamalı bir süreçtir. İki Toplam API [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) ve [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) dahil. İşlem, önce PDF'yi Excel XLSX biçimine, ardından XLSX'i CSV'ye çevirebilmenizdir. Daha ayrıntılı olarak, PDF dosyasını [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfı aracılığıyla yükleyin ve [kaydet](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) yöntemi. Ardından, oluşturulan XLSX belgesini [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak yükleyin ve [kaydet](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) öğesini çağırın yöntemi.

{{% blocks/products/pf/feature-page-code h3="Android - PDF'den Excel'e Dönüştürme" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Excel'den Word'e Dönüştürme" %}}
Android API, Excel dönüşümünü de yönetir. İşlem, EXCEL XLSX dosyasını [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak yükleyin ve SaveFormat'ı AUTO olarak ayarlayarak EXCEL'i PDF'ye dönüştürün. Ardından kaydedilen PDF dosyasını [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak yükleyin ve [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) öğesini çağırın Belgeyi Word DOC / DOCX biçiminde kaydetmek için  yöntemi.

{{% blocks/products/pf/feature-page-code h3="Android - Excel'den Word'e Dönüştürme" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="POWERPOINT'i HTML ve MHTML'ye Dönüştür" %}}
Android Total API, PowerPoint dosyaları da dahil olmak üzere çeşitli biçimlerle ilgilenir, böylece sunumları HTML ve MHTML'ye dönüştürebilir. İşlem, [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak POWERPOINT PPT/PPTX dosyasını yükleyin ve [kaydet](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) çağırın POWERPOINT'i HTML'ye dönüştürmek için  yöntemi. Ayrıca, Şimdi dönüştürülen HTML belgesini [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak yükleyin ve [kaydet](https://reference.aspose.com/cells/java/com.aspose.cells/) çağırın MHTML dönüştürme için  yöntemi. 
{{% blocks/products/pf/feature-page-code h3="Android - PowerPoint Slaytlarından HTML ve MHTML'ye Dönüştürme" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}