# 打造一個 Windows+Ubuntu 的雙系統 投影片
## 原始作者<br />Original author
宋岡哲(@Explorer09)
原始作品網站： https://www.dropbox.com/s/h0u60tjcwnsfo36/index.htm

## 授權條款<br />License
創用 CC-BY-SA 4.0 授權條款

## 第1章：下載Ubuntu及需要的軟體
下載投影片：
[[PDF](https://www.dropbox.com/s/nxmpncg7jmqwd9z/1-download-software.pdf?dl=0)]
[[ODP](https://www.dropbox.com/s/zgb8bywjrlycp9v/1-download-software.odp?dl=0)]
[[PPT](https://www.dropbox.com/s/hvcf7y8gq3yxe0i/1-download-software.ppt?dl=0)]

1. Ubuntu 光碟映像檔
2. EaseUS Partition Master

## 第2章：分割硬碟給Ubuntu
下載投影片：
[[PDF](https://www.dropbox.com/s/lr4gmmrz0ucvlvh/2-partition.pdf?dl=0)]
[[ODP](https://www.dropbox.com/s/f3yrceo5z5o5l92/2-partition.odp?dl=0)]
[[PPT](https://www.dropbox.com/s/yk5vkbvj15v5xtd/2-partition.ppt?dl=0)]

## 第3章：安裝Ubuntu 12.04 LTS
下載投影片：
[[PDF](https://www.dropbox.com/s/9iowzvv38i4ehry/3-install-ubuntu.pdf?dl=0)]
[[ODP](https://www.dropbox.com/s/vx6m9zob4xmg9qj/3-install-ubuntu.odp?dl=0)]
[[PPT](https://www.dropbox.com/s/gxisuydzviacco3/3-install-ubuntu.ppt?dl=0)]

## 第4章：與Windows分享檔案
下載投影片：
[[PDF](https://www.dropbox.com/s/fa9jigzlzf3b90m/4-windows-files.pdf?dl=0)]
[[ODP](https://www.dropbox.com/s/yi86tx1j5wh45nc/4-windows-files.odp?dl=0)]
[[PPT](https://www.dropbox.com/s/rxfelkort4pwrpa/4-windows-files.ppt?dl=0)]

1. 在 Ubuntu 上存取 Windows 檔案
2. 設定檔案系統標籤
3. 在 Windows 上讀 Ubuntu 檔案 (Ext2Fsd)
4. 網路上的芳鄰與 Samba

## 第5章：Ubuntu之後可灌的常用軟體
下載投影片：
[[PDF](https://www.dropbox.com/s/4uyw1qfklpel5zu/5-post-install.pdf?dl=0)]
[[ODP](https://www.dropbox.com/s/ztib0kpx571wqtn/5-post-install.odp?dl=0)]
[[PPT](https://www.dropbox.com/s/pwn4gs7u193mvy3/5-post-install.ppt?dl=0)]

1. ubuntu-restricted-extras (codecs, Flash, MS fonts, RAR)
2. Google Chrome
3. Skype
4. gcin/hime 輸入法
5. sudo apt-get 的意思，以及 PPA
6. LibreOffice
7. 顯卡驅動程式（包括雙顯卡支援）
8. Wine
9. 免費中文字型

## 第6章：當機生存指南
下載投影片：
[[PDF](https://www.dropbox.com/s/e7qk0vkkwdiz9lt/6-crash-handling.pdf?dl=0)]
[[ODP](https://www.dropbox.com/s/zw2bpw5ziibfqbz/6-crash-handling.odp?dl=0)]
[[PPT](https://www.dropbox.com/s/aujj1se5ypbgre5/6-crash-handling.ppt?dl=0)]

1. Ubuntu 的「系統監控」（工作管理員）
2. 文字模式和 top 的使用
3. 如何重啟圖形介面

## 第7章：加入社群
下載投影片：
[[PDF](https://www.dropbox.com/s/gd01d6b278khyeo/7-community.pdf?dl=0)]
[[ODP](https://www.dropbox.com/s/943dd9rv2x7d9ov/7-community.odp?dl=0)]
[[PPT](https://www.dropbox.com/s/k736715lnb2gqjq/7-community.ppt?dl=0)]

1. Ubuntu 的論壇與網路社團
2. 提問與找資料的方法
3. 認識不同的 Ubuntu 發行版

## 附錄A：雙系統常見問題
下載投影片：
[[PDF](https://www.dropbox.com/s/nxhmt4kx7whybi6/appendix-a.pdf?dl=0)]
[[ODP](https://www.dropbox.com/s/gib8yg8nm4fqcap/appendix-a.odp?dl=0)]
[[PPT](https://www.dropbox.com/s/gdvs98qvl9rn5x6/appendix-a.ppt?dl=0)]

1. 如何設定預設開機的作業系統
2. 重灌 Windows 後，如何開機到 Ubuntu

![「軟體來源」視窗→「其它軟體」頁籤，所有第 5 章所加入的 APT 來源列](./額外螢幕擷圖/8-ppas-all.png)

在第5章裡面，你總共會新增4個套件庫來源。

![「更新管理員」視窗，提示訊息說有新 Ubuntu 發行版 '14.04' 可供升級](./額外螢幕擷圖/8-upgrade.png)

如果你要從 Ubuntu 12.04 升級到 14.04 ，可以從「更新管理員」裡面按「升級」來完成。這個升級按鈕會在 7 月 24 日， Ubuntu 14.04.1 發行時出現。

如果要透過命令列升級，請用 "sudo do-release-upgrade" 。

## Source

* 原始螢幕擷圖
* 投影片樣板 (ODP)

## 如何對本專案做出貢獻<br />How to contribute to this project
### 回報問題與改善建議<br />Report issues and improvement suggestions
* 發現問題或是有改善本專案的建議的話請到[本專案的問題追蹤系統(issue tracker)](https://github.com/Vdragon/ubuntu-dual-boot/issues)建檔回報

### 貢獻本專案內容
* 要貢獻內容的話歡迎克隆(clone)本專案的版本倉庫至您的電腦中，建立並切換至一個新的 Git 分支(branch)完成編輯後提交(commit)為一個新版本，推送到您的 GitHub 版本倉庫再跟我們的版本倉庫發出拉取請求(pull request)

### 宣傳本專案給別人

### 翻譯本專案內容
如果您熟悉其他語言，歡迎將本專案之內容翻譯為不同的語言
