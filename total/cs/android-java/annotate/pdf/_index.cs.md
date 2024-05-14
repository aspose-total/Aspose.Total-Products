---
title: Odeberte online anotaci PDF nebo spravujte anotace pomocí mobilních aplikací pro Android
description: odstranit komentáře ze souboru PDF prostřednictvím online aplikace zdarma.Android API kód pro správu komentářů souborů PDF.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Vymazat komentáře z dokumentu PDF Online nebo spravovat prostřednictvím aplikací pro Android" h2="Vyvíjejte výkonnou aplikaci pro anotaci dokumentů PDF pro Android.Uvedený kód pro správu komentářů souboru PDF." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Odebrat PDF Anotace online" %}}

1. Importujte soubor PDF a odstraňte komentáře jeho nahráním
1. Udělejte to kliknutím do oblasti přetažení pomocí aplikace pro anotaci přetažením
1. V závislosti na velikosti souboru PDF a rychlosti internetu počkejte několik sekund
1. Kliknutím na tlačítko 'Odebrat' komentáře vymažete
1. Stáhněte soubor okamžitě

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Odstraňte komentáře dokumentu PDF prostřednictvím rozhraní Android App API" %}}

1. Přidejte odkaz na knihovnu do projektu Android
1. Načíst dokument přes objekt třídy Document
1. Vyberte konkrétní stránku pomocí getPages().get_Item(Index)
1. Použijte AnnotationSelector a získejte všechny textové anotace přes annotationSelector.getSelected()
1. Projděte každou anotaci a voláním metody delete ji odstraňte.
1. Chcete-li soubor uložit, zavolejte metodu uložení.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód : Odstraňte komentáře ze souboru PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Přidejte anotaci přes Android App API" %}}

1. Přidejte odkaz na knihovnu do projektu Android
1. Vytvořit objekt třídy dokumentu
1. Přidejte novou stránku a obsah pomocí getPages().add()
1. Použijte getPages().get_Item(Index) třídy TextAnnotation
1. Nastavte příslušné anotace, jako je název, předmět, obsah atd
1. Pro přidání anotací použijte getAnnotations().add
1. Chcete-li soubor uložit s přidanými komentáři, zavolejte metodu uložení
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód : Přidat anotaci PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Vyvinout aplikaci pro Android Anotace dokumentu PDF</h2>

Potřebujete vyvinout anotační mobilní aplikaci nebo nástroj PDF, abyste mohli na dokumentu poskytovat zpětnou vazbu, návrhy nebo spolupráci s ostatními?S [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/cs/android-java/), podřízeným API [Aspose.Total for Android via Java](https://products.aspose.com/total/cs/android-java/), může každý vývojář Androidu integrovat výše uvedený kód API do své aplikace pro anotaci dokumentů.Výkonná knihovna pro Android umožňuje naprogramovat jakékoli řešení anotací dokumentů.Navíc může podporovat mnoho populárních formátů včetně formátu PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Knihovna Android pro anotaci souborů PDF" %}}

- Naše balíčky Java hostujeme v [Úložiště Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java je běžný soubor JAR obsahující bajtový kód.
- Postupujte podle [pokyny krok za krokem](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository), jak nainstalovat Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

- Android API 31 a 32
- Android 4.0 a vyšší
- Android Studio a nástroje SDK

<br />
Další podrobnosti o volitelných závislostech balíčků, jako je JogAmp JOGL, fontový engine Harfbuzz, Java Advanced Imaging JAI, najdete v [Produktová dokumentace](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}