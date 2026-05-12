---
title: Python で WORDML を VCF に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で WORDML を VCF に保存します。

family: total
platformtag: Python
feature: conversion
informat: WORDML
outformat: VCF
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して WORDML を VCF に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで WORDML から VCF への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に WORDML から VCF への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に WORDML ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、VCF 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で WORDML を VCF に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース WORDML ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、WORDML ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にWORDMLが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- WORDML から VCF への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでWORDMLをVCFに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

WordMLからVCFへの変換は、文書ベースの連絡先情報をvCardファイルに変換し、連絡先管理システムにインポートできるようにします。これは、文書に保存された名前、電話番号、住所、または関連情報を標準化された連絡先レコードにする必要がある場合に便利です。

Python API を使用すると、WordMLからVCFへの変換を自動化でき、関連する連絡先フィールドを抽出し、CRM、ディレクトリ、同期ワークフロー向けのポータブルなvCard出力を生成します。

{{% blocks/products/pf/agp/feature-section-col title="主な使用例" %}}

* **連絡先レコード抽出**
  WordMLドキュメントから連絡先詳細を変換し、インポート可能なVCFファイルにします。

* **ディレクトリとCRMのサポート**
  文書ベースの連絡先データを構造化された連絡先システムへ移行するのに役立ちます。

* **ポータブルな連絡先共有**
  プラットフォーム間で標準化された連絡先情報の交換を可能にします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **大量連絡先生成**
  WordMLに保存されたディレクトリ、フォーム、または連絡先リストからVCF作成を自動化します。

* **CRMデータ準備**
  標準化された連絡先レコードを自動化された業務システムに取り込むことをサポートします。

* **同期ワークフローの有効化**
  文書に保持された連絡先詳細を、定期的な同期のためのポータブルファイルに変換します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}