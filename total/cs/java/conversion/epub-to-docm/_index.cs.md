---
title: Java API pro export EPUB do DOCM
description: Převeďte EPUB na DOCM pomocí on premise Java API
url_ignore: /cs/java/conversion/epub-to-docm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: DOCM
otherformats: ODT WORDML MARKDOWN RTF PCL XAMLFLOW DOTX PS DOT OTT MHTML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformujte EPUB na DOCM přes Java" h2="On Premise Java API pro vykreslení EPUB do DOCM bez použití jakékoli aplikace třetí strany" >}}
{{% blocks/products/pf/feature-page-summary %}}
EPUB můžete převést na DOCM pomocí dvou jednoduchých kroků. Nejprve musíte vykreslit soubor EPUB do DOC pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Poté můžete pomocí výkonného API pro zpracování dokumentů [Aspose.Words for Java](https://products.aspose.com/words/java/) převést DOC na DOCM. Obě rozhraní API jsou součástí balíčku [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API pro převod EPUB na DOCM" %}}
1. Otevřete soubor EPUB pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte EPUB na DOC pomocí [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Načtěte soubor DOC pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) třídy Aspose.Words
4. Uložte dokument do formátu DOCM pomocí metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) a nastavte DOCM jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) ve vašem pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Při převodu EPUB na DOCM, i když je váš dokument chráněn heslem, jej stále můžete otevřít pomocí rozhraní API pro manipulaci s PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Chcete-li otevřít zašifrovaný soubor, musíte vytvořit objekt [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) a otevřít EPUB pomocí hesla vlastníka.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otevřete dokument EPUB chráněný heslem přes Java" %}}
Při ukládání vstupního dokumentu do formátu souboru DOCM můžete také dokument uložit do databáze namísto systému souborů. Možná budete muset implementovat ukládání a načítání objektů Document do az databáze. To by bylo nutné, pokud byste implementovali jakýkoli typ systému pro správu obsahu. Aby bylo možné uložit váš DOCM do databáze, je často nutné dokument serializovat a získat tak bajtové pole. To lze provést pomocí rozhraní API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Po získání bajtového pole jej můžete uložit do databáze pomocí příkazu SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOCM);
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
Převod **EPUB na DOCM** je velmi cenný pro generování **makro-povolených dokumentů Word** z digitálních publikací. Soubory DOCM umožňují integraci automatizačních skriptů a maker, což umožňuje zjednodušit zpracování dokumentů, zlepšit interaktivitu a vytvářet inteligentní pracovní postupy pro publikování. Transformací e-knih do formátu DOCM mohou vydavatelé, akademici a podniky optimalizovat reporting, zabezpečit digitální práva a automatizovat složité úkoly spojené s obsahem.

{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}
- **Automatizované pracovní postupy pro publikování** – Zjednodušte redakční a produkční procesy obsahu.
- **Automatizace dokumentů ve výzkumu** – Generujte strukturované zprávy s vestavěnými makry.
- **Akademický obsah s makry** – Vytvářejte interaktivní studijní materiály a automatizované analytické nástroje.
- **Dokumenty pro správu digitálních práv** – Bezpečně distribuujte obsah e-knih s automatizovanými ovládacími prvky.
- **Generování podnikových zpráv** – Vytvářejte dynamické, makro-povolené zprávy z dat publikací.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}
- **Potrubí EPUB na DOCM** – Automatizujte převod e-knih do makro-povolených souborů Word.
- **Automatické vytváření makro-povolených dokumentů** – Okamžitě generujte soubory DOCM s vlastními skripty.
- **Hromadný převod e-knih do formátu Word** – Efektivně zpracovávejte velké digitální knihovny.
- **Automatizace publikování řízená pracovním postupem** – Integrujte generování souborů DOCM do systémů pro obsah podniku.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}