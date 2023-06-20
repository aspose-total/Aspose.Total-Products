---
title: Konversi POTX ke ODT melalui C# .NET atau dengan Konverter Online gratis
description: Konversikan dokumen PowerPoint potx ke file dokumen Word dengan C#. Konversi banyak file dalam ASP.NET atau aplikasi .NET lainnya.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi POTX ke ODT menggunakan C# atau daring" h2="Bangun Presentasi POTX Microsoft PowerPoint ke aplikasi konversi dokumen Word ODT di .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin Platforms." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Cara Mengonversi POTX ke ODT Menggunakan C#" %}}

Untuk mengotomatiskan proses presentasi potx PowerPoint ke konversi batch file dokumen Word, kami akan menggunakan [Aspose.Slides for .NET](https://products.aspose.com/slides/net) dan [Aspose.Words untuk .NET](https://products.aspose.com/words/net) API. Yang pertama adalah API manipulasi presentasi PowerPoint yang memungkinkan Anda membuat atau memodifikasi slide Microsoft PowerPoint. Sedangkan yang terakhir adalah API pengolah kata untuk memproses atau memanipulasi dokumen Microsoft Word. Kedua API tersebut merupakan bagian dari paket [Aspose.Total for .NET](https://products.aspose.com/total/net). Anda dapat langsung [download](https://releases.aspose.com/) dari Nuget atau dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Perintah Konsol Manajer Paket" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengkonversi POTX ke ODT melalui C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Tambahkan referensi Aspose.Slides untuk .NET dan Aspose.Words untuk .NET
1. Muat presentasi PowerPoint POTX menggunakan kelas [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Simpan dokumen ke dalam Objek [MemoryStream](https://odts.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0)
1. Buat [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) dan inisialisasi dengan MemoryStream Object
1. Simpan dokumen menggunakan [Aspose.Words.Document.Save("output.odt", SaveFormat.Odt)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Platform .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin.
- Lingkungan pengembangan seperti Microsoft Visual Studio.
- Aspose.Slides untuk .NET dan Aspose.Words untuk .NET DLL yang dirujuk dalam proyek Anda.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Contoh kode ini menunjukkan cara mengonversi POTX ke ODT menggunakan C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint POTX file
Aspose.Slides.Presentation potx = new Aspose.Slides.Presentation("source.potx");

var stream = new MemoryStream();

potx.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var odt = new Aspose.Words.Document(stream);
      
// Save the Word ODT document
odt.Save("output.odt", Aspose.Words.SaveFormat.Odt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Konverter Online untuk POTX ke ODT</h3>

<iframe title="Alat Konversi potx ke odt Gratis" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=odt&from=potx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplikasi Gratis untuk Mengonversi POTX ke ODT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POTX file." >}}

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
                          <span itemprop="name"><b>Bagaimana cara mengonversi POTX ke ODT Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Aplikasi Online untuk konversi POTX terintegrasi di atas. Untuk menggunakan aplikasi ini, Anda dapat menambahkan file POTX dengan menyeret dan melepaskannya ke area yang ditentukan atau mengklik di dalam area untuk mengimpor file. Setelah file ditambahkan, klik tombol Konversi untuk memulai proses konversi. Setelah konversi POTX ke ODT selesai, Anda dapat mengunduh file yang baru dikonversi hanya dengan satu klik, dan itu akan tersedia dalam format ODT.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Berapa lama waktu yang diperlukan untuk mengonversi POTX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">konverter online ini cepat, tetapi kecepatan konversi POTX ke ODT terutama bergantung pada ukuran file POTX yang sedang dikonversi. File POTX yang lebih kecil dapat dirender ke dalam format ODT dalam hitungan detik. Selain itu, jika Anda telah mengintegrasikan kode konversi POTX ke ODT dalam aplikasi .NET, kecepatan konversi akan bergantung pada seberapa baik Anda mengoptimalkan aplikasi untuk proses konversi.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Apakah aman mengonversi POTX ke ODT menggunakan pengonversi Aspose.Total gratis?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Tentu saja! Setelah proses konversi POTX ke ODT selesai, tautan unduhan untuk file ODT yang dikonversi akan tersedia secara instan. Semua file yang diunggah, termasuk file POTX, dihapus dari sistem setelah 24 jam, dan tautan unduhan berhenti berfungsi setelah jangka waktu tersebut. Konverter online memastikan keamanan dan privasi file Anda, dan aplikasi terintegrasi tersedia gratis untuk tujuan pengujian. Ini memungkinkan pengguna untuk memeriksa hasilnya sebelum mengintegrasikan kode ke dalam proyek mereka.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Browser apa yang harus saya gunakan untuk mengonversi POTX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Anda dapat menggunakan browser web kontemporer apa pun seperti Google Chrome, Firefox, Opera, atau Safari untuk mengonversi file POTX ke ODT online. Namun, jika Anda membuat aplikasi desktop, Aspose.Total POTX Conversion API direkomendasikan untuk proses konversi yang lancar dan mulus.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}