# i.5　指南嘅約定
最後 [updated](/node/2827281/discuss) 於2023年2月21日

### [](#s-assumptions-and-prerequisites "Permalink to this headline")假設和先決條件
本指南具有以下假設和先決條件：

- 本指南涵蓋咗核心軟件嘅當前主要版本。
- 本指南被組織為主題；有關詳細信息，請參見 [Section i.3, 「Organization」](/docs/user_guide/en/preface-organization.html "i.3. Organization")。許多主題包括「*先決條件知識*」部分，其中列出咗需要其內容知識嘅其佢主題，以瞭解您正喺閱讀嘅主題。還假定咗指南中未涵蓋嘅啲背景知識；有關詳細信息，請參見 [Section i.2, 「Audience and Goal」](/docs/user_guide/en/preface-audience.html "i.2. Audience and Goal")。
- 許多任務主題列表「*站點先決條件*」，呢個係您喺網企上完成嘅任務，然後才能完成您正喺閱讀嘅主題中嘅任務。
- 本網站先決條件嘅細節與喺本指南中使用嘅場景有關，該指南為農貿街市建立網站（有關詳細信息，請參見 [Section i.6, 「Guiding Scenario」](/docs/user_guide/en/preface-scenario.html "i.6. Guiding Scenario")）。您可以將任務調整到自己嘅情況下，但係您還需要記住確定網站係否滿足任務嘅站點先決條件時所做嘅更改。
- 對於 [Section 3.7, 「Running the Interactive Installer」](/docs/user_guide/en/install-run.html "3.7. Running the Interactive Installer") 之後嘅所有任務主題，也有一個隱式先決條件：您必須喺網企上安裝咗最新嘅內容管理軟件嘅穩定版本，並可以登錄到具有足夠許可權嘅用戶帳戶任務（例如安裝網站時創建嘅用戶帳戶，自喐具有完整嘅許可權）。
- 如果您撳順序讀取所有主題，並喺執行任務主題中執行所有步驟（登錄），則喺閱讀它時，您應該為每個主題提供背景知識和站點先決條件。
- 本指南演示咗如何使用管理用戶界面執行任務，並喺可能嘅情況下使用 `Drush` 命令行工具嘅最新穩定版本（請參閱 [Section 3.2, 「Concept: Additional Tools」](/docs/user_guide/en/install-tools.html " Additional Tools")）。您可以隨意使用其佢命令行工具，例如 `Drupal Console`（如果查搵等效命令），或者而家僅使用管理界面。

### [](#s-text-conventions "Permalink to this headline")文本約定
本指南嘅文本中使用以下慣例：

-  URL 「*example.com*」係指您網站嘅基本 URL。請參閱下面嘅「導航」部分，以獲取有關如何指示網站內部URL嘅更多詳細信息。
- 您應該喺網站嘅用戶界面中睇到嘅文本顯示喺「*斜體*」中，例如：單擊「*保存配置*」。呢僅適用於嚟自軟件嘅用戶界面中嘅文本，而唔係上一個主題中輸入嘅文本。例如，喺有關編輯嘅主題中，您可能會睇到以下說明：單擊「*編輯*」喺關於頁面嘅行（「*編輯*」關於頁面係喺上一個主題中創建嘅）。
- 喺「*斜體*」中也顯示咗 URL，文件名和新引入嘅術語。
- 您應喺 `shell` 命令行鍵入嘅文本以等寬字體顯示，例如：


```php
drush cache:rebuild
```
- 喺本指南中，單詞「*目錄*」始終用於參考文件目錄（有啲人更鍾意調用「*文件夾*」）。

### [](#s-navigation "Permalink to this headline")導航
要喺本指南中執行大多數任務主題，您需要喺網站嘅管理界面中導航到一個或多個頁面。您可能會喺說明中睇到類似嘅內容（喺安裝咗基本軟件后，呢將更有意義）：

喺「*管理*」管理菜單中，導航到「*結構* > *分類法*（*`admin/structure/taxonomy`*）」。

噉嘅導航指令假設您已安裝咗核心工具欄模嚿，並且此示例意味着喺網站頂部嘅菜單欄中，您需要單擊「*管理*」以公開菜單選擇，然後單擊「*結構*」，然後「*分類法*」，最後，您將使用 URL 「*[`http://example.com/admin/structure/taxonomy`](http://example.com/admin/structure/taxonomy)*」喺頁面上（如果您嘅站點基礎URL為「*[http://example.com](http://example.com)*」）。

![Admin menu](/files/docs/user_guide/en/images/preface-conventions-top-menu.png)

呢個係另一個例子：

喺「*管理*」管理菜單中，導航到「*配置* > *系統* > *基本站點設置*（*`admin/config/system/site-information`*）」。

喺此示例中，單擊「*管理*」和「*配置*」后，您需要搵到頁面嘅「*系統*」部分，然後喺此中單擊「*基本站點設置*」。之後，您最終會出現「*[`http://example.com/admin/config/system/site-information`](http://example.com/admin/config/system/site-information)*」。

![System section of the Configuration page](/files/docs/user_guide/en/images/preface-conventions-config-system.png)

另一個注意事項：如果您使用嘅係標準管理核心七主題，則顯示管理界面中嘅許多「添加」撳鈕，上面有 +符號。例如，喺管理/內容上，添加新內容撳鈕顯示為「*+添加新內容*」。但係，呢個係主題依賴性嘅，並唔係撳鈕上文本嘅一部分（例如，屏幕讀取器唔一定會讀取它），因此喺本指南中，約定係唔要喺該指南上提及 +符號撳鈕。

### [](#s-filling-in-forms "Permalink to this headline")填充表格
本指南中嘅許多任務主題包括您將填寫 Web 表單嘅步驟。喺大多數情況下，將包含表單嘅屏幕捕獲圖像，以及您需要輸入每個表單欄位嘅值嘅表。例如，您可能會睇到像下方嘅表格，解釋咗如果您導航到「*配置* > * 系統 * > *站點信息*（*`admin/config/config/system/site-information`*）」時將睇到嘅網站信息表單。

  
  
| 欄位名稱 | 說明 | 示例值 |  
| ---- | ---- | ---- |  
| 站點詳細信息 > 站點名稱 | 您嘅網站名稱 | 任何城鎮農貿街市 |  
### 署名
英文版由 [Jennifer Hodgdon](https://www.drupal.org/u/jhodgdon) 撰寫/編輯。

粤语版由 [Cantonese translation team](https://github.com/Drupal-Cantonese) 翻譯，校對：空缺，一審：空缺，二審：空缺，責編：空缺

 Next [→ i.6. Guiding Scenario](/docs/user_guide/en/preface-scenario.html) Previous [← i.4. Reporting Problems](/docs/user_guide/en/preface-reporting.html)

