---
title: Konvertera POTM till TXT via C# .NET eller med gratis Online Converter
description: Konvertera PowerPoint potm-dokument till Word-txt-filer med C#. Konvertera flera filer inom ASP.NET eller andra .NET-program.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera POTM till TXT med C# eller online" h2="Bygg Microsoft PowerPoint POTM-presentation till Word TXT-dokumentkonverteringsappar på .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTM" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Hur man konverterar POTM till TXT med C#" %}}

För att automatisera processen för en PowerPoint potm-presentation till Word txt-filer batchkonvertering kommer vi att använda [Aspose.Slides for .NET](https://products.aspose.com/slides/net) och [Aspose.Words för .NET](https://products.aspose.com/words/net) API:er. Det förstnämnda är ett API för PowerPoint-presentationsmanipulering som låter dig skapa eller ändra Microsoft PowerPoint-bilder. Medan det senare är ett ordbehandlings-API för bearbetning eller manipulering av Microsoft Word-dokument. Båda API:erna är en del av paketet [Aspose.Total for .NET](https://products.aspose.com/total/net). Du kan [ladda ner](https://releases.aspose.com) direkt från Nuget eller kan använda följande kommandon från pakethanterarens konsol.

{{% blocks/products/pf/agp/code-block title="Pakethanterarens konsolkommando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera POTM till TXT via C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Lägg till referens för Aspose.Slides för .NET och Aspose.Words för .NET
1. Ladda PowerPoint POTM-presentation med klassen [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Spara dokumentet i [MemoryStream](https://txts.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) Object
1. Skapa [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) och initialisera det med MemoryStream Object
1. Spara dokumentet med [Aspose.Words.Document.Save("output.txt", SaveFormat.Txt)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar.
- Utvecklingsmiljö som Microsoft Visual Studio.
- Aspose.Slides för .NET och Aspose.Words för .NET DLL som refereras till i ditt projekt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Detta kodexempel visar hur man konverterar en POTM till TXT med C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint POTM file
Aspose.Slides.Presentation potm = new Aspose.Slides.Presentation("source.potm");

var stream = new MemoryStream();

potm.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var txt = new Aspose.Words.Document(stream);
      
// Save the Word TXT document
txt.Save("output.txt", Aspose.Words.SaveFormat.Txt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class="demobox tc col-md-12 padding-0" align="center">
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Online-omvandlare för POTM till TXT</h3>

<iframe title="potm till txt Conversion Online Tool" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=txt&from=potm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app för att konvertera POTM till TXT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POTM file." >}}

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
              <h2>Vanliga frågor</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Hur kan jag konvertera POTM till TXT Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Online-app för POTM-konvertering är integrerad ovan. För att använda appen kan du lägga till din POTM-fil genom att antingen dra och släppa den i det angivna området eller klicka inuti området för att importera filen. När filen har lagts till klickar du på knappen Konvertera för att initiera konverteringsprocessen. När POTM till TXT-konverteringen är klar kan du ladda ner din nyligen konverterade fil med bara ett klick, och den kommer att vara tillgänglig i TXT-format.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Hur lång tid tar det att konvertera POTM?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">denna online-omvandlare är snabb, men hastigheten på POTM till TXT-konverteringen beror huvudsakligen på storleken på POTM-filen som konverteras. Mindre POTM-filer kan renderas till TXT-format inom några sekunder. Dessutom, om du har integrerat POTM till TXT-konverteringskoden i en .NET-applikation, kommer konverteringshastigheten att bero på hur väl du har optimerat din applikation för konverteringsprocessen.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Är det säkert att konvertera POTM till TXT med gratis Aspose.Total-omvandlare?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Självklart! När POTM till TXT-konverteringsprocessen är klar kommer nedladdningslänken för den konverterade TXT-filen att vara tillgänglig omedelbart. Alla uppladdade filer, inklusive POTM-filer, raderas från systemet efter 24 timmar, och nedladdningslänkarna upphör att fungera efter denna tidsperiod. Onlinekonverteraren säkerställer säkerheten och integriteten för dina filer, och den integrerade appen är tillgänglig utan kostnad för teständamål. Detta tillåter användare att kontrollera resultatet innan de integrerar koden i sina projekt.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Vilken webbläsare ska jag använda för att konvertera POTM?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Du kan använda vilken modern webbläsare som helst som Google Chrome, Firefox, Opera eller Safari för att konvertera POTM-filer till TXT online. Men om du skapar ett skrivbordsprogram rekommenderas Aspose.Total POTM Conversion API för en smidig och sömlös konverteringsprocess.</span>
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