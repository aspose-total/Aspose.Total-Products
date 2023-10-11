---
title: Sök i dokument via C# .NET 

description: Sök i dokument inklusive PDF, Microsoft Office Excel, Word, PowerPoint och mer via din .NET-applikation. Sök efter dokument online via app.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Sök i dokument med .NET API:er" h2="Sök och hämta enkelt data från ett brett utbud av dokument, som omfattar Microsoft Office Word, Excel, PowerPoint och PDF-filer på ett mycket effektivt sätt med Aspose.Total för .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

Genom att möjliggöra textsökning och innehållsindexering för olika dokumentfilformat ger användarna möjlighet att optimera produktiviteten, effektivisera datahämtning och förbättra informationshanteringen i organisationer och applikationer. Förbättra funktionaliteten hos din .NET-baserade programvara eller system genom att möjliggöra textbaserade sökningar i dokument och upprätta index för effektiv hämtning av information från en mängd olika dokumentfilformat.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Viktiga skäl att söka i dokument" %}}

1. Dokumentorganisation
1. Informationsinhämtning
1. Innehållsvalidering 
1. Sammanfattning av innehåll 
1. Textanalys
1. Dataextraktion 
1. Dokumentindexering 


{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Sök i PDF-dokument" %}}

Vi använder [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), ett underordnat API till [Aspose.Total for .NET](https://products.aspose.com/total/net/) som är designat för särskilda dokumentmanipuleringsfunktioner samt uppgifter i samband med hämtning och sökning av dokumentinnehåll. Nedanstående kodavsnitt är skrivet i C# för att interagera med ett PDF-dokument. Det skapar först ett reguljärt uttrycksmönster för att söka efter sekvenser av tecken som inte är blanksteg i dokumentet. Därefter kommer den åt den första sidan i PDF:en och använder en TextFragmentAbsorber för att söka efter text på den sidan med det angivna reguljära uttrycket. Koden samlar sedan de upptäckta textfragmenten till en samling. Slutligen itererar den genom denna samling och matar ut varje identifierat textfragment till konsolen. I huvudsak fungerar detta kodavsnitt som en mekanism för att extrahera och visa specifika textmönster från ett PDF-dokument. Dessutom stöder .NET Search API även Microsoft [Sök i Word-dokument](https://products.aspose.com/total/net/search/word/) och andra format.

{{% blocks/products/pf/feature-page-code h3="C#-kod för PDF-dokumentsökning" %}}

{{< gist "aspose-com-gists" "3c806eb023f399cd402ab922a247f2d0" "pdf-document-search.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}