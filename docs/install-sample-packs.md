---
title: Office 365 開発者サブスクリプションでサンプル データ パックを使用する
description: サンドボックス環境を迅速に稼働させるために、Office 365 開発者サブスクリプションにサンプル データ パックをインストールする方法を説明します。
localization_priority: Priority
ms.openlocfilehash: 16e605080673678b750ebeab4501ceb980cea6cb
ms.sourcegitcommit: 76c5e3c9b58026471378e7634d121842690fd517
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/10/2019
ms.locfileid: "35618856"
---
# <a name="use-sample-data-packs-with-your-office-365-developer-subscription"></a><span data-ttu-id="e7226-103">Office 365 開発者サブスクリプションでサンプル データ パックを使用する</span><span class="sxs-lookup"><span data-stu-id="e7226-103">Use sample data packs with your Office 365 developer subscription</span></span>

<span data-ttu-id="e7226-104">Office 365 開発者サブスクリプションにサンプル データ パックをインストールすることができます。</span><span class="sxs-lookup"><span data-stu-id="e7226-104">You can install sample data packs on your Office 365 developer subscription.</span></span> <span data-ttu-id="e7226-105">サンプル データ パックは、ソリューションの構築とテストに必要なデータとコンテンツを自動的にインストールするため、時間を節約することができます。</span><span class="sxs-lookup"><span data-stu-id="e7226-105">Sample data packs save you time by automatically installing data and content you need to build and test your solutions.</span></span> <span data-ttu-id="e7226-106">これには、小規模の企業環境をシミュレートするための架空のユーザー、メタデータ、および写真が含まれます。</span><span class="sxs-lookup"><span data-stu-id="e7226-106">This includes fictitious users, metadata, and photos to simulate a small corporate environment.</span></span> <span data-ttu-id="e7226-107">サンプル データをすばやくインストールできるため、サンプル データを自分で作成することに時間を費やすことなく、ソリューションに集中することができます。</span><span class="sxs-lookup"><span data-stu-id="e7226-107">You can quickly install the sample data so that you can focus on your solutions rather than spend time creating sample data yourself.</span></span>

<span data-ttu-id="e7226-108">サンプル データ パックは、Office 365 サブスクリプション タイルの下部にある [Office 365 開発者プログラム ダッシュボード](https://developer.microsoft.com/office/profile)にあります。</span><span class="sxs-lookup"><span data-stu-id="e7226-108">You can find sample data packs on your [Office 365 Developer Program dashboard](https://developer.microsoft.com/office/profile), at the bottom of your Office 365 subscription tile.</span></span>

![ダッシュボード ページのサブスクリプション タイルのスクリーンショット](images/content-packs-06.PNG)

<span data-ttu-id="e7226-110">現在、次のサンプル データ パックをご利用になれます。</span><span class="sxs-lookup"><span data-stu-id="e7226-110">The following sample data packs are currently available:</span></span>

- <span data-ttu-id="e7226-111">ユーザー - 各ユーザーの名前および写真を含むライセンスとメールボックスのある 16 人の架空のユーザーをインストールします。</span><span class="sxs-lookup"><span data-stu-id="e7226-111">Users - Installs 16 fictitious users with licenses, mailboxes, and metadata, including names and photos for each user.</span></span> <span data-ttu-id="e7226-112">Microsoft Graph API を使用して、次の方法でユーザー サンプル データを操作します。</span><span class="sxs-lookup"><span data-stu-id="e7226-112">Use Microsoft Graph APIs to work with user sample data in the following ways:</span></span>
  - <span data-ttu-id="e7226-113">特定のユーザーの詳細を取得する</span><span class="sxs-lookup"><span data-stu-id="e7226-113">Get specific user details</span></span>
  - <span data-ttu-id="e7226-114">ユーザーを更新する</span><span class="sxs-lookup"><span data-stu-id="e7226-114">Update user</span></span>
  - <span data-ttu-id="e7226-115">直属の部下を取得する</span><span class="sxs-lookup"><span data-stu-id="e7226-115">Get user's direct reports.</span></span>
  - <span data-ttu-id="e7226-116">組織図を準備する</span><span class="sxs-lookup"><span data-stu-id="e7226-116">Prepare organization chart</span></span>  
  - <span data-ttu-id="e7226-117">部署別にユーザーを取得する</span><span class="sxs-lookup"><span data-stu-id="e7226-117">Get users by department</span></span>

- <span data-ttu-id="e7226-118">メールとイベント - 各 16 人のサンプル ユーザーに Outlook メールの会話とカレンダーのイベントを追加します。</span><span class="sxs-lookup"><span data-stu-id="e7226-118">Mail and events - Adds Outlook email conversations and calendar events for each of the 16 sample users.</span></span> <span data-ttu-id="e7226-119">Microsoft Graph API を使用して、次の方法でメールとイベント サンプル データを操作します。</span><span class="sxs-lookup"><span data-stu-id="e7226-119">Use Microsoft Graph APIs to work with mail and events sample data in the following ways:</span></span>
  - <span data-ttu-id="e7226-120">ユーザーがメールを取得する</span><span class="sxs-lookup"><span data-stu-id="e7226-120">Get emails by users</span></span>
  - <span data-ttu-id="e7226-121">日付でフィルター処理されたメールを取得する</span><span class="sxs-lookup"><span data-stu-id="e7226-121">Get emails filtered by date</span></span>
  - <span data-ttu-id="e7226-122">今後のイベントを取得する</span><span class="sxs-lookup"><span data-stu-id="e7226-122">Get upcoming events</span></span>
  - <span data-ttu-id="e7226-123">今後のイベントを更新/削除する</span><span class="sxs-lookup"><span data-stu-id="e7226-123">Update/delete upcoming events</span></span>

> [!NOTE]
> <span data-ttu-id="e7226-124">メールとイベントをインストールする前に、ユーザー サンプル データ パックをインストールする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7226-124">You must install the Users sample data pack before you install Mail and Events.</span></span>

## <a name="what-do-the-sample-data-packs-add-to-my-office-365-subscription"></a><span data-ttu-id="e7226-125">サンプル データ パックは、Office 365 サブスクリプションに何を追加しますか?</span><span class="sxs-lookup"><span data-stu-id="e7226-125">What do the sample data packs add to my Office 365 subscription?</span></span>

<span data-ttu-id="e7226-126">ユーザー サンプル データ パックは、サブスクリプションに 16 人の架空のユーザーを作成します。各ユーザーのライセンスと、各ユーザーのメールボックス、名前、メタデータ、写真が含まれます。</span><span class="sxs-lookup"><span data-stu-id="e7226-126">The Users sample data pack creates 16 fictitious users on your subscription, and includes the licenses for each user, and mailboxes, names, metadata, and photos for each.</span></span>

<span data-ttu-id="e7226-127">メールとイベントのサンプル データ パックによって、インストールされた各 16 人のユーザーに Outlook メールの会話とカレンダーのイベントが追加されます。</span><span class="sxs-lookup"><span data-stu-id="e7226-127">The Mail and Events sample data pack adds Outlook email conversations and calendar events for each of the 16 users installed.</span></span>

## <a name="how-do-i-install-the-users-sample-data-pack"></a><span data-ttu-id="e7226-128">ユーザー サンプル データ パックをインストールする方法</span><span class="sxs-lookup"><span data-stu-id="e7226-128">How do I install the Users sample data pack?</span></span>

<span data-ttu-id="e7226-129">ユーザー サンプル データ パックをインストールする前に、Office 365 開発者サブスクリプションをお持ちで、管理者として自分にライセンスを割り当てる必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7226-129">Before you install the Users sample data pack, make sure that you have an Office 365 developer subscription and that you assign a license to yourself as the admin.</span></span>

<span data-ttu-id="e7226-130">ユーザー サンプル データ パックをインストールするには、次の操作を行います。</span><span class="sxs-lookup"><span data-stu-id="e7226-130">To install the Users sample data pack:</span></span>

1. <span data-ttu-id="e7226-131">サブスクリプション タイルの下部にある [**ユーザー**] ボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="e7226-131">Select the **Users** box at the bottom of your subscription tile.</span></span>
2. <span data-ttu-id="e7226-132">管理者 ID をコピーします。サブスクリプションにサインインする際に、アカウントが必要です。</span><span class="sxs-lookup"><span data-stu-id="e7226-132">Copy your administrator ID; you will need it to sign in to your subscription.</span></span>
3. <span data-ttu-id="e7226-133">サインイン ページで、管理者 ID とパスワードを入力します。</span><span class="sxs-lookup"><span data-stu-id="e7226-133">Enter your administrator ID and password on the sign in page.</span></span>
4. <span data-ttu-id="e7226-134">Office 365 開発者サブスクリプションの管理者としての権限に同意します。</span><span class="sxs-lookup"><span data-stu-id="e7226-134">Consent to the permissions as an administrator of your Office 365 developer subscription.</span></span>

![権限の同意ダイアログ ボックスを示すスクリーンショット](images/content-packs-01.png)

5. <span data-ttu-id="e7226-136">すべてのサンプル ユーザーのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="e7226-136">Configure your passwords for all sample users.</span></span> <span data-ttu-id="e7226-137">すべての架空のユーザーを簡単に管理できるように、1 つの共有パスワードを定義する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7226-137">You will need to have one shared password defined for easy administration of all your fictitious users.</span></span>

![共有ユーザー パスワードを追加するダイアログ ボックスのスクリーンショット](images/content-packs-02.png)

6. <span data-ttu-id="e7226-139">データがインストールされます。</span><span class="sxs-lookup"><span data-stu-id="e7226-139">The existing data will be overwritten.</span></span> <span data-ttu-id="e7226-140">インストールには約 5 分ほどかかります。</span><span class="sxs-lookup"><span data-stu-id="e7226-140">The installation should take about 5 minutes.</span></span>

![ダッシュボード タイルのインストール処理を示すスクリーンショット](images/content-packs-03.PNG)

7. <span data-ttu-id="e7226-142">インストールが完了すると、メールで通知され、サブスクリプション タイルのボックスは緑色になります。</span><span class="sxs-lookup"><span data-stu-id="e7226-142">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span> <span data-ttu-id="e7226-143">メールとイベントのサンプル データ パックをインストールできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="e7226-143">You can now install the Mail and Events sample data pack.</span></span>

![インストールの準備ができたメールとイベントが表示されているダッシュボード タイルのスクリーンショット](images/content-packs-04.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a><span data-ttu-id="e7226-145">メールとイベントのサンプル データ パックをインストールする方法</span><span class="sxs-lookup"><span data-stu-id="e7226-145">How do I install the Mail and Events sample data pack?</span></span>

<span data-ttu-id="e7226-146">ユーザー サンプル データ パックをインストールした後、メールとイベントをインストールすることができます。</span><span class="sxs-lookup"><span data-stu-id="e7226-146">After you've installed the Users sample data pack, you can install mail and events.</span></span>

1. <span data-ttu-id="e7226-147">サブスクリプション タイルの [**メール &amp; イベント**] ボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="e7226-147">Choose the **Mail &amp; Events** box on your subscription tile.</span></span>
2. <span data-ttu-id="e7226-148">[**インストール**] を選択して、インストールを開始します。</span><span class="sxs-lookup"><span data-stu-id="e7226-148">Click **Install** to begin the installation.</span></span>

![インストール ダイアログ ボックスのスクリーンショット](images/content-packs-05.png)

> [!NOTE]
> <span data-ttu-id="e7226-150">サブスクリプションを作成したばかりの場合は、インストールを開始する前にそのサブスクリプションを完全にプロビジョニングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7226-150">If you just created your subscription, it must be fully provisioned before installation can begin.</span></span> <span data-ttu-id="e7226-151">これには数時間かかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="e7226-151">This can take up to a few hours.</span></span> <span data-ttu-id="e7226-152">インストールが開始された後、終了には最大 20 分かかります。</span><span class="sxs-lookup"><span data-stu-id="e7226-152">After installation starts, it can take up to 20 minutes to finish.</span></span>

3. <span data-ttu-id="e7226-153">インストールが完了すると、メールで通知され、サブスクリプション タイルのボックスは緑色になります。</span><span class="sxs-lookup"><span data-stu-id="e7226-153">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span>

## <a name="are-more-sample-data-packs-coming"></a><span data-ttu-id="e7226-154">サンプル データ パックは追加されますか?</span><span class="sxs-lookup"><span data-stu-id="e7226-154">Are more sample data packs coming?</span></span>

<span data-ttu-id="e7226-155">はい。</span><span class="sxs-lookup"><span data-stu-id="e7226-155">Yes.</span></span> <span data-ttu-id="e7226-156">SharePoint と OneDrive のサンプル データ パックを追加する予定です。</span><span class="sxs-lookup"><span data-stu-id="e7226-156">We will add sample data packs for SharePoint and OneDrive.</span></span> <span data-ttu-id="e7226-157">将来、Office アドイン、Microsoft Teams など、その他の製品とテクノロジのサンプル データ パックを追加することを検討しています。</span><span class="sxs-lookup"><span data-stu-id="e7226-157">In the future, we will consider adding sample data packs for more products and technologies, including Office Add-ins, Microsoft Teams, and more.</span></span>

## <a name="can-i-install-sample-data-packs-on-my-other-office-365-subscriptions"></a><span data-ttu-id="e7226-158">サンプル データ パックを他の Office 365 サブスクリプションにインストールできますか?</span><span class="sxs-lookup"><span data-stu-id="e7226-158">Can I install sample data packs on my other Office 365 subscriptions?</span></span>

<span data-ttu-id="e7226-159">いいえ。</span><span class="sxs-lookup"><span data-stu-id="e7226-159">No.</span></span> <span data-ttu-id="e7226-160">これらのサンプル データ パックは、Office 365 開発者プログラムに含まれている Office 365 開発者サブスクリプションとのみ互換性があります。</span><span class="sxs-lookup"><span data-stu-id="e7226-160">These sample data packs are only compatible with the Office 365 Developer Subscription you get as part of the Office 365 Developer Program.</span></span>

## <a name="see-also"></a><span data-ttu-id="e7226-161">関連項目</span><span class="sxs-lookup"><span data-stu-id="e7226-161">See also</span></span>

- [<span data-ttu-id="e7226-162">Office 365 開発者サブスクリプションのセットアップ</span><span class="sxs-lookup"><span data-stu-id="e7226-162">Set up an Office 365 developer subscription</span></span>](office-365-developer-program-get-started.md)
