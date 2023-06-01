---
title: Java kullanarak XLS'yi WORD'ye dönüştürün veya ücretsiz Çevrimiçi Dönüştürücü ile
description: Excel veya Word kullanarak XLS'yi WORD'a Dışa Aktarmak için Java API veya çevrimiçi veya çevrimiçi. Kodu entegre etmeden önce ücretsiz CSV'den DOC'e çevrimiçi dönüştürücüyü hızlı bir şekilde test edin.
url_ignore: /tr/java/conversion/xls-to-word/
family: total
platformtag: net
feature: conversion
informat: XLS
outformat: WORD
otherformats: POWERPOINT PPTX WORD WORDX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XLS'yi WORD'a Dışa Aktarmak için Java API veya çevrimiçi" h2="Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
XLS'yi WORD'ye işlemek iki adımlı bir işlemdir. Verilen XLS belgesini PDF'ye dönüştürmek için önce [Aspose.Cells for Java](https://products.aspose.com/cells/java) API'sini ve ardından [Aspose.Pdf for Java](https) kullanacaksınız. ://products.aspose.com/pdf/java) API ile PDF belgenizi kolayca WORD'a dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) dosya formatı otomasyon kitaplıklarının koleksiyonuna dahildir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API ile XLS'yi WORD'ye Dönüştürme" %}}
1. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak XLS dosyasını açın
2. XLS'yi PDF'ye dönüştürün ve SaveFormat'ı AUTO olarak ayarlayın
3. Dönüştürülen PDF dosyasını [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) kullanarak WORD biçiminde kaydedin-) yöntemi ve Word'u SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kullanmanız gerekir. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in WORD format
document.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>XLS'den WORD'e Çevrimiçi Dönüştürücü</h3>

<iframe title="xls'dan docx'ye Çevrimiçi Dönüştürme Aracı" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xls" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xls-to-docx/">XLS'den WORD'e dönüştürme için ücretsiz uygulamamızı deneyin</a></p>
</div></div>
</div></div>
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
              <h2>Sıkça Sorulan Sorular</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>XLS'yi Çevrimiçi WORD'e nasıl dönüştürebilirim?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">XLS dönüştürme için Çevrimiçi Uygulama yukarıda entegre edilmiştir. Dönüştürme işlemi, XLS dosyanızı beyaz alana sürükleyip bırakarak veya dosyayı içe aktarmak için alanın içine tıklayarak eklemeyi içerir. Dosya eklendikten sonra, dönüştürme işlemini başlatmak için Dönüştür düğmesini tıklamanız yeterlidir. Tamamlandığında, yeni dönüştürülen WORD dosyanızı tek bir tıklamayla indirebilirsiniz.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>XLS'yi dönüştürmek ne kadar sürer?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bu çevrimiçi dönüştürücünün hızı büyük ölçüde dönüştürülmekte olan XLS dosyasının boyutuna göre belirlenir. Daha küçük XLS dosyaları sadece birkaç saniye içinde WORD'e dönüştürülebilir. Ek olarak, dönüştürme kodunu bir Java uygulamasına dahil ettiyseniz, uygulamanın verimliliği de dönüştürme sürecini etkileyecektir.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ücretsiz Aspose.Total dönüştürücü kullanarak XLS'yi WORD'e dönüştürmek güvenli midir?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Elbette! Dönüştürme işlemi tamamlandıktan sonra, WORD dosyası için bir indirme bağlantısı hemen kullanıma sunulacaktır. Yüklenen dosyalar 24 saat sonra otomatik olarak silinir ve indirme bağlantıları bu süreden sonra aktif olmaz. Dosyalarınızın güvende olduğundan ve XLS dahil dosya dönüştürmenin tamamen güvenli olduğundan emin olabilirsiniz. Ücretsiz uygulama, öncelikle test amacıyla entegre edilmiştir ve kodu projenize entegre etmeden önce sonuçları doğrulamanıza olanak tanır.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>XLS'yi dönüştürmek için hangi tarayıcıyı kullanmalıyım?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Çevrimiçi dönüştürme için Google Chrome, Firefox, Opera veya Safari gibi herhangi bir modern web tarayıcısını kullanabilirsiniz. Ancak, bir masaüstü uygulaması geliştiriyorsanız Aspose.Total XLS Conversion API, bu tür ortamlarda sorunsuz çalışacak şekilde tasarlandığından mükemmel bir seçimdir.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}