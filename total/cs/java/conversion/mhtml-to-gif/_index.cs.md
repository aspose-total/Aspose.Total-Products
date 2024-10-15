---
title: Online konverze MHTML na GIF nebo vývoj aplikace založené na Java pro konverzi souborů MHTML
description: Bezplatná online aplikace pro převod souborů MHTML na soubory GIF. Kód knihovny konverze Java pro dokumenty MHTML.  

family: total
platformtag: Java
feature: conversion
informat: MHTML
outformat: GIF
otherformats: DOT RTF ODT FLATOPC MARKDOWN PS WORDML PCL DOTM DOTX GIF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Online aplikace pro převod MHTML na GIF a kód Java pro převod souborů MHTML" h2="Vyvíjejte výkonnou aplikaci pro konverzi a export MHTML založenou na Javě.  Převeďte jeden nebo více souborů MHTML do formátu GIF a dalších formátů pomocí rozhraní Java automation API.  Zdarma převádějte soubory MHTML online prostřednictvím aplikace s okamžitým stažením." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Bezplatná online aplikace pro převod MHTML na GIF" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=gif&from=mhtml" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte MHTML na GIF soubory online pomocí aplikace App" %}}

1. Nahrajte soubory MHTML, které chcete převést
1. Počkejte několik sekund nebo déle v závislosti na velikosti MHTML
1. Sledujte stavový řádek nahrávání
1. Klikněte na tlačítko "Převést".
1. MHTML bude převeden na dokument GIF
1. Stáhněte si převedený soubor GIF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Převeďte MHTML na GIF pomocí Java Automation API" %}}


1. Otevřete soubor MHTML pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte MHTML na DOC pomocí [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Načtěte soubor DOC pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) třídy Aspose.Words
4. Uložte dokument do formátu GIF pomocí metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) a nastavte GIF jako SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kód Java pro konverzi MHTML na GIF" offSpacer="" %}}


```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.GIF
outputDocument.save("output.gif", SaveFormat.GIF);   
```



{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Několik dalších případů pro uložení MHTML do GIF s dalšími funkcemi, jako je Požadavky na převod, Otevřete dokument MHTML chráněný heslem přes Java.

{{% blocks/products/pf/feature-page-code %}}


```cs
// open encrypted document
Document document = new Document("input.mhtml", "password");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.GIF);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Vyvíjejte aplikaci pro konverzi souborů MHTML pomocí Javy</h2>

Potřebujete vyvinout softwarovou aplikaci založenou na Javě pro snadné ukládání a export souborů MHTML do dokumentu GIF?  S [Aspose.Total for Java](https://products.aspose.com/total/cs/java/) může každý vývojář Java integrovat výše uvedený kód API k naprogramování konverzní aplikace v různých formátech včetně Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, e-mailové soubory, obrázky. (JPG, PNG, BMP, GIF) a další formáty.  Výkonná Java knihovna pro konverzi dokumentů, podporuje mnoho oblíbených formátů včetně formátu MHTML.  Při exportu a vykreslování dokumentů do jiných formátů mohou programátoři používat podřízená API Aspose.Total for Java, včetně [Aspose.Words for Java](https://products.aspose.com/words/cs/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/cs/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/cs/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/cs/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/cs/java/) a dalších.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MHTML Knihovna konverzí pro Javu" %}}

Existují alternativní možnosti integrace Aspose.Total for Java do vašeho systému.  Vyberte si prosím ten, který odpovídá vašim potřebám, a postupujte podle pokynů krok za krokem:<br /><br />

- Použijte Aspose.Total for Java přímo z projektu založeného na Maven a zahrňte příslušné podřízené API do pom.xml.
- Alternativně lze získat soubor ZIP z [stahování](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Ukládání MHTML do GIF Požadavky na aplikaci" %}}

Jakýkoli operační systém, na kterém lze spustit Java Runtime Environment (JRE), může spouštět Aspose.Total for Java.  Následující seznam uvádí většinu, ale ne všechny podporované operační systémy.  <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS a další
- macOS: 10.9 (Mavericks) a novější
- Mobil: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}