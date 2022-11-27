---
title: Bestand maken met Python 

description: Maak tekst- en Microsoft Word-documenten zonder Microsoft Office te installeren 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Documenten maken met Python" h2="Maak tekst- en Microsoft Word DOCX-, DOC-bestanden in Python-toepassingen zonder Microsoft Office<sup>&reg;</sup> te installeren." >}}

{{% blocks/products/pf/feature-page-summary %}}
Het opslaan van gegevens is de basis van elke softwaretoepassing, afhankelijk van de aard van de toepassing. De opslaglocatie kan de database, XML, JSON, tekstbestanden, Excel-rapporten of Microsoft Word-documenten zijn. Bestands-I/O is het onderdeel van elke taal en meestal ondersteunen talen, waaronder Python, het schrijven van gegevens naar tekstbestanden. Laten we eens kijken naar de Python-taal. Bestaande tekstbestanden schrijven met Python, het biedt een open, schrijf en sluitmethode voor deze taken. Open eerst het bestand met het relevante bestandspad en voeg een functie toe of schrijf deze als argumenten. Schrijf vervolgens de vereiste tekst in het bestand en sluit het bestand tot slot met de methode close(). 

Voor het maken van Microsoft Word-documenten met Python gebruiken we het [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) APIs-pakket dat de [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API als onderdeel van het pakket bevat. Deze API biedt een volledige documentautomatiseringsoplossing voor facturen, rapporten en technische artikelen. Procedure voor het maken van een Word-document hieronder vermeld.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Hoe maak je een tekstbestand aan met Python" %}}

Het maken van en schrijven naar tekstbestanden is eenvoudig. Python biedt de open()-methode met drie parameters en moet een van de parameters samen met het bestandspad gebruiken. Drie parameters zijn "x", "a" en "w". Door "x" op te geven, wordt een nieuw bestand gemaakt, maar er wordt een fout gegenereerd in het geval dat het bestand al bestaat. Door "a" op te geven, wordt een nieuw tekstbestand gemaakt als het niet bestaat en als het bestaat, wordt de inhoud aan het einde toegevoegd. En als laatste "w" verstrekkend, wordt er een nieuw tekstdocument gemaakt en overschreven met de nieuwe inhoud voor het geval deze al bestaat.

{{% blocks/products/pf/feature-page-code h3="Python - Tekstbestand maken" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word-documenten maken" %}}

Total Python Word API heeft meerdere functies, waaronder het maken van Microsoft Word-bestanden, het invoegen van afbeeldingen en tekst in documenten, het toevoegen van tabellen en lijsten binnen de bestanden en het eenvoudig wijzigen van bestaande documenten. Als u een Microsoft Word-documentproces wilt maken, maakt u het object van de klassen [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) en [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/). Voeg de gewenste tekst, alinea, lijsten en tabellen toe aan het document en sla het tenslotte op.

{{% blocks/products/pf/feature-page-code h3="Python - Microsoft Word-documenten maken" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Creëren">}}