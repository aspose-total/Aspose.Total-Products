---
title: Convertir PDF a EML en Python
description: Guarde PDF en EML dentro de las aplicaciones de Python sin usar Microsoft Word o Outlook

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierte PDF a EML usando Python" h2="Conversión de PDF a EML en sus aplicaciones Python sin instalar Microsoft Word<sup>&reg;</sup> o Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador de Python, ¿quién está tratando de agregar una función de conversión de PDF a EML dentro de la aplicación? La API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) puede ayudar a automatizar el proceso de conversión. Es un paquete completo de varias API que se ocupan de diferentes formatos, incluidos los formatos de correo electrónico, imágenes y Microsoft Word. Las API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) y [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) que forman parte del paquete [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) facilitan esta conversión con Python. Es un proceso de dos pasos, primero cargue el archivo PDF y transfiéralo a HTML a través de [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). En segundo lugar, cargue el HTML convertido usando [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) y guárdelo en formato EML.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir PDF a EML en Python" %}}

- Abra el archivo PDF de origen utilizando la clase [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Llame al método `save` mientras especifica la ruta del archivo HTML de salida y las opciones HTML Save relevantes como parámetro. Entonces su archivo PDF se convierte a HTML en la ruta especificada
- Ahora cargue el archivo HTML guardado usando MailMessage.load
- Llame al método de guardar con la ruta de archivo relevante. Así que finalmente el PDF se convierte

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

- Para la conversión de PDF a EML, se requiere Python 3.5 o posterior
- API de referencia dentro del proyecto directamente desde PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) y [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- O utilice el siguiente comando pip ```pip install aspose.words``` y ```pip install Aspose.Email-for-Python-via-NET``` 
- Además, el sistema operativo basado en Microsoft Windows o Linux (ver más para [Words](https://docs.aspose.com/words/python-net/system-requirements/) y [Email](https://docs.aspose.com/email/python-net/system-requirements/)) y para Linux verifique los requisitos adicionales para gcc y libpython y siga las instrucciones paso a paso [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Guardar PDF en EML en Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

La conversión de PDF a EML mediante APIs de Python ayuda a transformar documentos PDF en archivos de mensaje de correo electrónico estándar que pueden almacenarse, compartirse o importarse en sistemas de correo compatibles. Esto es valioso para preservar el contenido del documento en un formato orientado a mensajes para comunicación, respaldo e interoperabilidad.

Automatizar la conversión de PDF a EML mejora la eficiencia operativa al permitir la ingestión de documentos en archivos de correo electrónico, flujos de mensajería automatizados y sistemas de procesamiento masivo. Soporta el intercambio de datos escalable donde se requiere una salida estructurada de archivos de correo.

{{% blocks/products/pf/agp/feature-section-col title="Casos de Uso Clave" %}}

* **Generación de Archivos de Correo**  
  Convertir documentos PDF en archivos EML para almacenamiento, transferencia o entrega posterior.

* **Flujos de Trabajo de Archivo**  
  Preservar el contenido del documento en un formato estándar compatible con correo electrónico para la conservación de registros.

* **Integración con Sistemas de Correo**  
  Preparar el contenido derivado de PDF para importarlo en clientes de correo y sistemas de procesamiento.

* **Reutilización de Contenido**  
  Reformatear la información del PDF en archivos de mensaje estructurados para flujos de trabajo de comunicación digital.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Escenarios de Automatización" %}}

* **Creación por Lotes de Archivos de Correo**  
  Los scripts automatizados pueden convertir grandes volúmenes de PDFs en archivos EML para uso posterior.

* **Canales de Ingesta de Archivos**  
  Los sistemas pueden dirigir las salidas EML convertidas a almacenamiento o repositorios de cumplimiento.

* **Preparación Automatizada de Mensajes**  
  El contenido del PDF puede prepararse programáticamente como archivos de correo para revisión o envío posterior.

* **Transformación de Documento a Mensaje**  
  Los flujos de trabajo en Python pueden convertir dinámicamente PDFs entrantes en activos EML reutilizables.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}