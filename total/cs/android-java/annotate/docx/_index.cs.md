---
title: Odeberte online anotaci DOCX nebo spravujte anotace pomocí mobilních aplikací pro Android
description: odstranit komentáře ze souboru DOCX prostřednictvím online aplikace zdarma.Android API kód pro správu komentářů souborů DOCX.

family: total
platformtag: Android
feature: Annotate
informat: DOCX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Vymazat komentáře z dokumentu DOCX Online nebo spravovat prostřednictvím aplikací pro Android" h2="Vyvíjejte výkonnou aplikaci pro anotaci dokumentů DOCX pro Android.Uvedený kód pro správu komentářů souboru DOCX." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Odebrat DOCX Anotace online" %}}

1. Importujte soubor DOCX a odstraňte komentáře jeho nahráním
1. Udělejte to kliknutím do oblasti přetažení pomocí aplikace pro poznámky
1. V závislosti na velikosti souboru DOCX a rychlosti internetu počkejte několik sekund
1. Kliknutím na tlačítko 'Odebrat' komentáře vymažete
1. Stáhnout soubor okamžitě

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Odstraňte komentáře dokumentu DOCX prostřednictvím aplikace pro Android" %}}

1. Přidejte odkaz na knihovnu do projektu Android
1. Načíst dokument přes objekt třídy Document
1. Získejte všechny komentáře ze všech uzlů pomocí [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) a NodeType.COMMENT
1. Chcete-li odstranit všechny komentáře, použijte metodu [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear)
1. Chcete-li soubor uložit, zavolejte metodu uložení.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód : Odstraňte komentáře ze souboru DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Odebrat a přidat komentář DOCX Odpověď" %}}

1. Přidejte odkaz na knihovnu do projektu Android
1. Načíst dokument přes objekt třídy Document
1. Získejte komentář pomocí getChild
1. Použijte [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) pro odstranění zadané odpovědi na tento komentář
1. Pro přidání jakékoli odpovědi na tento komentář použijte [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String)
1. Chcete-li soubor uložit, zavolejte metodu uložení

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Přidejte komentáře prostřednictvím aplikace pro Android" %}}

1. Přidejte odkaz na knihovnu do projektu Android
1. Vytvořit objekt třídy dokumentu
1. K vytvoření komentáře použijte [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/)
1. Použijte getParagraphs().add a getFirstParagraph().getRuns().add
1. Chcete-li soubor uložit, zavolejte metodu uložení with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód : Odebrat a přidat komentář Odpověď ze souboru DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Kód: Přidávání komentářů" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Vyvinout aplikaci pro Android Anotace dokumentu DOCX</h2>

Potřebujete vyvinout anotační mobilní aplikaci nebo nástroj DOCX, abyste mohli poskytovat zpětnou vazbu, navrhovat nebo spolupracovat s ostatními na dokumentu?S [Aspose.Words for Android via Java](https://products.aspose.com/words/cs/android-java/), podřízeným API [Aspose.Total for Android via Java](https://products.aspose.com/total/cs/android-java/), může každý vývojář Androidu integrovat výše uvedený kód API do své aplikace pro anotaci dokumentů.Výkonná knihovna pro Android umožňuje naprogramovat jakékoli řešení anotací dokumentů.Navíc může podporovat mnoho populárních formátů včetně formátu DOCX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Knihovna Android pro anotaci souborů DOCX" %}}

- Naše balíčky Java hostujeme v [Úložiště Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Aspose.Words for Java je běžný soubor JAR obsahující bajtový kód.
- Postupujte podle [pokyny krok za krokem](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/), jak nainstalovat Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

- Jsou podporovány Java SE 7 a novější verze Java.
- Samostatný balíček pro Java SE 6 v případě, že je nutné používat zastaralé JRE.
- Balíček Java je multiplatformní a běží na všech operačních systémech s implementací JVM.
- Operační systémy zahrnují Microsoft Windows, Linux, macOS, Android a iOS.

<br />
Další podrobnosti o volitelných závislostech balíčků, jako je JogAmp JOGL, fontový engine Harfbuzz, Java Advanced Imaging JAI, najdete v [Produktová dokumentace](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}