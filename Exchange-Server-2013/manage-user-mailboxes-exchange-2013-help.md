﻿---
title: '管理使用者信箱: Exchange Online Help'
TOCTitle: 管理使用者信箱
ms:assetid: 957ca61c-1fa1-42ab-a0e6-8488e4782566
ms:mtpsurl: https://technet.microsoft.com/zh-tw/library/Bb123809(v=EXCHG.150)
ms:contentKeyID: 50473816
ms.date: 05/23/2018
mtps_version: v=EXCHG.150
f1_keywords:
- Microsoft.Exchange.Management.SnapIn.Esm.Recipients.NewMailboxWizardForm.NewMailboxIntroductionWizardPage
ms.translationtype: MT
---

# 管理使用者信箱

 

_**適用版本：**Exchange Online, Exchange Server 2013_

_**上次修改主題的時間：**2014-05-27_

建立使用者信箱後，您可以使用 EAC 或命令介面變更並設定額外屬性。

可同時間變更多個使用者信箱的內容。如需詳細資訊，請參閱Bulk edit user mailboxes。

## 開始之前有哪些須知？

  - 估計每個使用者信箱工作的完成時間：2 至 5 分鐘。

  - 您必須已獲指派權限，才能執行此程序或這些程序。若要查看您需要的權限，請參閱 [收件者權限](recipients-permissions-exchange-2013-help.md) 主題中的「收件者佈建權限」一節。

  - 如需適用於此主題中程序的快速鍵相關資訊，請參閱 [Exchange 系統管理中心的鍵盤快速鍵](keyboard-shortcuts-in-the-exchange-admin-center-exchange-online-protection-help.md)。

<table>
<thead>
<tr class="header">
<th><img src="images/Bb124558.tip(EXCHG.150).gif" title="提示" alt="提示" />提示：</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>有問題嗎？在 Exchange 論壇中尋求協助。 論壇的網址為：<a href="https://go.microsoft.com/fwlink/p/?linkid=60612">Exchange Server</a>、 <a href="https://go.microsoft.com/fwlink/p/?linkid=267542">Exchange Online</a> 或 <a href="https://go.microsoft.com/fwlink/p/?linkid=285351">Exchange Online Protection</a>。.</td>
</tr>
</tbody>
</table>


## 您要執行的工作

## 變更使用者信箱屬性

## 使用 EAC 變更使用者信箱內容

1.  在 EAC 中，瀏覽至 \[收件者\] \> \[信箱\]。

2.  在使用者信箱清單中，按一下您想變更屬性的信箱，然後按一下 \[編輯\]![編輯圖示](images/JJ218640.6f53ccb2-1f13-4c02-bea0-30690e6ea71d(EXCHG.150).gif "編輯圖示")。

3.  在信箱內容頁上，按一下下列其中一個要檢視或變更內容的區段。
    
      - General
    
      - Mailbox Usage
    
      - Contact Information
    
      - Organization
    
      - Email Address
    
      - Mailbox Features
    
      - Member Of
    
      - MailTip
    
      - Mailbox Delegation

## \[一般\]

使用 \[一般\] 區段，檢視或變更使用者的基本資訊。

  - \[名字\]、\[縮寫\]、\[姓氏\]

  - \[\* 名稱\]   這是列於 Active Directory 中的名稱。如果您變更這個名稱，這個名稱不可超過 64 個字元。

  - \* \[顯示名稱\]   這個名稱會出現在組織通訊錄、電子郵件及信箱清單的 \[收件者:\]和 \[寄件者:\]行中。這個顯示名稱前後不可包含空格。

  - \[\* 別名\]此參數指定使用者的電子郵件別名。使用者的別名是電子郵件地址中 (@) 符號左側的部分。它在樹系中必須是唯一的。

  - \* \[使用者登入名稱\]   這是用來登入信箱與登入網域的使用者名稱。通常，使用者登入名稱由 @ 符號左邊的使用者別名組成，@ 符號右邊的使用者帳戶則為網域名稱。
    
    <table>
    <thead>
    <tr class="header">
    <th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td>在 Exchange Online 中，此方塊會標示為 <strong>[使用者識別碼]</strong>。</td>
    </tr>
    </tbody>
    </table>


  - \[必須在下次登入時變更密碼\]   如果您要使用者在下次登入信箱時重設密碼，請選取這個核取方塊。
    
    <table>
    <thead>
    <tr class="header">
    <th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td>在 Exchange Online 中沒有此核取方塊。</td>
    </tr>
    </tbody>
    </table>


  - \[從 Exchange 地址清單隱藏\]   選取此核取方塊，可防止收件者出現在通訊錄以及您的 Exchange 組織中定義的其他通訊錄中。選取此核取方塊後， 使用者仍可以使用電子郵件地址傳送郵件給收件者。

按一下 \[更多選項\]，檢視或變更這些額外的內容：

  - \[組織單位\]   這個唯讀欄位可顯示包含使用者帳戶的組織單位 (OU)。您必須使用 Active Directory 使用者和電腦，才能將使用者帳戶移至不同的 OU。
    
    <table>
    <thead>
    <tr class="header">
    <th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td>在 Exchange Online 中沒有此方塊。</td>
    </tr>
    </tbody>
    </table>


  - \[信箱資料庫\]   這個唯讀方塊顯示主控信箱的信箱資料庫所用的名稱。若要將信箱移動到另一個資料庫，請在信箱清單中選取該信箱，然後在 \[詳細資料\] 窗格中按一下 \[將信箱移至其他資料庫\]。
    
    <table>
    <thead>
    <tr class="header">
    <th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td>在 Exchange Online 中沒有此選項。</td>
    </tr>
    </tbody>
    </table>


  - \[自訂屬性\]   此區段會顯示為使用者信箱定義的自訂屬性。若要指定自訂屬性值，請按一下 \[編輯\]。您最多可為收件者指定 15 個自訂屬性。

## 信箱使用量

使用 \[信箱使用量 \] 區段來檢視或變更信箱儲存配額，以及信箱的已刪除項目的保留設定。信箱建立時這些設定將根據預設設定。這些將使用對於信箱資料庫設定並套用於該資料庫中所有信箱的值。您可以對於各個信箱自訂這些設定，而不使用信箱資料庫預設值。

  - \[上次登入時間\]   此唯讀方塊顯示使用者上一次登入至信箱的時間。

  - \[信箱使用量\]   這個區域顯示信箱的總大小，以及已使用的信箱總配額百分比。

<table>
<thead>
<tr class="header">
<th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>為了取得前面兩個方塊中顯示的資訊，EAC 會查詢主控信箱的信箱資料庫。如果 EAC 無法與包含信箱資料庫的 Exchange 儲存區進行通訊，則這些方塊將會空白。如果使用者尚未登入信箱，將顯示警告訊息。</td>
</tr>
</tbody>
</table>


按一下 \[更多選項\]，檢視或變更信箱儲存配額，以及針對信箱已刪除的項目的保留設定。

<table>
<thead>
<tr class="header">
<th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>在 Exchange Online 中，EAC 沒有這些設定。</td>
</tr>
</tbody>
</table>


  - **儲存配額設定**   若要自訂信箱的這些設定，而不使用信箱資料庫的預設值，按一下 \[自訂此信箱的設定\]，輸入新的值，然後按一下 \[儲存\]。
    
    對於任何儲存配額設定的值範圍是 0 到 2047 GB。
    
      - \[在 (GB) 時發出警告\]   這個方塊顯示向使用者發出警告前的儲存上限。如果信箱大小到達或超過指定的值，Exchange 就會傳送警告郵件給使用者。
    
      - \[在 (GB) 時禁止傳送   這個方塊顯示信箱的*禁止傳送*限制。如果信箱大小到達或超過指定的限制，Exchange 會阻止使用者傳送新郵件，並會顯示描述性錯誤訊息。
    
      - \[在 (GB) 時禁止傳送和接收   這個方塊顯示信箱的*禁止傳送和接收*限制。如果信箱大小到達或超過指定的限制，Exchange 會阻止信箱使用者傳送新郵件，且不會將任何新郵件傳遞到信箱。傳送給信箱的任何郵件都會退回給寄件者，並附帶描述性錯誤訊息。

  - **已刪除項目的保留設定**   若要自訂信箱的這些設定，而不使用信箱資料庫的預設值，按一下 \[自訂此信箱的設定\]，輸入新的值，然後按一下 \[儲存\]。
    
      - \[保留已刪除郵件的天數\]   這個方塊顯示將刪除的項目予以保留的時間長度，經過這段時間後，將永久刪除項目，使用者無法加以復原。信箱建立時，此值會根據信箱資料庫設定的刪除項目保留設定進行設定。依預設，信箱資料庫設定為將刪除的項目保留 14 天。這個內容的值範圍是 0 到 24855 天。
    
      - \[不要在備份資料庫前永久刪除項目\]   選取這個核取方塊，可在備份信箱所在的信箱資料庫之後，才刪除信箱和電子郵件。

## 連絡人資訊

使用\[連絡人資訊\]：這個區段可用來檢視或變更使用者的連絡人資訊。此頁的資訊顯示於通訊錄中。按一下\[更多選項\]以顯示其他方塊。

<table>
<thead>
<tr class="header">
<th><img src="images/Bb124558.tip(EXCHG.150).gif" title="提示" alt="提示" />提示：</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>您可以使用 [縣/市]方塊來建立動態通訊群組、電子郵件地址原則或通訊清單的收件者條件。</td>
</tr>
</tbody>
</table>


信箱使用者可以使用 Outlook 或 Outlook Web App 來檢視和變更他們的連絡人資訊。不過，他們無法變更 \[附註\] 和 \[網頁\] 方塊中的資訊。

## 組織

使用 \[組織\]區段可以記錄組織中之使用者角色的詳細資訊。這個資訊將出現在通訊錄中。另外，您可以從 Outlook 之類的電子郵件用戶端存取的建立虛擬組織圖表。

  - **職稱**   使用這個方塊可檢視或變更收件者的職稱。

  - \[部門\]   使用這個方塊可檢視或變更使用者工作的部門。您可以使用此方塊建立動態通訊群組、電子郵件地址原則或通訊清單的收件者條件。

  - \[公司\]   使用這個方塊可檢視或變更使用者工作的公司。您可以使用此方塊建立動態通訊群組、電子郵件地址原則或通訊清單的收件者條件。

  - **主管**   若要新增主管，按一下 **\[瀏覽\]**。在 \[選取管理員\] 中選取人員，然後按一下 \[確定\]。

  - \[直屬員工\]   您無法修改這個方塊。*「直屬員工」*是向指定的主管報告的使用者。如果您已經為使用者指定主管，此使用者在主管信箱的詳細資料中會顯示為直屬員工。例如，Kari 管理 Chris 和 Kate，所以 Kari 的信箱應分別在 Chris 和 Kate 信箱中的 \[主管\] 中指定，而且 Chris 和 Kate 會出現在 Kari 信箱屬性的 \[直屬員工\] 方塊中。

## 電子郵件地址

使用 \[電子郵件地址\] 區段可用來檢視或變更與使用者信箱相關聯的電子郵件地址。這包括使用者的主要 SMTP 位址以及任一關聯的 Proxy 位址。主要 SMTP 位址 (也稱為*預設回覆地址*) 以粗體顯示在通訊清單中，並且在 \[類型\] 欄中顯示大寫的 **SMTP** 值。

  - \[新增\]  按一下 \[新增\]![加入圖示](images/JJ218640.c1e75329-d6d7-4073-a27d-498590bbb558(EXCHG.150).gif "加入圖示")，可為此信箱新增新的電子郵件地址。選取下列其中一種位址類型：
    
      - \[SMTP\]   這是預設的位址類型。按一下此按鈕，然後在 \[\* 電子郵件地址\] 方塊中輸入新的 SMTP 位址。
    
      - **EUM**   EUM (Exchange 整合通訊) 位址是由 Microsoft Exchange 整合通訊服務用於尋找 Exchange 組織中啟用 UM 功能的使用者。EUM 位址包含啟用 UM 功能的使用者本身的分機號碼和 UM 撥號對應表。點選此按鈕並在 \[通訊錄/分機\]方塊中輸入分機號碼。然後按一下 \[瀏覽\]，並選取使用者的撥號對應表。
    
      - \[自訂位址類型\]   按一下此按鈕，並在 \[\* 電子郵件地址\] 方塊中，輸入其中一種支援的非 SMTP 電子郵件地址類型。
        
        <table>
        <thead>
        <tr class="header">
        <th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td>除了 X.400 位址以外，Exchange 不會驗證自訂位址的格式是否正確。您必須確保指定的自訂位址符合該位址類型的格式需求。</td>
        </tr>
        </tbody>
        </table>
    
      - **將此位址設為回覆地址**   在 Exchange Online 中，您可以選取這個核取方塊，使新的電子郵件地址成為信箱的主要 SMTP 位址。在 Exchange 2013 中，EAC 沒有此核取方塊。

  - \[依照套用至此收件者的電子郵件地址原則自動更新電子郵件地址\]   選取此核取方塊，可讓收件者的電子郵件地址自動依照組織內電子郵件地址原則的變更而更新。預設會選取此方塊。
    
    <table>
    <thead>
    <tr class="header">
    <th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td>在 Exchange Online 中沒有此核取方塊。</td>
    </tr>
    </tbody>
    </table>


  - **將此位址設為回覆地址**

## 信箱功能

使用 \[信箱功能\] 區段可檢視或變更下列信箱功能和設定：

  - \[共用原則\]   這個方塊顯示套用於信箱的共用原則。共用原則可控制組織內的使用者與 Exchange 組織外的使用者共用行事曆與連絡人資訊的方式。建立信箱時，會將預設共用原則指派給信箱。若要變更指派給使用者的共用原則，請從下拉式清單中選取不同的原則。

  - \[角色指派原則\]   這個方塊顯示指派給信箱的角色指派原則。角色指派原則指定指派給使用者的角色存取控制 (RBAC) 角色與控制使用者可修改哪些特定信箱和通訊群組設定。若要變更指派給使用者的角色指派原則，請從下拉式清單中選取不同的原則。

  - \[保留原則\]   這個方塊顯示指派給信箱的保留原則。保留原則是一組套用於使用者信箱的保留標記。它們可讓您控制要將項目保留在使用者信箱中的時間長度，並且定義要針對已達特定天數之項目採取的動作。建立信箱時，不會將保留原則指派給信箱。若要將保留原則指派給使用者，請從下拉式清單中選取原則。

  - **通訊錄原則**   此方塊會顯示套用到信箱的通訊錄原則。通訊錄原則可讓您將使用者分成特定群組，以提供通訊錄的自訂檢視。若要套用或變更套用到信箱中的通訊錄原則，從下拉式清單中選取以下其中一個。

  - **整合通訊**   此功能預設為停用。當您啟用整合通訊 (UM) 時，使用者將可使用您的組織的 UM 功能及使用者套用的一組預設 UM 屬性。按一下 \[啟用\] 為信箱啟用 UM。如需如何啟用 UM 的資訊，請參閱[啟用使用者的語音信箱](enable-a-user-for-voice-mail-exchange-2013-help.md)。
    
    <table>
    <thead>
    <tr class="header">
    <th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td>必須有 UM 撥號對應表和 UM 信箱原則，才能啟用 UM。</td>
    </tr>
    </tbody>
    </table>


  - **行動裝置**   使用此區段可檢視和變更 Exchange ActiveSync (預設為啟用) 的設定。Exchange ActiveSync 原則可讓使用者從行動裝置存取 Exchange 信箱。按一下 \[停用 Exchange ActiveSync\] 可停用信箱的這項功能。

  - **Outlook Web App**   此功能預設為啟用。Outlook Web App 可讓您從任何網頁瀏覽器存取 Exchange 信箱。按一下 \[停用\] 可停用信箱的 Outlook Web App。按一下 \[編輯詳細資料\] 可新增或變更信箱的 Outlook Web App 信箱原則。

  - **IMAP**   此功能預設為啟用。按一下 \[停用\] 以停用信箱的 IMAP。

  - **POP3**   此功能預設為啟用。按一下 \[停用\] 以停用信箱的 POP3。

  - **MAPI**   此功能預設為啟用。MAPI 可讓使用者透過 Outlook 之類的 MAPI 用戶端存取 Exchange 信箱。按一下 \[停用\] 可停用信箱的 MAPI。

  - **訴訟暫止**   此功能預設為停用。訴訟保留功能會保留已刪除的信箱項目，並記錄對信箱項目進行的變更。已刪除的項目和已變更項目的執行個體會在探索搜尋中傳回。按一下 \[啟用\] 可讓信箱處於訴訟暫止狀態。如果信箱處於訴訟暫止狀態，按一下 \[停用\] 可移除訴訟暫止狀態。處於訴訟暫止狀態的信箱是非作用中的信箱，無法加以刪除。若要刪除信箱，請移除訴訟暫止狀態。如果信箱處於訴訟暫止狀態，按一下 \[編輯詳細資料\] 可檢視和變更下列的訴訟暫止設定：
    
      - **暫止日期**   此唯讀方塊指出信箱被放置訴訟暫止的日期和時間。
    
      - \[暫止狀態設定者\]   這個唯讀方塊指出使信箱處於訴訟暫止狀態的使用者。
    
      - **注意**   您可以使用這個方塊通知使用者有關訴訟暫止的資訊、說明信箱處於訴訟暫止狀態的原因，或提供其他指引給使用者，例如告知他們訴訟暫止不會影響日常的電子郵件使用。
    
      - \[URL\]   使用這個方塊可提供網站的 URL，以便提供有關信箱訴訟暫止的相關資訊或指引。
        
        <table>
        <thead>
        <tr class="header">
        <th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td>只有當使用者使用 Outlook 2010 或更新版時，這些方塊中的文字才會顯示在使用者的信箱中。它不會顯示在 Outlook Web App 或其他電子郵件用戶端中。若要在 Outlook 中檢視 [附註] 和 [URL] 方塊中的文字，請按一下 [檔案] 索引標籤，然後您就會在 [資訊] 頁面的 [帳戶設定] 底下看見訴訟暫止註解。</td>
        </tr>
        </tbody>
        </table>


  - **封存**   如果使用者沒有封存信箱，會停用此功能。若要啟用封存信箱，請按一下 \[啟用\]。如果使用者有封存信箱，則會顯示封存信箱的大小和用量統計資料。按一下 \[編輯詳細資料\] 可檢視和變更下列的封存信箱設定：
    
      - \[狀態\]   這個唯讀方塊指出封存信箱是否存在。
    
      - \[資料庫\]   這個唯讀方塊顯示主控封存信箱的信箱資料庫所用的名稱。在 Exchange Online 中沒有此方塊。
    
      - \[名稱\]   在這個方塊中輸入封存信箱的名稱。此名稱顯示於 Outlook 或 Outlook Web App 中的資料夾清單下。
    
      - \[封存配額 (GB)\]   此方塊顯示封存信箱的總容量。若要變更容量，請在方塊中輸入新值或從下拉式清單選擇一個值。
    
      - \[超過下列大小就發出警告 (GB)\]   在警告發出給使用者前，此方塊將顯示封存信箱的最高儲存限制。如果封存信箱大小到達或超過指定的值， Exchange 就會傳送警告郵件給使用者。若要變更此限制，請在方塊中輸入新值或從下拉式清單選擇一個值。
        
        <table>
        <thead>
        <tr class="header">
        <th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td>在 Exchange Online 中，無法變更封存信箱的封存配額和問題警告配額。</td>
        </tr>
        </tbody>
        </table>


  - \[傳遞選項\]   將傳送給使用者的電子郵件轉寄給另一位收件者，以及設定使用者寄送郵件的最大收件者數。請按一下 \[檢視詳細資料\] 來檢視和變更這些設定。
    
      - \[轉寄地址\]   選擇 \[啟用轉寄\] 核取方塊然後按一下 \[瀏覽\] 以顯示 \[選擇郵件使用者與信箱\] 頁面。請使用此頁面，選取您要轉寄此信箱所收到的所有電子郵件的收件者。
    
      - **將郵件同時傳遞到轉寄地址和信箱**   選取這個核取方塊，郵件將傳送到轉寄地址和使用者的信箱。
    
      - \[收件者限制\]   此設定控制使用者可傳送郵件的最高收件者數量。選取 \[收件者人數上限\] 核取方塊以設定電子郵 \[收件者:\]、\[副本:\] 和 \[密件副本:\]方塊的收件者人數限制，然後指定收件者人數上限。
        
        <table>
        <thead>
        <tr class="header">
        <th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td>若是內部部署的 Exchange 組織，收件者限制則無上限。若是 Exchange Online 的組織，上限為 500 位收件者。</td>
        </tr>
        </tbody>
        </table>


  - **郵件大小限制**   這些設定會控制使用者可以傳送和接收的郵件大小。請按一下 \[檢視詳細資料\] 來檢視和變更傳送和接收郵件的大小上限。
    
    <table>
    <thead>
    <tr class="header">
    <th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td>在 Exchange Online 中，無法變更這些設定。</td>
    </tr>
    </tbody>
    </table>
    
      - \[已傳送郵件\]   若要指定此使用者傳送的最大郵件容量，請選擇 \[郵件大小上限 (KB)\] 核取方塊並在方塊中輸入值。郵件大小必須介於 0 和 2,097,151 KB 之間。如果使用者傳送的郵件大於指定的大小，該郵件便會傳回給使用者，並說明為錯誤郵件。
    
      - \[已接收郵件\]   若要指定此使用者接收的最大郵件容量，請選擇 \[郵件大小上限 (KB)\] 核取方塊並在方塊中輸入值。郵件大小必須介於 0 和 2,097,151 KB 之間。如果使用者收到的郵件大於指定的大小，該郵件便會退回給寄件者，並提供說明錯誤訊息。

  - **郵件傳遞限制**   這些設定會控制可以傳送電子郵件訊息給這位使用者的寄件者。請按一下 \[檢視詳細資料\] 來檢視和變更這些限制。
    
      - \[接受郵件的來源\]   使用此區段來指定誰可以傳送郵件給此位使用者。
        
          - \[所有寄件者\]   選擇此選項以指定使用者可接收來自所有寄件者的郵件。其中同時包括 Exchange 組織和外部寄件者中的寄件者。此為預設選取的選項。只有在您清除 \[需要驗證所有寄件者\] 核取方塊時，這個選項才會包括外部使用者。如果您選取此核取方塊，則來自外部使用者的郵件將遭拒。
        
          - \[僅下列清單中的寄件者\]   選擇此選項以指定使用者只可接受來自 Exchange 組織中指定之一組寄件者的郵件。按一下 \[新增\]![加入圖示](images/JJ218640.c1e75329-d6d7-4073-a27d-498590bbb558(EXCHG.150).gif "加入圖示")以顯示 \[選擇收件人\] 頁面，此頁面將顯示所有在您的 Exchange 組織中的收件人。選取想要的收件者，然後按一下 \[確定\]。您也可以在搜尋方塊中輸入收件者的名稱，然後按一下 \[搜尋\]![搜尋圖示](images/Dn624163.773574d0-9b92-4cab-9f6b-81532c7418b9(EXCHG.150).gif "搜尋圖示")，就可以搜尋特定的收件者。
        
          - \[需要驗證所有寄件者\]   選取這個選項，可防止匿名使用者傳送郵件給使用者。
    
      - \[拒絕郵件的來源\]   使用此區段來指定傳送郵件給此位使用者的封鎖對象。
        
          - \[沒有寄件者\]   選擇此選項以指定信箱不會拒絕來自 Exchange 組織中任何寄件者的郵件。此為預設選取的選項。
        
          - \[下列清單中的寄件者\]   選擇此選項以指定信箱將拒絕來自 Exchange 組織中指定之一組寄件者的郵件。按一下 \[新增\]![加入圖示](images/JJ218640.c1e75329-d6d7-4073-a27d-498590bbb558(EXCHG.150).gif "加入圖示") 以顯示 \[選取收件者\] 頁面，此頁面將顯示所有在您的 Exchange 組織中的收件者。選取想要的收件者，然後按一下 \[確定\]。您也可以在搜尋方塊中輸入收件者的名稱，然後按一下 \[搜尋\]![搜尋圖示](images/Dn624163.773574d0-9b92-4cab-9f6b-81532c7418b9(EXCHG.150).gif "搜尋圖示")，就可以搜尋特定的收件者。

## 成員隸屬

使用 \[成員隸屬\] 區段可檢視此使用者所屬之通訊群組或安全性群組的清單。您不能更改此頁上的成員資訊。請注意，使用者可能會符合組織中，一個或多個動態通訊群組的準則。不過，動態通訊群組不會顯示在這個頁面上，因為每次使用此群組時就會計算其成員資格。

## 郵件提示

使用 \[郵件提示\] 區段來加入「郵件提示」，以便在將郵件傳送給此收件者時，警示使用者潛在的問題。「郵件提示」是在此收件者加入至新電子郵件的 \[收件者\]、\[副本\] 或 \[密件副本\] 方塊時，顯示在資訊列中的文字。

<table>
<thead>
<tr class="header">
<th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>「寄件提醒」可以包含 HTML 標記，但是不允許指令碼。自訂郵件提示的長度不能超過 175 個顯示的字元。HTML 標記則不包括在此限制內。</td>
</tr>
</tbody>
</table>


## \[信箱委派\]

使用 \[信箱委派\] 區段來指派其他使用者的權限（也稱為 *委派*）以允許使用者登入至使用者信箱或代表使用者傳送郵件。您可以指派下列權限：

  - \[代表傳送\]   此權限允許除信箱擁有者之外的使用者可使用該信箱傳送郵件。在此權限指派給代理人後，任何代理人自此信箱傳送的郵件都將顯示為由信箱擁有者傳送。但是，此權限不允許代理人登入至使用者的信箱。

  - \[代理傳送者\]   此權限同時允許代理人使用此信箱傳送郵件。但是，在此權限指派給代理人後，在代理人傳送的任何郵件中之 \[寄件者：\]地址將指明郵件是由代理人代表信箱擁有者傳送。

  - \[完整存取\]   此權限允許代理人登入至使用者信箱並可檢視信箱內容。但是，在此權限指派給代理人後，代理人不可自信箱傳送郵件。若要允許代理人自使用者的信箱傳送電子郵件，仍需為代理人指派 \[代表傳送\] 或 \[代理傳送者\] 權限。

若要指派權限給代理人，請按一下適當權限下方的 \[新增\]![加入圖示](images/JJ218640.c1e75329-d6d7-4073-a27d-498590bbb558(EXCHG.150).gif "加入圖示")，即會顯示一個頁面，其中會顯示一份 Exchange 組織中可指派權限的所有收件者清單。選取想要的收件者，然後按一下 \[確定\]。您也可以在搜尋方塊中輸入收件者的名稱，然後按一下 \[搜尋\]![搜尋圖示](images/Dn624163.773574d0-9b92-4cab-9f6b-81532c7418b9(EXCHG.150).gif "搜尋圖示")，就可以搜尋特定的收件者。

## 使用命令介面變更信箱內容

使用 **Get-Mailbox** 與 **Set-Mailbox** 指令程式來檢視與變更使用者信箱的屬性。使用命令介面的其中一個優勢是，可變更多個信箱的屬性。若要瞭解關於對應至信箱屬性的參數，請參閱下列主題：

  - [Get-Mailbox](https://technet.microsoft.com/zh-tw/library/bb123685\(v=exchg.150\))

  - [Set-Mailbox](https://technet.microsoft.com/zh-tw/library/bb123981\(v=exchg.150\))

這裡提供一些使用命令介面變更使用者信箱屬性的範例。

此範例顯示如何將 Pat Coleman 的電子郵件轉寄至 Sunil Koduri 的 (sunilk@contoso.com) 信箱。

    Set-Mailbox -Identity patc -DeliverToMailboxAndForward $true -ForwardingAddress sunilk@contoso.com

此範例使用 **Get-Mailbox** 命令來尋找組織中所有的使用者信箱，然後使用 **Set-Mailbox** 命令將電子郵件 \[收件者:\]、\[副本:\] 和 \[密本副件:\]方塊的收件者限制設定為 500 位收件者。

    Get-Mailbox -ResultSize unlimited -Filter {(RecipientTypeDetails -eq 'UserMailbox')} | Set-Mailbox -RecipientLimits 500

此範例使用 **Get-Mailbox** 命令尋找 Marketing 組織單位中的所有信箱，然後使用 **Set-Mailbox** 命令設定這些信箱。自訂警告、禁止傳送以及禁止傳送和接收限制分別設為 200 MB、250 MB 及 280 MB，並且會略過信箱資料庫的預設限制。此命令可以用來設定一組特定的信箱，讓這些信箱的限制大於或小於組織中的其他信箱。

    Get-Mailbox -OrganizationalUnit "Marketing" | Set-Mailbox -IssueWarningQuota 209715200 -ProhibitSendQuota 262144000 -ProhibitSendReceiveQuota 293601280 -UseDatabaseQuotaDefaults $false 

此範例使用 **Get-Mailbox** 指令程式尋找客戶服務部門中的所有使用者，然後使用 **Set-Mailbox** 指令程式將傳送郵件時的郵件大小上限變更為 2 MB。

    Get-Mailbox -Filter "Department -eq 'Customer Service'" | Set-Mailbox -MaxSendSize 2097152

此範例會設定法文和中文的郵件提示轉譯。

    Set-Mailbox john@contoso.com -MailTipTranslations ("FR: C'est la langue française", "CHT: 這是漢語語言")

## 如何知道這是否正常運作？

若要驗證是否成功變更使用者信箱的屬性，請執行以下其中一個操作：

  - 在 EAC 中，選擇信箱然後按一下 \[編輯\]![編輯圖示](images/JJ218640.6f53ccb2-1f13-4c02-bea0-30690e6ea71d(EXCHG.150).gif "編輯圖示") 以檢視您已變更的內容或功能。根據您變更的屬性，可能會顯示在選取信箱的 \[詳細資料\] 窗格中。

  - 在命令介面中，使用 **Get-Mailbox** 指令程式來驗證變更。使用介面的其中一個優勢是，可檢視多個會議室信箱的不同內容。在上方範例中變更收件者限制的位置執行下列命令，以驗證新值。
    
        Get-Mailbox -ResultSize unlimited -Filter {(RecipientTypeDetails -eq 'UserMailbox')} | fl Name,RecipientLimits
    
    針對上述變更郵件限制的範例中，請執行此命令。
    
        Get-Mailbox -OrganizationalUnit "Marketing" | fl Name,IssueWarningQuota,ProhibitSendQuota,ProhibitSendReceiveQuota,UseDatabaseQuotaDefaults

## 大量編輯使用者信箱

您可以使用 EAC 以變更多個使用者信箱的屬性。當您在 EAC 信箱清單中選取兩個以上的使用者信箱時，\[詳細資料\] 窗格中會顯示可大量編輯的屬性。變更其中一項內容時，變更將套用於所有選取的信箱。

以下是可大量編輯的使用者信箱屬性和功能清單。請注意，不是每一區域的所有屬性都可以變更。

  - **連絡人資訊**   變更街道、郵遞區號和城市名稱等共用內容。

  - **組織**   變更部門名稱、公司名稱以及所選使用者直屬主管等共用屬性。

  - **自訂屬性**   變更或新增自訂屬性值 1-15。

  - **信箱配額**   變更信箱配額值和已刪除項目的保留期間。在 Exchange Online 中沒有這一項。

  - **電子郵件連線**   啟用或停用 Outlook Web App、POP3、IMAP、MAPI 和 Exchange ActiveSync。

  - **封存**   啟用或停用封存信箱。

  - **保留原則、角色指派原則和共用原則**   更新這些信箱功能的設定。

  - **將電子信箱移動到另一個資料庫**   移動所選的信箱到另一個資料庫。

  - **委派權限**   將權限指派給使用者或群組，以允許他們從其他信箱開啟或傳送郵件。您可以將「完整」、「以下列傳送」和「代理傳送者」權限指派給使用者或群組。如需詳細資料，請參閱[管理收件者的權限](manage-permissions-for-recipients-exchange-online-help.md)。

<table>
<thead>
<tr class="header">
<th><img src="images/Bb124558.note(EXCHG.150).gif" title="注意事項" alt="注意事項" />注意事項：</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>此工作的完成時間預計要 2 分鐘，不過，如果您要變更多個屬性或功能，可能會更久。</td>
</tr>
</tbody>
</table>


## 使用 EAC 大量編輯使用者信箱

1.  在 EAC 中，瀏覽至 \[收件者\] \> \[信箱\]。

2.  在信箱清單中，選取兩個或多個信箱。
    
    <table>
    <thead>
    <tr class="header">
    <th><img src="images/Bb124558.tip(EXCHG.150).gif" title="提示" alt="提示" />提示：</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td>您可以按住 Shift 鍵並按一下第一個信箱，然後按一下您想編輯的最後一個信箱，就可選取多個鄰近的信箱。您也可以按住 Ctrl 鍵並按一下您想編輯的每個信箱，就可選取多個不相鄰的信箱。</td>
    </tr>
    </tbody>
    </table>


3.  在 \[詳細資料\] 窗格中 \[大量編輯\] 下，選取您要編輯的信箱屬性或功能。

4.  在內容頁上進行變更，然後儲存您的變更。

## 如何知道這是否正常運作？

若要驗證是否成功設定大量編輯使用者信箱，請執行以下其中一個操作：

  - 在 EAC 中，選擇您想大量編輯的每個使用者信箱，然後按一下 \[編輯\]![編輯圖示](images/JJ218640.6f53ccb2-1f13-4c02-bea0-30690e6ea71d(EXCHG.150).gif "編輯圖示") 以檢視您已變更的屬性或功能。

  - 在 Exchange 管理命令介面中，使用 **Get-Mailbox** 指令程式來驗證變更。使用介面的其中一個優勢是，可檢視多個會議室信箱的不同內容。例如，假設您在 EAC 中使用了大量編輯功能來啟用封存信箱並指派保留原則給組織中所有的使用者。若要確認這些變更，您可執行以下命令：
    
        Get-Mailbox -ResultSize unlimited -Filter {(RecipientTypeDetails -eq 'UserMailbox')} | fl Name,ArchiveDatabase,RetentionPolicy
    
    如需 **Get-Mailbox** 指令程式可用參數的相關資訊，請參閱 [Get-Mailbox](https://technet.microsoft.com/zh-tw/library/bb123685\(v=exchg.150\))。
