---
title: Odeberte online anotaci ODP nebo spravujte anotace pomocí mobilních aplikací pro Android
description: odstranit komentáře ze souboru ODP prostřednictvím online aplikace zdarma.Android API kód pro správu komentářů souborů ODP.

family: total
platformtag: Android
feature: Annotate
informat: ODP
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Vymazat komentáře z ODP Presentation Online nebo spravovat prostřednictvím aplikací pro Android" h2="Vyvíjejte výkonnou prezentační anotační aplikaci ODP pro Android.Uvedený kód pro správu komentářů souboru ODP." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Odebrat ODP Anotace online" %}}

1. Importujte soubor ODP a odstraňte komentáře jeho nahráním
1. Udělejte to kliknutím do oblasti přetažení pomocí aplikace pro anotaci přetažením
1. V závislosti na velikosti souboru ODP a rychlosti internetu počkejte několik sekund
1. Kliknutím na tlačítko 'Odebrat' komentáře vymažete
1. Stáhněte soubor okamžitě

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Odstraňte komentáře k prezentaci ODP prostřednictvím aplikace pro Android" %}}

1. Přidejte odkaz na knihovnu do projektu Android
1. Načtěte ODP přes objekt třídy Presentation
1. Iterujte každého autora prostřednictvím kolekce Presentation.getCommentAuthors()
1. Vyvoláním metody clear() smažete její komentář
1. Nakonec zavolejte getCommentAuthors().clear() a odstraňte všechny autory
1. Chcete-li soubor uložit, zavolejte metodu uložení
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód : Smazat komentáře a autory z prezentace ODP" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Přidejte komentáře k prezentaci ODP prostřednictvím aplikace pro Android" %}}

1. Přidejte odkaz na knihovnu do projektu Android
1. Načtěte ODP přes objekt třídy Presentation
1. Chcete-li přidat autory, vyvolejte Presentation.getCommentAuthors().addAuthor(String, String)
1. Pro přidávání komentářů použijte ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date)
1. Chcete-li soubor uložit, zavolejte metodu uložení with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód: Přidávání komentářů" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Vyvinout aplikaci pro Android Anotace dokumentu ODP</h2>

Potřebujete vyvinout anotační mobilní aplikaci nebo nástroj ODP, abyste mohli poskytovat zpětnou vazbu, navrhovat nebo spolupracovat s ostatními na dokumentu?S [Aspose.Slides for Android via Java](https://products.aspose.com/slides/cs/android-java/), podřízeným API [Aspose.Total for Android via Java](https://products.aspose.com/total/cs/android-java/), může každý vývojář Androidu integrovat výše uvedený kód API do své aplikace pro anotaci dokumentů.Výkonná knihovna pro Android umožňuje naprogramovat jakékoli řešení anotací dokumentů.Navíc může podporovat mnoho populárních formátů včetně formátu ODP.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Knihovna Android pro anotaci souborů ODP" %}}

- Naše balíčky Java hostujeme v [Úložiště Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/). 
- Aspose.Slides for Java je běžný soubor JAR obsahující bajtový kód.
- Postupujte podle [pokyny krok za krokem](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository), jak nainstalovat Aspose.Slides for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

- J2SE 6.0 (Java 1.6) a vyšší
- Balíček Java je multiplatformní a běží na všech operačních systémech s implementací JVM.

<br />
Další podrobnosti naleznete v [Produktová dokumentace](https://docs.aspose.com/slides/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}