---
title: Odeberte online anotaci XLSX nebo spravujte anotace pomocí mobilních aplikací pro Android
description: odstranit komentáře ze souboru XLSX prostřednictvím online aplikace zdarma.Android API kód pro správu komentářů souborů XLSX.

family: total
platformtag: Android
feature: Annotate
informat: XLSX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Vymazat komentáře z dokumentu XLSX Online nebo spravovat prostřednictvím aplikací pro Android" h2="Vyvíjejte výkonnou aplikaci pro anotaci dokumentů XLSX pro Android.Uvedený kód pro správu komentářů souboru XLSX." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Odebrat XLSX Anotace online" %}}

1. Importujte soubor XLSX a odstraňte komentáře jeho nahráním
1. Udělejte to kliknutím do oblasti přetažení pomocí aplikace pro poznámky
1. V závislosti na velikosti souboru XLSX a rychlosti internetu počkejte několik sekund
1. Kliknutím na tlačítko 'Odebrat' komentáře vymažete
1. Stáhněte soubor okamžitě

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Odstraňte komentáře dokumentu XLSX prostřednictvím rozhraní Android App API" %}}

1. Přidejte odkaz na knihovnu do projektu Android
1. Načíst dokument prostřednictvím objektu třídy Workbook
1. Vyberte konkrétní pracovní list
1. Získejte všechny komentáře z používání [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)
1. Získejte všechny Threaded komentáře přes getThreadedComments
1. K odstranění komentářů a autorů použijte funkci removeAt
1. Chcete-li soubor uložit, zavolejte metodu uložení
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód : Odstraňte komentáře z dokumentu XLSX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Aktualizujte podprocesové komentáře XLSX" %}}

1. Načíst dokument prostřednictvím objektu třídy Workbook
1. Získejte konkrétní pracovní list
1. Získejte vláknový komentář pomocí getComments().getThreadedComments(Index).get(Index)
1. Pro aktualizaci komentáře použijte metodu setNotes
1. Chcete-li soubor uložit, zavolejte metodu uložení

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Přidejte komentáře přes Android App API" %}}

1. Vytvořte dokument prostřednictvím objektu třídy Workbook
1. Získejte konkrétní pracovní list
1. Přidejte index komentářů přes getComments().add
1. Pro přidání komentáře použijte metodu setNotes
1. Chcete-li soubor uložit, zavolejte metodu uložení with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód : Aktualizujte tématický komentář souboru XLSX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Kód: Přidávání komentářů" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Vyvinout aplikaci pro Android Anotace dokumentu XLSX</h2>

Potřebujete vyvinout anotační aplikaci nebo nástroj XLSX pro Android, abyste mohli poskytovat zpětnou vazbu, navrhovat nebo spolupracovat s ostatními na dokumentu?S [Aspose.Cells for Android via Java](https://products.aspose.com/cells/cs/android-java/), podřízeným API [Aspose.Total for Android via Java](https://products.aspose.com/total/cs/android-java/), může každý vývojář Androidu integrovat výše uvedený kód API do své aplikace pro anotaci dokumentů.Výkonná knihovna pro Android umožňuje naprogramovat jakékoli řešení anotací dokumentů.Navíc může podporovat mnoho populárních formátů včetně formátu XLSX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API pro anotaci souborů XLSX" %}}

- Naše balíčky Java hostujeme v [Úložiště Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/). 
- Aspose.Cells for Java je běžný soubor JAR obsahující bajtový kód.
- Postupujte podle [pokyny krok za krokem](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository), jak nainstalovat Aspose.Cells for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

- Android OS 2.0 nebo vyšší.
- Balíček Java je multiplatformní a běží na všech operačních systémech s implementací JVM.

<br />
Další podrobnosti naleznete v [Produktová dokumentace](https://docs.aspose.com/cells/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}