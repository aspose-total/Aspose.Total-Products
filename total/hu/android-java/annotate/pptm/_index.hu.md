---
title: Távolítsa el a PPTM Annotation Online-t vagy kezelje a kommentárokat az Android mobilalkalmazások segítségével
description: ingyenesen törölje a megjegyzéseket a PPTM fájlból az online alkalmazáson keresztül.Android API kód a PPTM fájlok megjegyzéseinek kezeléséhez.

family: total
platformtag: Android
feature: Annotate
informat: PPTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Törölje a megjegyzéseket a PPTM online prezentációból, vagy kezelje az Android-alkalmazásokon keresztül" h2="Hatékony Android alapú PPTM prezentációs annotációs segédprogram fejlesztése.A PPTM fájl megjegyzéseinek kezeléséhez felsorolt kód." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Távolítsa el a PPTM megjegyzéseket online" %}}

1. Importáljon PPTM fájlt a megjegyzések feltöltésével való törléséhez
1. Ehhez kattintson a ledobási területen belülre a megjegyzés alkalmazás húzásával
1. A PPTM fájl méretétől és az internet sebességétől függően várjon néhány másodpercet
1. Kattintson az "Eltávolítás" gombra a megjegyzések törléséhez
1. Azonnal töltse le a fájlt

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Távolítsa el a PPTM prezentáció megjegyzéseit az Android alkalmazáson keresztül" %}}

1. Könyvtári hivatkozás hozzáadása az Android projekthez
1. PPTM betöltése a Presentation class objektumon keresztül
1. Ismételje meg az egyes szerzőket a Presentation.getCommentAuthors() gyűjtemény segítségével
1. A megjegyzés törléséhez hívja meg a clear() metódust
1. Végül hívja a getCommentAuthors().clear()-et az összes szerző eltávolításához
1. Hívja a mentési módot a fájl mentéséhez
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód : Megjegyzések és szerzők törlése a PPTM prezentációból" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="PPTM-bemutató megjegyzések hozzáadása az Android alkalmazáson keresztül" %}}

1. Könyvtári hivatkozás hozzáadása az Android projekthez
1. PPTM betöltése a Presentation class objektumon keresztül
1. A szerzők hozzáadásához hívja meg a Presentation.getCommentAuthors().addAuthor(String, String)-öt
1. Megjegyzések hozzáadásához használja a ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date)-ot
1. Hívja a mentési módot a fájl mentéséhez with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód: Megjegyzések hozzáadása" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>PPTM Document Annotation Android alkalmazás fejlesztése</h2>

PPTM annotációs mobilalkalmazást vagy segédprogramot szeretne fejleszteni, hogy visszajelzést adjon, javaslatokat tegyen, vagy együttműködjön másokkal a dokumentummal kapcsolatban?A [Aspose.Slides for Android via Java](https://products.aspose.com/slides/hu/android-java/)-tal, amely a [Aspose.Total for Android via Java](https://products.aspose.com/total/hu/android-java/) gyermek API-ja, bármely androidos fejlesztő integrálhatja a fenti API-kódot dokumentumannotáló alkalmazásába.A nagy teljesítményű android könyvtár lehetővé teszi bármilyen dokumentum-annotációs megoldás programozását.Ezenkívül számos népszerű formátumot támogat, beleértve a PPTM formátumot.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android Library a PPTM fájlok megjegyzéseivel" %}}

- Java csomagjainkat [Maven adattárak](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/)-ben tároljuk. 
- A Aspose.Slides for Java egy gyakori JAR-fájl, amely bájtkódot tartalmaz.
- Kövesse a [lépésről lépésre utasításokat](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository)-t a Aspose.Slides for Android via Java telepítéséhez.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

- J2SE 6.0 (Java 1.6) és újabb
- A Java csomag többplatformos, és minden JVM implementációval rendelkező operációs rendszeren fut.

<br />
További részletekért lásd a [Termékdokumentáció](https://docs.aspose.com/slides/java/system-requirements/)-at.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}