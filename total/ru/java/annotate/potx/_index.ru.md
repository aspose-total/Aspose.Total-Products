---
title: Удаление аннотаций POTX онлайн или управление аннотациями через Java
description: удалять комментарии из файла POTX через онлайн-приложение бесплатно.Код Java API для управления комментариями к файлам POTX.

family: total
platformtag: Java
feature: Annotate
informat: POTX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Удаление комментариев из презентации POTX онлайн или управление через Java" h2="Разработайте мощное приложение для создания аннотаций презентаций POTX на базе Java.Перечислен код для управления комментариями к файлу POTX через Java." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Удаление аннотаций POTX онлайн" %}}

1. Импортируйте файл POTX, чтобы удалить комментарии, загрузив его.
1. Сделайте это, щелкнув внутри области перетаскивания с помощью перетаскивания приложения аннотаций.
1. В зависимости от размера файла POTX и скорости интернета подождите несколько секунд.
1. Нажмите кнопку «Удалить», чтобы удалить комментарии.
1. Загрузите файл мгновенно

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Удаление комментариев к презентации POTX через Java" %}}

1. Добавить ссылку на библиотеку в проект Java
1. Загрузите POTX через объект класса Presentation
1. Перебрать каждого автора через коллекцию [Presentation.getCommentAuthors()](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#getCommentAuthors--).
1. Вызовите метод [clear()](https://reference.aspose.com/slides/java/com.aspose.slides/icommentcollection/#clear--), чтобы удалить комментарий.
1. Наконец, вызовите [getCommentAuthors().clear()](https://reference.aspose.com/slides/java/com.aspose.slides/commentauthorcollection/#clear--), чтобы удалить всех авторов.
1. Вызовите метод save, чтобы сохранить файл.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Пример кода на Java для удаления комментариев и авторов из презентации POTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Добавление комментариев к презентации POTX через Java" %}}

1. Добавить ссылку на библиотеку в проект Java
1. Загрузите POTX через объект класса Presentation
1. Вызов [Presentation.getCommentAuthors().addAuthor(String, String)](https://reference.aspose.com/slides/java/com.aspose.slides/ICommentAuthorCollection#addAuthor-java.lang.String-java.lang.String-), чтобы добавить авторов
1. Используйте [ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date)](https://reference.aspose.com/slides/java/com.aspose.slides/ICommentCollection#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) для добавления комментариев.
1. Вызовите метод save, чтобы сохранить файл. with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Java-код: добавление комментариев" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Разработка приложения аннотации документов POTX с помощью Java</h2>

Вам нужно разработать приложение или утилиту для аннотаций POTX, чтобы оставлять отзывы, вносить предложения или сотрудничать с другими людьми в работе над документом?Благодаря тому, что [Aspose.Slides for Java](https://products.aspose.com/slides/java/) является дочерним API [Aspose.Total for Java](https://products.aspose.com/total/java/), любой разработчик Java может интегрировать приведенный выше код API в свое приложение для аннотаций документов.Мощная библиотека Java позволяет программировать любое решение для аннотирования документов.Более того, он может поддерживать многие популярные форматы, включая формат POTX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Библиотека Java для аннотирования файлов POTX" %}}
Существуют альтернативные варианты установки «[Aspose.Slides for Java](https://products.aspose.com/slides/java/)» или «[Aspose.Total for Java](https://products.aspose.com/total/java/)» в вашу систему. Наш пакет Java разработан так, чтобы быть кроссплатформенным и совместимым с реализациями JVM в различных операционных системах, таких как Microsoft Windows, Linux, macOS, Android и iOS.Пожалуйста, выберите тот, который соответствует вашим потребностям, и следуйте пошаговым инструкциям:<br />

- Установить [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/)
- Или из [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/)
- Шаг за шагом [инструкции](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

- J2SE 6.0 (Java 1.6) и выше

<br />
Подробную информацию см. в формате [Документация продукта](https://docs.aspose.com/slides/java/system-requirements/#optional-dependencies).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="Часто задаваемые вопросы" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Часто задаваемые вопросы</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Могу ли я использовать приведенный выше код Java в своем приложении?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Да, вы можете загрузить этот код и использовать его для разработки приложения для аннотирования документов на основе Java.Этот код может служить ценным ресурсом для улучшения функциональности и возможностей ваших проектов в области внутренней обработки и манипулирования документами.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Это онлайн-приложение для аннотаций документов работает только в Windows?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">У вас есть возможность инициировать аннотирование документа для удаления комментариев на любом устройстве, независимо от того, в какой операционной системе оно работает, будь то Windows, Linux, Mac OS или Android.Все, что требуется, — это современный веб-браузер и активное подключение к Интернету.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Безопасно ли использовать онлайн-приложение для аннотирования документа POTX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Конечно! Выходные файлы, созданные с помощью нашей службы, будут безопасно и автоматически удалены с наших серверов в течение 24 часов.В результате по истечении этого периода отображаемые ссылки, связанные с этими файлами, перестанут работать.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>В каком браузере следует использовать приложение?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Вы можете использовать любой современный веб-браузер, например Google Chrome, Firefox, Opera или Safari, для онлайн-аннотаций документов POTX.Однако, если вы разрабатываете настольное приложение, мы рекомендуем использовать API обработки документов Aspose.Total для эффективного управления.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}