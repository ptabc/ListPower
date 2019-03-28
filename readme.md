# ListPower 清單力量

ListPower 讓你可以針對特定主題，與社群一起蒐集整理資料。

請參考基於 ListPower 開發的幾個線上網站：

- [Cafe Nomad - 最適合工作的咖啡廳清單](https://cafenomad.tw/)
- [Urschool - 大學科系教授評價網](https://urschool.org/)
- [SportsMap 運動地圖](https://isportsmap.com/)
- [ListBox 清單盒子 - 蒐集與整理各種實用、有趣的清單](https://listbox.app/)

## 功能

目前的「核心系統」有六大功能：

- 新增
- 編修
- 評分
- 留言
- 照片
- 標籤

# Roadmap

- 新增與編修權限設定功能
  - 目前清單資料是自由貢獻
  - 做成可設定「全開放」、「需審核」、「不可編輯」

- 模板主題功能
  - 開發 themes 功能，目前的主題僅是「listbox」平台主題
  - 讓特定主題的站能有自己的品牌主題
  - 開發 theme helper layer（可以是一堆 function 或是 Facade），方便創造主題時能專注在 html/css

- 用戶與清單權限功能
  - 每張清單各自有一或多個管理員
  - 開發管理面板，讓管理員能管理資料

- 完成地圖模組
  - 確定抓取座標的時間點
  - 設計座標不準確時，人為介入修正的機制
  - 可切換 map 來源（Google, MapBox, OpenMap, ...etc）

- 支援系統更新的檔案架構
  - open source 核心升級時，各專案要能無痛升級，包含：
  - 開發了各自主題的專案
  - 進行過功能客製化的專案（太 hardcore 硬改過就算了）