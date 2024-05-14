---
title: Távolítsa el a PDF Annotation Online-t vagy kezelje a kommentárokat az Android mobilalkalmazások segítségével
description: ingyenesen törölje a megjegyzéseket a PDF fájlból az online alkalmazáson keresztül.Android API kód a PDF fájlok megjegyzéseinek kezeléséhez.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Törölje a megjegyzéseket a PDF Document Online alkalmazásból, vagy kezelje az Android-alkalmazásokon keresztül" h2="Hatékony Android alapú PDF dokumentumannotációs segédprogram fejlesztése.A PDF fájl megjegyzéseinek kezeléséhez felsorolt kód." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Távolítsa el a PDF megjegyzéseket online" %}}

1. Importáljon PDF fájlt a megjegyzések feltöltésével való törléséhez
1. Ehhez kattintson a ledobási területen belülre a megjegyzés alkalmazás húzásával
1. A PDF fájl méretétől és az internet sebességétől függően várjon néhány másodpercet
1. Kattintson az "Eltávolítás" gombra a megjegyzések törléséhez
1. Azonnal töltse le a fájlt

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Távolítsa el a PDF-dokumentum megjegyzéseit az Android App API-n keresztül" %}}

1. Könyvtári hivatkozás hozzáadása az Android projekthez
1. Dokumentum betöltése a Dokumentum osztály objektumon keresztül
1. Válassza ki az adott oldalt a getPages().get_Item(Index)-n keresztül
1. Használja az AnnotationSelector-t, és kapja meg az összes szöveges megjegyzést a annotationSelector.getSelected()-on keresztül
1. Ismételje meg az egyes megjegyzéseket, és hívja meg a törlési metódust az eltávolításhoz.
1. Hívja a mentési módot a fájl mentéséhez.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód: Megjegyzések törlése a PDF fájlból" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Megjegyzés hozzáadása az Android App API-n keresztül" %}}

1. Könyvtári hivatkozás hozzáadása az Android projekthez
1. Dokumentum osztály objektum létrehozása
1. Adja hozzá az új oldalt és tartalmat a getPages().add() segítségével
1. Használja a TextAnnotation osztály getPages().get_Item(Index) elemét
1. Állítsa be a megfelelő megjegyzéseket, például címet, tárgyat, tartalmat stb
1. A megjegyzések hozzáadásához használja a getAnnotations().add-et
1. Hívja a mentési módot a megjegyzésekkel ellátott fájl mentéséhez
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód: PDF megjegyzés hozzáadása" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>PDF Document Annotation Android alkalmazás fejlesztése</h2>

Ki kell fejlesztenie egy PDF annotációs mobilalkalmazást vagy segédprogramot, amellyel visszajelzést adhat, javaslatokat tehet, vagy együttműködhet másokkal a dokumentummal kapcsolatban?A [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/hu/android-java/)-tal, amely a [Aspose.Total for Android via Java](https://products.aspose.com/total/hu/android-java/) gyermek API-ja, bármely Android-fejlesztő integrálhatja a fenti API-kódot a dokumentumjegyzet-alkalmazásába.A nagy teljesítményű android könyvtár lehetővé teszi bármilyen dokumentum-annotációs megoldás programozását.Ezenkívül számos népszerű formátumot támogat, beleértve a PDF formátumot.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android Library a PDF fájlok megjegyzéseivel" %}}

- Java csomagjainkat [Maven adattárak](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/)-ben tároljuk. 
- A Aspose.PDF for Java egy gyakori JAR-fájl, amely bájtkódot tartalmaz.
- Kövesse a [lépésről lépésre utasításokat](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository)-t a Aspose.PDF for Android via Java telepítéséhez.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

- Android API 31 és 32
- Android 4.0 és újabb
- Android Studio és SDK eszközök

<br />
Az opcionális csomagfüggőségekről, például a JogAmp JOGL-ről, a Harfbuzz font engine-ről, a Java Advanced Imaging JAI-ról további részletekért tekintse meg a [Termékdokumentáció](https://docs.aspose.com/pdf/java/system-requirements/)-at.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}