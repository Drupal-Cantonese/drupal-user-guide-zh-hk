#  1.1　概念：Drupal 作為內容管理系統
最後 [updated](/node/2827284/discuss) 於2023年2月21日

### [](#s-what-is-a-content-management-system "Permalink to this headline")乜係內容管理系統？
內容管理系統（CMS）係一種軟件工具，可畀用戶使用智能手機，平板電腦或台式計數器上嘅 Web 瀏覽器從網企上添加，發佈，編輯或刪除內容。通常，CMS 軟件係用腳本語言編寫嘅，其腳本喺安裝資料庫和 Web 伺服器嘅計數器上運行。該網站嘅內容和設置通常存儲喺資料庫中，對於每個頁面請求，腳本將資料庫中嘅信息和「*資產*」（屬於 CMS 嘅一部分或已上傳內容，JavaScript 文件，CSS 文件，圖像文件等）合喺一起嚟構建網站嘅頁面。

 CMS 運行嘅操作系統嘅組合，編寫嘅腳本語言，其存儲信息嘅資料庫以及運行腳本以檢索信息嘅Web伺服器並將其返回到網站訪問者嘅 Web 中瀏覽器被稱為「*堆棧*」，CMS 可以運行；Linux 操作系統，Apache Web 伺服器，MySQL 資料庫和 PHP 腳本語言嘅常用組合被稱為「*LAMP 堆棧*」。

### [](#s-what-is-drupal "Permalink to this headline")乜係 Drupal？
 Drupal 係基於「*LAMP 堆棧*」嘅靈活 CMS，具有模嚿化設計，可以通過安裝和卸載「*模嚿*」添加和刪除功能，並允許通過安裝和卸載「*主題*」嚟更改網站嘅整體外觀。基本 Drupal 下載稱為 Drupal Core，包含運行基本 CMS 功能，幾個可選模嚿和主題以及許多JavaScript，CSS和圖像資產所需嘅PHP腳本。可以從[ 「* drupal.org *」 ](https://www.drupal.org)網企上下載許多其佢模嚿和主題。

 Drupal 也可以喺其佢技術堆棧上運行：

- 操作系統可以係Windows或Mac OS，而唔係Linux。
-  Web伺服器可以係NGINX或IIS，而唔係Apache。
- 資料庫可以係postgresql或sqlite，而唔係mySQL，也可以係與MySQL兼容嘅替代品，例如Mariadb或Percona。

其佢操作系統，Web伺服器和資料庫也可以使工作；但係，軟件使用嘅腳本係用PHP編寫嘅，因此無法更改。

### [](#s-what-are-the-reasons-for-using-drupal "Permalink to this headline")使用 Drupal 嘅原因係咩？
構建網站時，您可以選擇使用許多現有嘅CMS軟件包和託管服務之一，開發自己嘅CMS或唔使用CMS構建網站。呢個係您可能選擇使用 Drupal 嘅啲原因：

- 建立一個帶有靜態HTML頁面嘅小型，簡單嘅網站並唔困難，您可以好快獲得一個簡單嘅網站。最初，喺CMS中設置網站通常需要更多嘅時間，但係為您帶嚟咗喺線編輯嘅好處（對於經驗唔足嘅內容維護者而言更容易），統一性（對於較大嘅網站使用靜態 HTML 更難維護），以及需要資料庫嘅更複雜功能嘅可能性。
- 啲CMS軟件係特殊嘅；例如，您可以使用呢啲軟件包和託管服務嚟構建博客或俱樂部會員網站。相比之下，Drupal係通用CMS。如果您要建立專用網站，則可以選擇使用專用嘅CMS；但係，如果您嘅網站甚至略微超出咗預期目嘅，嗰麼使用通用CMS可能會更好，而唔係試圖調整專用CMS。
- 構建自己嘅CMS型軟件似乎好有吸引力。但係，使用Drupal（例如Drupal）嘅通用CMS通常係一個更得嘞主意，因為基本CMS功能（例如用戶帳戶和內容管理）具有成千上萬嘅開發人員實踐，包括多年嘅用戶測試，錯誤修復和安全性強化。
- 啲CMS軟件包購買許可證嘅成本昂貴。有啲係免費嘅或有免費版本嘅，但具有限制性許可，唔允許您進行修改和擴展。您可能更鍾意使用具有限制性軟件許可嘅軟件包（例如Drupal），並且由全球社區開發。有關此主題嘅更多信息，請參見[Section 1.6, 「Concept: The Drupal Project」](/docs/user_guide/en/understanding-project.html " The Drupal Project")。

### [](#s-related-topics "Permalink to this headline")相關主題
- [Section 1.2, 「Concept: Modules」](/docs/user_guide/en/understanding-modules.html " Modules")
- [Section 1.3, 「Concept: Themes」](/docs/user_guide/en/understanding-themes.html " Themes")
- [Section 1.4, 「Concept: Distributions」](/docs/user_guide/en/understanding-distributions.html " Distributions")
- [Section 1.6, 「Concept: The Drupal Project」](/docs/user_guide/en/understanding-project.html " The Drupal Project")

### [](#s-additional-resources "Permalink to this headline")附加資源
- [「*Drupal.org*」 community documentation page "Understanding Drupal: Overview"](https://www.drupal.org/docs/understanding-drupal/overview)
- [「*Drupal.org*」 page "FAQ" (Frequently Asked Questions)](https://www.drupal.org/about/faq)
- [「*Drupal.org*」 page "Case Studies"](https://www.drupal.org/case-studies)
- [Wikipedia page "Content management systems"](https://en.wikipedia.org/wiki/Content_management_system)
- [Wikipedia page "Modular design"](https://en.wikipedia.org/wiki/Modular_design)

### 署名
英文版由 [Kristof van Tomme](https://www.drupal.org/u/kvantomme)（任職于 [Pronovix](https://pronovix.com/)），[Jennifer Hodgdon](https://www.drupal.org/u/jhodgdon) 和 [Michael Lenahan](https://www.drupal.org/u/michaellenahan)（任職于 [erdfisch](https://erdfisch.de)）撰寫和編輯。

粤语版由 [Cantonese translation team](https://github.com/Drupal-Cantonese) 翻譯，校對：空缺，一審：空缺，二審：空缺，責編：空缺

 Next [→ 1.2. Concept: Modules](/docs/user_guide/en/understanding-modules.html) Previous [← i.6. Guiding Scenario](/docs/user_guide/en/preface-scenario.html)

