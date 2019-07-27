---
title: Office 365 開発者サブスクリプションでサンプル データ パックを使用する
description: サンドボックス環境を迅速に稼働させるために、Office 365 開発者サブスクリプションにサンプル データ パックをインストールする方法を説明します。
localization_priority: Priority
ms.openlocfilehash: 8c6c5c634080e951ca2e60d0d6236db1331d44ae
ms.sourcegitcommit: 6b77e649d1be568a71b6ec572f9d0d2c7cea6f3e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/25/2019
ms.locfileid: "35902350"
---
# <a name="use-sample-data-packs-with-your-office-365-developer-subscription"></a><span data-ttu-id="aaeff-103">Office 365 開発者サブスクリプションでサンプル データ パックを使用する</span><span class="sxs-lookup"><span data-stu-id="aaeff-103">Use sample data packs with your Office 365 developer subscription</span></span>

<span data-ttu-id="aaeff-104">Office 365 開発者サブスクリプションにサンプル データ パックをインストールすることができます。</span><span class="sxs-lookup"><span data-stu-id="aaeff-104">You can install sample data packs on your Office 365 developer subscription.</span></span> <span data-ttu-id="aaeff-105">サンプル データ パックは、ソリューションの構築とテストに必要なデータとコンテンツを自動的にインストールするため、時間を節約することができます。</span><span class="sxs-lookup"><span data-stu-id="aaeff-105">Sample data packs save you time by automatically installing data and content you need to build and test your solutions.</span></span> <span data-ttu-id="aaeff-106">これには、小規模の企業環境をシミュレートするための架空のユーザー、メタデータ、および写真が含まれます。</span><span class="sxs-lookup"><span data-stu-id="aaeff-106">This includes fictitious users, metadata, and photos to simulate a small corporate environment.</span></span> <span data-ttu-id="aaeff-107">サンプル データをすばやくインストールできるため、サンプル データを自分で作成することに時間を費やすことなく、ソリューションに集中することができます。</span><span class="sxs-lookup"><span data-stu-id="aaeff-107">You can quickly install the sample data so that you can focus on your solutions rather than spend time creating sample data yourself.</span></span>

<span data-ttu-id="aaeff-108">サンプル データ パックは、Office 365 サブスクリプション タイルの下部にある [Office 365 開発者プログラム ダッシュボード](https://developer.microsoft.com/office/profile)にあります。</span><span class="sxs-lookup"><span data-stu-id="aaeff-108">You can find sample data packs on your [Office 365 Developer Program dashboard](https://developer.microsoft.com/office/profile), at the bottom of your Office 365 subscription tile.</span></span>

![ダッシュボード ページのサブスクリプション タイルのスクリーンショット](images/content-packs-06.PNG)

<span data-ttu-id="aaeff-110">現在、次のサンプル データ パックをご利用になれます。</span><span class="sxs-lookup"><span data-stu-id="aaeff-110">The following sample data packs are currently available:</span></span>

- <span data-ttu-id="aaeff-111">ユーザー - 各ユーザーの名前および写真を含むライセンスとメールボックスのある 16 人の架空のユーザーをインストールします。</span><span class="sxs-lookup"><span data-stu-id="aaeff-111">Users - Installs 16 fictitious users with licenses, mailboxes, and metadata, including names and photos for each user.</span></span> <span data-ttu-id="aaeff-112">Microsoft Graph API を使用して、次の方法でユーザー サンプル データを操作します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-112">Use Microsoft Graph APIs to work with user sample data in the following ways:</span></span>
  - <span data-ttu-id="aaeff-113">特定のユーザーの詳細を取得する</span><span class="sxs-lookup"><span data-stu-id="aaeff-113">Get specific user details</span></span>
  - <span data-ttu-id="aaeff-114">ユーザーを更新する</span><span class="sxs-lookup"><span data-stu-id="aaeff-114">Update user</span></span>
  - <span data-ttu-id="aaeff-115">直属の部下を取得する</span><span class="sxs-lookup"><span data-stu-id="aaeff-115">Get user's direct reports.</span></span>
  - <span data-ttu-id="aaeff-116">組織図を準備する</span><span class="sxs-lookup"><span data-stu-id="aaeff-116">Prepare organization chart</span></span>  
  - <span data-ttu-id="aaeff-117">部署別にユーザーを取得する</span><span class="sxs-lookup"><span data-stu-id="aaeff-117">Get users by department</span></span>

- <span data-ttu-id="aaeff-118">メールとイベント - 各 16 人のサンプル ユーザーに Outlook メールの会話とカレンダーのイベントを追加します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-118">Mail and events - Adds Outlook email conversations and calendar events for each of the 16 sample users.</span></span> <span data-ttu-id="aaeff-119">Microsoft Graph API を使用して、次の方法でメールとイベント サンプル データを操作します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-119">Use Microsoft Graph APIs to work with mail and events sample data in the following ways:</span></span>
  - <span data-ttu-id="aaeff-120">ユーザーがメールを取得する</span><span class="sxs-lookup"><span data-stu-id="aaeff-120">Get emails by users</span></span>
  - <span data-ttu-id="aaeff-121">日付でフィルター処理されたメールを取得する</span><span class="sxs-lookup"><span data-stu-id="aaeff-121">Get emails filtered by date</span></span>
  - <span data-ttu-id="aaeff-122">今後のイベントを取得する</span><span class="sxs-lookup"><span data-stu-id="aaeff-122">Get upcoming events</span></span>
  - <span data-ttu-id="aaeff-123">今後のイベントを更新/削除する</span><span class="sxs-lookup"><span data-stu-id="aaeff-123">Update/delete upcoming events</span></span>

> [!NOTE]
> <span data-ttu-id="aaeff-124">メールとイベントをインストールする前に、ユーザー サンプル データ パックをインストールする必要があります。</span><span class="sxs-lookup"><span data-stu-id="aaeff-124">You must install the Users sample data pack before you install Mail and Events.</span></span>

## <a name="what-do-the-sample-data-packs-add-to-my-office-365-subscription"></a><span data-ttu-id="aaeff-125">サンプル データ パックは、Office 365 サブスクリプションに何を追加しますか?</span><span class="sxs-lookup"><span data-stu-id="aaeff-125">What do the sample data packs add to my Office 365 subscription?</span></span>

<span data-ttu-id="aaeff-126">ユーザー サンプル データ パックは、サブスクリプションに 16 人の架空のユーザーを作成します。各ユーザーのライセンスと、各ユーザーのメールボックス、名前、メタデータ、写真が含まれます。</span><span class="sxs-lookup"><span data-stu-id="aaeff-126">The Users sample data pack creates 16 fictitious users on your subscription, and includes the licenses for each user, and mailboxes, names, metadata, and photos for each.</span></span>

<span data-ttu-id="aaeff-127">メールとイベントのサンプル データ パックによって、インストールされた各 16 人のユーザーに Outlook メールの会話とカレンダーのイベントが追加されます。</span><span class="sxs-lookup"><span data-stu-id="aaeff-127">The Mail and Events sample data pack adds Outlook email conversations and calendar events for each of the 16 users installed.</span></span>

## <a name="how-do-i-install-the-users-sample-data-pack"></a><span data-ttu-id="aaeff-128">ユーザー サンプル データ パックをインストールする方法</span><span class="sxs-lookup"><span data-stu-id="aaeff-128">How do I install the Users sample data pack?</span></span>

<span data-ttu-id="aaeff-129">ユーザー サンプル データ パックをインストールする前に、Office 365 開発者サブスクリプションをお持ちで、管理者として自分にライセンスを割り当てる必要があります。</span><span class="sxs-lookup"><span data-stu-id="aaeff-129">Before you install the Users sample data pack, make sure that you have an Office 365 developer subscription and that you assign a license to yourself as the admin.</span></span>

<span data-ttu-id="aaeff-130">ユーザー サンプル データ パックをインストールするには、次の操作を行います。</span><span class="sxs-lookup"><span data-stu-id="aaeff-130">To install the Users sample data pack:</span></span>

1. <span data-ttu-id="aaeff-131">サブスクリプション タイルの下部にある [**ユーザー**] ボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-131">Select the **Users** box at the bottom of your subscription tile.</span></span>
2. <span data-ttu-id="aaeff-132">管理者 ID をコピーします。サブスクリプションにサインインする際に、アカウントが必要です。</span><span class="sxs-lookup"><span data-stu-id="aaeff-132">Copy your administrator ID; you will need it to sign in to your subscription.</span></span>
3. <span data-ttu-id="aaeff-133">サインイン ページで、管理者 ID とパスワードを入力します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-133">Enter your administrator ID and password on the sign in page.</span></span>
4. <span data-ttu-id="aaeff-134">Office 365 開発者サブスクリプションの管理者としての権限に同意します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-134">Consent to the permissions as an administrator of your Office 365 developer subscription.</span></span>

![権限の同意ダイアログ ボックスを示すスクリーンショット](images/content-packs-01.png)

5. <span data-ttu-id="aaeff-136">すべてのサンプル ユーザーのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-136">Configure your passwords for all sample users.</span></span> <span data-ttu-id="aaeff-137">すべての架空のユーザーを簡単に管理できるように、1 つの共有パスワードを定義する必要があります。</span><span class="sxs-lookup"><span data-stu-id="aaeff-137">You will need to have one shared password defined for easy administration of all your fictitious users.</span></span>

![共有ユーザー パスワードを追加するダイアログ ボックスのスクリーンショット](images/content-packs-02.png)

6. <span data-ttu-id="aaeff-139">データがインストールされます。</span><span class="sxs-lookup"><span data-stu-id="aaeff-139">The existing data will be overwritten.</span></span> <span data-ttu-id="aaeff-140">インストールには約 5 分ほどかかります。</span><span class="sxs-lookup"><span data-stu-id="aaeff-140">The installation should take about 5 minutes.</span></span>

![ダッシュボード タイルのインストール処理を示すスクリーンショット](images/content-packs-03.PNG)

7. <span data-ttu-id="aaeff-142">インストールが完了すると、メールで通知され、サブスクリプション タイルのボックスは緑色になります。</span><span class="sxs-lookup"><span data-stu-id="aaeff-142">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span> <span data-ttu-id="aaeff-143">メールとイベントのサンプル データ パックをインストールできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aaeff-143">You can now install the Mail and Events sample data pack.</span></span>

![インストールの準備ができたメールとイベントが表示されているダッシュボード タイルのスクリーンショット](images/content-packs-04.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a><span data-ttu-id="aaeff-145">メールとイベントのサンプル データ パックをインストールする方法</span><span class="sxs-lookup"><span data-stu-id="aaeff-145">How do I install the Mail and Events sample data pack?</span></span>

<span data-ttu-id="aaeff-146">ユーザー サンプル データ パックをインストールした後、メールとイベントをインストールすることができます。</span><span class="sxs-lookup"><span data-stu-id="aaeff-146">After you've installed the Users sample data pack, you can install mail and events.</span></span>

1. <span data-ttu-id="aaeff-147">サブスクリプション タイルの [**メール &amp; イベント**] ボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-147">Choose the **Mail &amp; Events** box on your subscription tile.</span></span>
2. <span data-ttu-id="aaeff-148">[**インストール**] を選択して、インストールを開始します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-148">Click **Install** to begin the installation.</span></span>

![インストール ダイアログ ボックスのスクリーンショット](images/content-packs-05.png)

> [!NOTE]
> <span data-ttu-id="aaeff-150">サブスクリプションを作成したばかりの場合は、インストールを開始する前にそのサブスクリプションを完全にプロビジョニングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="aaeff-150">If you just created your subscription, it must be fully provisioned before installation can begin.</span></span> <span data-ttu-id="aaeff-151">これには数時間かかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="aaeff-151">This can take up to a few hours.</span></span> <span data-ttu-id="aaeff-152">インストールが開始された後、終了には最大 20 分かかります。</span><span class="sxs-lookup"><span data-stu-id="aaeff-152">After installation starts, it can take up to 20 minutes to finish.</span></span>

3. <span data-ttu-id="aaeff-153">インストールが完了すると、メールで通知され、サブスクリプション タイルのボックスは緑色になります。</span><span class="sxs-lookup"><span data-stu-id="aaeff-153">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span>

## <a name="are-more-sample-data-packs-coming"></a><span data-ttu-id="aaeff-154">サンプル データ パックは追加されますか?</span><span class="sxs-lookup"><span data-stu-id="aaeff-154">Are more sample data packs coming?</span></span>

<span data-ttu-id="aaeff-155">はい。</span><span class="sxs-lookup"><span data-stu-id="aaeff-155">Yes.</span></span> <span data-ttu-id="aaeff-156">SharePoint と OneDrive のサンプル データ パックを追加する予定です。</span><span class="sxs-lookup"><span data-stu-id="aaeff-156">We will add sample data packs for SharePoint and OneDrive.</span></span> <span data-ttu-id="aaeff-157">将来、Office アドイン、Microsoft Teams など、その他の製品とテクノロジのサンプル データ パックを追加することを検討しています。</span><span class="sxs-lookup"><span data-stu-id="aaeff-157">In the future, we will consider adding sample data packs for more products and technologies, including Office Add-ins, Microsoft Teams, and more.</span></span>

## <a name="can-i-install-sample-data-packs-on-my-other-office-365-subscriptions"></a><span data-ttu-id="aaeff-158">サンプル データ パックを他の Office 365 サブスクリプションにインストールできますか?</span><span class="sxs-lookup"><span data-stu-id="aaeff-158">Can I install sample data packs on my other Office 365 subscriptions?</span></span>

<span data-ttu-id="aaeff-159">いいえ。</span><span class="sxs-lookup"><span data-stu-id="aaeff-159">No.</span></span> <span data-ttu-id="aaeff-160">これらのサンプル データ パックは、Office 365 開発者プログラムの一部として取得した Office 365 開発者サブスクリプションとのみ互換性があります。</span><span class="sxs-lookup"><span data-stu-id="aaeff-160">These sample data packs are only compatible with the Office 365 Developer Subscription you get as part of the Office 365 Developer Program.</span></span>

## <a name="how-can-i-see-the-sample-data-in-my-subscription"></a><span data-ttu-id="aaeff-161">どうすればサンプル データをサブスクリプションに表示できますか?</span><span class="sxs-lookup"><span data-stu-id="aaeff-161">How can I see the sample data in my subscription?</span></span>

<span data-ttu-id="aaeff-162">ユーザーのサンプル データ パックのインストール後に、追加されたユーザーを表示するには、Office 365 開発者サブスクリプションで**Microsoft 365 管理センター**に移動します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-162">After you install the Users sample data pack, to see the users that were added, go to the **Microsoft 365 Admin Center** on your Office 365 developer subscription.</span></span> <span data-ttu-id="aaeff-163">[**ユーザー**] の下で [**アクティブ ユーザー**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-163">Under **Users**, select **Active users**.</span></span> <span data-ttu-id="aaeff-164">16 人のユーザーの一覧が表示されます。</span><span class="sxs-lookup"><span data-stu-id="aaeff-164">You will see the list of 16 users.</span></span> <span data-ttu-id="aaeff-165">ユーザーを選択して、写真やライセンスを含む関連付けられたメタデータを表示します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-165">You can select a user to view the associated metadata, including photos and licenses.</span></span>

![Microsoft 365 管理センターの 16 人のユーザーのリストには、指定したユーザーのメタデータが含まれます。](images/content-packs-07.PNG)

<span data-ttu-id="aaeff-167">メールとイベントのサンプル パックのインストール後に、サンプル データを表示するには、**Microsoft 365 管理センター**で [**すべて表示**] を選択して、[**Exchange**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="aaeff-167">After you install the Mail and Events sample pack, to see the sample data, in the **Microsoft 365 Admin Center**, choose **Show all** and then select **Exchange**.</span></span> <span data-ttu-id="aaeff-168">Exchange 管理センターで [**受信者**] を選択すると、各 16 人のユーザーが、追加されたメールとイベントを含むメールボックスと共に表示されます。</span><span class="sxs-lookup"><span data-stu-id="aaeff-168">In the Exchange admin center, when you select **recipients**, you can see that each of the 16 users has mailboxes with mail and events added.</span></span>
<span data-ttu-id="aaeff-169">![Exchange 管理センターに追加された 16 人のユーザーのスクリーンショット](images/content-packs-08.PNG)</span><span class="sxs-lookup"><span data-stu-id="aaeff-169">![Screenshot of 16 users added to the Exchange Admin Center](images/content-packs-08.PNG)</span></span>

## <a name="see-also"></a><span data-ttu-id="aaeff-170">関連項目</span><span class="sxs-lookup"><span data-stu-id="aaeff-170">See also</span></span>

- [<span data-ttu-id="aaeff-171">Office 365 開発者サブスクリプションのセットアップ</span><span class="sxs-lookup"><span data-stu-id="aaeff-171">Set up an Office 365 developer subscription</span></span>](office-365-developer-program-get-started.md)
