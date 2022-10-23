---
title: Skapa fil med Python 
url: /sv/python-net/create/
description: Skapa text- och Microsoft Word-dokument utan att installera Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Skapa dokument med Python" h2="Skapa text- och Microsoft Word DOCX-, DOC-filer i Python-applikationer utan att installera Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Att lagra data är grunden för alla program beroende på programmets karaktär. Lagringsplatsen kan vara databasen, XML, JSON, textfiler, Excel-rapporter eller Microsoft Word-dokument. Fil I/O är en del av alla språk och mestadels språk inklusive Python stöder skrivning av data till textfiler. Låt oss överväga Python-språket. Skriver befintliga textfiler med Python, det ger öppna, skriv och stäng metod för dessa uppgifter. Öppna först filen med relevant sökväg och lägg till eller skriv funktion som argument. Skriv sedan den önskade texten i filen och stäng till sist filen med metoden close(). 

För att skapa Microsoft Word-dokument med Python använder vi [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) APIs-paket som har [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API som en del av sitt paket. Detta API tillhandahåller fullständig dokumentautomatiseringslösning för fakturor, rapporter och tekniska artiklar. Procedur för skapande av word-dokument som anges nedan.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Hur man skapar en textfil med Python" %}}

Det är enkelt att skapa och skriva till textfiler. Python tillhandahåller open()-metoden med tre parametrar och måste använda en av parametrarna tillsammans med filsökvägen. Tre parametrar är "x", "a" och "w". Genom att ange "x" kommer en ny fil att skapas men ger ett felmeddelande om filen redan finns. Genom att ange "a" kommer en ny textfil att skapas om den inte finns och om den finns kommer innehåll att läggas till i slutet. Och slutligen med "w", kommer ett nytt textdokument att skapas och skrivas över med det nya innehållet om det redan finns.

{{% blocks/products/pf/feature-page-code h3="Python - Skapa textfil" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa Microsoft Word-dokument" %}}

Total Python Word API har flera funktioner inklusive skapande av Microsoft Word-filer, infoga bilder och text i dokument, lägga till tabeller och listor i filerna samt modifiera befintliga dokument med lätthet. För att skapa en Microsoft Word-dokumentprocess, skapa objektet för klasserna [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) och [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/). Lägg till önskad text, stycke, listor och tabeller i dokumentet och spara det slutligen.

{{% blocks/products/pf/feature-page-code h3="Python - Skapa Microsoft Word-dokument" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}