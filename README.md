# VBlog
![](https://img.shields.io/github/languages/top/github-laziji/VBlog.svg?style=flat)
![](https://img.shields.io/github/stars/gitHub-laziji/VBlog.svg?style=social)

## 目錄
- [簡介](#簡介)
- [演示地址](#演示地址)
- [專案原始碼](#專案原始碼)
- [專案特點](#專案特點)
- [更新記錄](#更新記錄)
- [快速使用](#快速使用)

## 簡介

部落格可搭建在 GitHub Pages 上,
文章數據儲存於gist 中, 通過Github API 與數據進行互動, 實現無後臺、可動態發佈文章的部落格系統

> 最近暫無更新計劃


## 演示地址
[https://github-laziji.github.io][1]

## 專案原始碼
[https://github.com/GitHub-Laziji/vblog][3]

## 專案特點

- [x] 基於 GitHub Pages 無需伺服器
- [x] 改進傳統 GitHub Pages 不能動態發佈的缺陷
- [x] 包含電腦端和移動端
- [x] 單頁面應用


## 更新記錄

#### 2018.5.19 更新
- 增加使用幫助頁面
- 修復沒有README.md時候出現的BUG

#### 2018.5.16 更新
- 顯示粉絲數量
- 增加粉絲詳情頁面

#### 2018.5.15 更新
- 粉絲頁面優化沒有粉絲的情況
- 修改有的圖片越界
- 配置增加是否自動播放音樂
- 去除預設音樂

#### 2018.5.13 更新
- 電腦端增加社交圈, 檢視粉絲和關注的使用者

#### 2018.5.11 更新
- 移動端增加部落格, 專案, 個人中心, 移動端和PC端共用API, 頁面獨立 
- 修復文章樣式奇怪的BUG

#### 2018.5.8 更新
- 增加配置選項
- 改善富文字編輯器

#### 2018.5.6 更新
- 狀態列增加音樂播放器

#### 2018.5.5 更新
- 增加了系統配置, 可以動態修改標題, 描述, 背景等配置 

#### 2018.5.2 更新
- 增加部落格和專案列表的分頁 
- 增加分享鏈接 
- 改進Token繫結驗證 
- 修改程式碼結構 

#### 2018.4.30 更新
- 新增了從github獲取個人開源專案的功能,顯示資訊更加全面,顯示開源專案列表
- Readme 從github動態獲取

#### 2018.4.29 更新
- 增加個人資訊的狀態列
- 修復發圖片博文的BUG 



## 快速使用
搭建部落格只需2步
- 點選github頭像旁邊的 "+" 號 選擇 ```Import repository ```克隆地址填 ```https://github.com/GitHub-Laziji/GitHub-Laziji.github.io ```專案名填 ```你的使用者名稱.github.io ```
- 克隆完成後 修改檔案 ```/static/configuration.json``` 中的 ```githubUsername``` 為自己的github使用者名稱


類似演示地址其中 GitHub-Laziji 為我的使用者名稱


現在 ```https://你的使用者名稱.github.io``` 就是你的個人部落格了,例如[https://github-laziji.github.io][1]



#### 獲取Token

在 ```github > settings > Developer settings > Personal access tokens```  勾選```gist``` 和 ```repo```許可權 獲取```Token```


------


作者 *Laziji*



  [1]: https://github-laziji.github.io
  [2]: https://github.com/GitHub-Laziji/GitHub-Laziji.github.io
  [3]: https://github.com/GitHub-Laziji/vblog
