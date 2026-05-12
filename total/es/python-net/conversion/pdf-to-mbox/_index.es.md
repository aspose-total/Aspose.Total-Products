---
title: Convertir PDF a MBOX en Python
description: Guarde PDF en MBOX dentro de las aplicaciones de Python sin usar Microsoft Word o Outlook

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierte PDF a MBOX usando Python" h2="Conversión de PDF a MBOX en sus aplicaciones Python sin instalar Microsoft Word<sup>&reg;</sup> o Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador de Python, ¿quién está tratando de agregar una función de conversión de PDF a MBOX dentro de la aplicación? La API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) puede ayudar a automatizar el proceso de conversión. Es un paquete completo de varias API que se ocupan de diferentes formatos, incluidos los formatos de correo electrónico, imágenes y Microsoft Word. Las API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) y [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) que forman parte del paquete [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) facilitan esta conversión con Python. Es un proceso de dos pasos, primero cargue el archivo PDF y transfiéralo a HTML a través de [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). En segundo lugar, cargue el HTML convertido usando [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) y guárdelo en formato MBOX.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir PDF a MBOX en Python" %}}

- Abra el archivo PDF de origen utilizando la clase [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Llame al método `save` mientras especifica la ruta del archivo HTML de salida y las opciones HTML Save relevantes como parámetro. Entonces su archivo PDF se convierte a HTML en la ruta especificada
- Ahora cargue el archivo HTML guardado usando MailMessage.load
- Llame al método de guardar con la ruta de archivo relevante. Así que finalmente el PDF se convierte

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

- Para la conversión de PDF a MBOX, se requiere Python 3.5 o posterior
- API de referencia dentro del proyecto directamente desde PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) y [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- O utilice el siguiente comando pip ```pip install aspose.words``` y ```pip install Aspose.Email-for-Python-via-NET``` 
- Además, el sistema operativo basado en Microsoft Windows o Linux (ver más para [Words](https://docs.aspose.com/words/python-net/system-requirements/) y [Email](https://docs.aspose.com/email/python-net/system-requirements/)) y para Linux verifique los requisitos adicionales para gcc y libpython y siga las instrucciones paso a paso [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Guardar PDF en MBOX en Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

La conversión de PDF a MBOX mediante APIs de Python permite que el contenido PDF se transforme en un formato de archivo de buzón utilizado para almacenar colecciones de mensajes de correo electrónico. Esto es útil cuando la información de los documentos debe incorporarse a flujos de trabajo de archivo de correo electrónico o preservarse en repositorios de mensajes masivos.

Automatizar esta conversión respalda operaciones de archivo escalables, procesos de migración y almacenamiento estructurado de comunicaciones. Reduce el esfuerzo manual al permitir que los documentos PDF se preparen programáticamente para sistemas que dependen de formatos de datos de buzón consolidados.

{{% blocks/products/pf/agp/feature-section-col title="Casos de Uso Clave" %}}

* **Creación de Archivo de Buzón**  
  Convertir contenido PDF en registros compatibles con MBOX para fines de archivo y almacenamiento.

* **Empaquetado de Comunicación Masiva**  
  Organizar mensajes derivados de documentos en colecciones de buzón para portabilidad del sistema.

* **Integración de Archivo de Correo Electrónico**  
  Utilizar los resultados convertidos en entornos que gestionan datos a través de contenedores MBOX.

* **Preservación de Registros**  
  Preservar la información basada en PDF dentro de flujos de trabajo de archivo de mensajes.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Escenarios de Automatización" %}}

* **Generación de Archivo por Lotes**  
  Los flujos de trabajo en Python pueden procesar muchos PDFs en salidas compatibles con MBOX automáticamente.

* **Canales de Retención de Cumplimiento**  
  El contenido convertido puede insertarse en repositorios de archivo para almacenamiento a largo plazo.

* **Preparación para Migración**  
  Los sistemas pueden empaquetar contenido derivado de PDF para transferirlo a plataformas basadas en buzón.

* **Actualizaciones Automatizadas del Repositorio**  
  Los documentos PDF entrantes pueden convertirse continuamente y añadirse a los flujos de trabajo de archivo.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}