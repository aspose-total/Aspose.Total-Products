---
title: Java API pro export PS do MARKDOWN
description: Převeďte PS na MARKDOWN pomocí on premise Java API
url_ignore: /cs/java/conversion/ps-to-markdown/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: MARKDOWN
otherformats: MARKDOWN RTF DOT OTT FLATOPC DOTM WORDML MHTML DOTX ODT XAMLFLOW PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformujte PS na MARKDOWN přes Java" h2="On Premise Java API pro vykreslení PS do MARKDOWN bez použití jakékoli aplikace třetí strany" >}}
{{% blocks/products/pf/feature-page-summary %}}
PS můžete převést na MARKDOWN pomocí dvou jednoduchých kroků. Nejprve musíte vykreslit soubor PS do DOC pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Poté můžete pomocí výkonného API pro zpracování dokumentů [Aspose.Words for Java](https://products.aspose.com/words/java/) převést DOC na MARKDOWN. Obě rozhraní API jsou součástí balíčku [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API pro převod PS na MARKDOWN" %}}
1. Otevřete soubor PS pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte PS na DOC pomocí [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Načtěte soubor DOC pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) třídy Aspose.Words
4. Uložte dokument do formátu MARKDOWN pomocí metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) a nastavte MARKDOWN jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) ve vašem pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Při převodu PS na MARKDOWN, i když je váš dokument chráněn heslem, jej stále můžete otevřít pomocí rozhraní API pro manipulaci s PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Chcete-li otevřít zašifrovaný soubor, musíte vytvořit objekt [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) a otevřít PS pomocí hesla vlastníka.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otevřete dokument PS chráněný heslem přes Java" %}}
Při ukládání vstupního dokumentu do formátu souboru MARKDOWN můžete také dokument uložit do databáze namísto systému souborů. Možná budete muset implementovat ukládání a načítání objektů Document do az databáze. To by bylo nutné, pokud byste implementovali jakýkoli typ systému pro správu obsahu. Aby bylo možné uložit váš MARKDOWN do databáze, je často nutné dokument serializovat a získat tak bajtové pole. To lze provést pomocí rozhraní API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Po získání bajtového pole jej můžete uložit do databáze pomocí příkazu SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MARKDOWN);
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

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

Převádění souborů PS (PostScript) do formátu MARKDOWN (.md) umožňuje použití textového a grafického obsahu PostScriptu ve formátech vhodných pro web. Markdown je ideální pro dokumentaci, znalostní báze, blogy a repozitáře projektů založených na Gitu.

{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}

* Přeměna manuálů a zpráv ve formátu PS na webové dokumenty v Markdownu.
* Převod diagramů a tabulek do formátů podporovaných v Markdownu pro dokumentaci.
* Publikování technického obsahu založeného na PS na GitHubu nebo interních wikách.
* Příprava tutoriálů, průvodců nebo akademických poznámek z souborů PS v Markdownu.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}

* Automatický převod PS do Markdownu v dokumentačních potrubích.
* Integrace do generátorů statických stránek pro technologické blogy a znalostní portály.
* Hromadné zpracování pro převod archivů PS do repozitářů Markdown.
* Extrahování obsahu z PS s asistencí AI pro výstupy připravené pro Markdown.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}