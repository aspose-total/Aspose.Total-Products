---
title: Konversi ODT ke PPSM melalui C# .NET atau dengan Konverter Online gratis
description: Konversikan dokumen dokumen Word ke file ppsm PowerPoint dengan C#. Konversi banyak file dalam ASP.NET atau aplikasi .NET lainnya.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi ODT ke PPSM menggunakan C# atau daring" h2="Bangun aplikasi konversi Microsoft Word ODT ke PowerPoint PPSM di .NET Framework, .NET Core, Windows Azure, Mono, atau Platform Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSM" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Cara Mengkonversi ODT ke PPSM Menggunakan C#" %}}

Untuk mengotomatiskan proses untuk file dokumen Word apa pun ke konversi batch presentasi PowerPoint ppsm, kami akan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net) dan [Aspose.Slides untuk .NET](https://products.aspose.com/slides/net) API. Yang pertama adalah API pengolah kata untuk memproses atau memanipulasi dokumen Microsoft Word. Sedangkan, yang terakhir adalah API manipulasi presentasi yang memungkinkan Anda membuat atau memodifikasi slide Microsoft PowerPoint. Kedua API tersebut merupakan bagian dari paket [Aspose.Total for .NET](https://products.aspose.com/total/net). Anda dapat langsung [download](https://releases.aspose.com/) dari Nuget atau dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Perintah Konsol Manajer Paket" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengkonversi ODT ke PPSM melalui C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Tambahkan referensi Aspose.Total untuk .NET
1. Muat file ODT menggunakan kelas [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Simpan dokumen ODT ke dalam HTML
1. Buat Objek [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Impor konten HTML dalam bingkai teks bentuk slide apa pun di dalam presentasi
1. Simpan dokumen menggunakan [Aspose.Slides.Presentation.Save("output.ppsm", SaveFormat.Ppsm)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Platform .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin.
- Lingkungan pengembangan seperti Microsoft Visual Studio.
- Aspose.Words untuk .NET &amp; Aspose.Slides untuk .NET DLL atau Aspose.Total untuk .NET DLL yang dirujuk dalam proyek Anda.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Contoh kode ini menunjukkan cara mengonversi ODT ke PPSM menggunakan C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word ODT file
Aspose.Words.Document odt = new Aspose.Words.Document("sourceWordFile.odt");

// Save ODT file to HTML 
odt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages ODT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPSM.

using (Presentation ppsm = new Presentation()){

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

	// Save the PPSM Presentation
	ppsm.Save("filepath\\pres.ppsm", Aspose.Slides.Export.SaveFormat.Ppsm);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Konverter Online untuk ODT ke PPSM</h3>

<iframe title="Alat Konversi odt ke ppsm Gratis" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=ppsm&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplikasi Gratis untuk Mengonversi ODT ke PPSM" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPSM file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Pertanyaan yang Sering Diajukan</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Bagaimana cara mengonversi ODT ke PPSM Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Aplikasi Online untuk konversi ODT terintegrasi di atas. Untuk menggunakan aplikasi ini, Anda dapat menambahkan file ODT dengan menyeret dan melepaskannya ke area putih yang ditentukan atau dengan mengklik di dalam area untuk mengimpor dokumen. Selanjutnya, tekan tombol Konversi untuk memulai proses konversi. Setelah konversi ODT ke PPSM selesai, Anda dapat mengunduh file yang baru dikonversi hanya dengan satu klik, dan itu akan tersedia untuk Anda dalam bentuk file PPSM.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Berapa lama waktu yang diperlukan untuk mengonversi ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Konverter online ini beroperasi dengan cepat tetapi terutama bergantung pada ukuran file ODT yang sedang dikonversi. Untuk file ODT kecil, konversi ke PPSM dapat diselesaikan dalam hitungan detik. Namun, jika Anda telah mengintegrasikan kode konversi dalam aplikasi .NET, kecepatan konversi akan bergantung pada seberapa baik aplikasi Anda dioptimalkan untuk proses konversi.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Apakah aman mengonversi ODT ke PPSM menggunakan pengonversi Aspose.Total gratis?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Tentu saja! Setelah konversi ODT ke PPSM selesai, tautan unduhan untuk file PPSM yang baru dikonversi akan tersedia secara instan. Ini juga menjamin keamanan proses konversi, karena semua file yang diunggah, termasuk file ODT, sepenuhnya aman dan akan dihapus dari sistem setelah 24 jam. Selanjutnya, tautan unduhan akan berhenti berfungsi setelah periode ini, memastikan privasi dan perlindungan file Anda. Aplikasi terintegrasi ini gratis untuk digunakan dan dirancang untuk tujuan pengujian sehingga pengguna dapat mengevaluasi hasilnya sebelum mengintegrasikan kode ke dalam proyek mereka.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Browser apa yang harus saya gunakan untuk mengonversi ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Anda dapat menggunakan browser web modern apa pun, seperti Google Chrome, Firefox, Opera, atau Safari, untuk konversi ODT ke PPSM online. Namun, jika Anda sedang mengembangkan aplikasi desktop, Aspose.Total ODT Conversion API direkomendasikan untuk pemrosesan yang lancar dan efisien.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}