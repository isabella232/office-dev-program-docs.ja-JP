---
title: Microsoft 365 開発者プログラム サブスクリプションの有効期限と更新
description: 期限切れの開発者サブスクリプションを更新する方法について説明します。
ms.date: 04/01/2019
localization_priority: Priority
ms.openlocfilehash: 0aa7907a7a2dbf1e1dec4fe5bf7192d8c4b23a54
ms.sourcegitcommit: 9c7a1aa1c562adb350fefc8068e154fa6f9a4ee3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/11/2020
ms.locfileid: "42600796"
---
# <a name="microsoft-365-developer-program-subscription-expiration-and-renewal"></a>Microsoft 365 開発者プログラム サブスクリプションの有効期限と更新

Microsoft 365 開発者プログラムのメンバーシップには、無料の Office 365 E3 または Microsoft 365 E5 開発者サブスクリプションが含まれています。 開発者サブスクリプションは開発アクティビティに基づいて更新可能です。ただし、一部の古いサブスクリプションは期限切れになります。 この記事では、更新可能なサブスクリプションと更新できないサブスクリプションの違い、および有効期限が切れた場合のサブスクリプションのアップグレード方法について説明します。

## <a name="expiring-vs-renewable-developer-subscriptions"></a>期限切れ vs. 更新可能 開発者サブスクリプション

Microsoft 365 開発者プログラムのリリースに伴い、期限切れになると更新できない 12 か月間の開発者サブスクリプションが提供されました。 2018 年 1 月、一部の開発者プログラム メンバーに対して、更新可能なサブスクリプションの提供を開始しました。

2019年 4 月から、更新可能な 90 日間のサブスクリプションを提供しています。

[Microsoft 365 開発者プログラム ダッシュボード](https://aka.ms/DevProgramDashboard)を表示すると、更新可能なサブスクリプションがあるかどうかを確認できます。

## <a name="non-renewable-subscriptions"></a>更新できないサブスクリプション

2018年 8 月より前にサブスクリプションにサインアップした場合、サブスクリプションは更新できず、ダッシュボードに次の警告が表示されます。 現在のサブスクリプションの有効期限が切れる前に、サブスクリプションを置換する必要があります。 警告テキストには、サブスクリプションを更新できないことが示されます。 また、サブスクリプションの有効期限が切れることを通知するメールも送信されます。
 
<img alt="Screenshot of a text box with the title This subscription expires soon and cannot be renewed" src="images/13-expiration-notice-yellow.png" width="500"> 

サブスクリプションの期限が切れると、次の警告テキストが表示されます。

<img alt="Screenshot of a text box with the title This subscription has expired and cannot be renewed" src="images/14-expiration-notice-red.png" width="500"> 

代替サブスクリプションを作成するには、**サブスクリプションの設定**を選択します。 

また、新しいサブスクリプションに保存する必要がある重要なデータを移行する必要があります。 詳細については、「[データを移行する方法](#migrate-data)」のトピックの後半で説明します。

## <a name="renewable-subscriptions"></a>更新可能なサブスクリプション

2018 年 8 月以降にサブスクリプションにサインアップした場合、更新可能なサブスクリプションを取得している可能性があります。 サブスクリプションがアクティブでない場合、ダッシュボードに次の警告が表示されます。 

<img alt="Screenshot of a text box with the title This subscription is inactive and expires soon" src="images/15-renewable-notice-yellow.png" width="500"> 

サブスクリプションの期限が切れると、次の警告テキストが表示されます。

<img alt="Screenshot of a text box with the title This subscription expired on Feb 1, 2019" src="images/16-renewable-notice-red.png" width="500"> 

あなたがアクティブな開発者であれば、サブスクリプションは元の有効期限からさらに 90 日間分自動的に更新されます。 

## <a name="why-isnt-my-current-subscription-renewable"></a>現在のサブスクリプションを更新できないのはなぜですか。

2018 年 8 月に更新可能なサブスクリプションを導入しました。 それより前にサブスクリプションにサインアップした場合、サブスクリプションは更新できず、期限が切れると新しいものを設定する必要があります。

<a name="migrate-data"> </a>

## <a name="how-do-i-migrate-my-data-when-my-subscription-expires"></a>サブスクリプションの有効期限が切れたときにデータを移行する方法は?

現在のサブスクリプションから新しいサブスクリプションにデータを移行するには、次のリソースを参照してください。

- [あるテナントから別のテナントにメールボックスを移行する方法](https://docs.microsoft.com/exchange/mailbox-migration/migrate-mailboxes-across-tenants)
- [PowerShell を使用して段階的な移行を実行する](https://docs.microsoft.com/office365/enterprise/powershell/use-powershell-to-perform-a-staged-migration-to-office-365)
- [サード パーティを介さずに別のサブスクリプションに移行する](https://social.technet.microsoft.com/Forums/en-US/ee507441-eb91-4b0a-ba6c-5bd9bb8c71b1/migration-from-one-o365-tenant-to-another-o365-without-third-party?forum=onlineservicesmigrationandcoexistence)

## <a name="how-do-i-know-if-my-subscription-was-deleted"></a>自分のサブスクリプションが削除されたかどうか、どうすれば確認できますか。

サブスクリプションが削除されると、次のスクリーンショットに示すように、サブスクリプションとその ID が削除されたという通知がダッシュボードに表示されます。 

<img alt="Screenshot of a text box with the title Deleted subscription" src="images/17-deleted-subscription.png" width="500"> 

## <a name="see-also"></a>関連項目

- [Microsoft 365 開発者プログラムに参加する](microsoft-365-developer-program.md)
- [Microsoft 365 開発者サブスクリプションを設定する](microsoft-365-developer-program-get-started.md)
- [サブスクリプションを使用して Microsoft 365 ソリューションを構築する](build-microsoft-365-solutions.md)
- [Microsoft 365 開発者プログラムの FAQ](microsoft-365-developer-program-faq.md)





