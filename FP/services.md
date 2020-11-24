## Member Service
- newest version
- owners
  - Jacky
- description: 
- cluster
- use product

## Role Service
- newest version:2.0.3
- owners
  - Shiny
- description: 
  '''
    member 的role 關係
    user policy
    ui policy
    permition
  '''
- cluster
- use product
  ```
  paybnb(2.0.3)
  betway(2.0.3) future
  ```

## Wallet Service
- newest version
- owners
  - ken  
- description: 
- cluster
- use product

## Betpull Service
- newest version
- owners
  - Leo
- description: 
  ```
  netium 重疊
  與各個Game vendor搜集資料(Derivc)(下注資料 其他原始資料)
  ```
- cluster
- use product
  - stage

## Oauth Service
- newest version
- owners
  - Brad
- description: 
  - 第三方登入的統一街口
- cluster
  - paybnbbo, paybnb clien(1.1.7)
  - paybnb sea(1.1.7)
- use product
  - payBnb bo ad login,paybnb bo password login,paybnb login

## Transaction Service
- newest version
- owners
  - Leo
- description: 
  ```
    確保service間 transaction 安全性 可rollback
  ```
- cluster
- use product
  - stage

## ING Service 
- newest version:1.0.4
- owners
  - shiny
  - Jacky
- description: 
  ```
  搜集使用者操作記錄
  每個user門檻值
  紀錄user event
  mq consumer
  snap shot by time duration threshold
  達到門檻值執行call back
  call back delay 為了檢查錯誤
  recovery 已經call back 則不管它
  ```
- cluster
- use product
  ···
  RB88(1.0.3 old,1.0.4 next)
  ···

## ThirdParty Payment Service
- newest version
- owners
  - Nick
- description: 
- cluster
- use product

## BackOffice Service*
- newest version
- owners
- description: 
- cluster
- use product

## Velocity Service
- newest version
- owners
  - Jacky
- description: 
- cluster
- use product

## Captcha Service
- newest version
- owners
  - Patil
- description: 
- cluster
- use product

## Domain Service
- newest version
- owners
  - eric
- description:
  ```
  動態變更domain
  ``` 
- cluster
- use product

## Verification Service
- newest version
- owners
  - Andrew
- description:
  ```
  1. 字串加解密
  2. send verification message (OTP)
  3. OCR 電子回單 圖片轉json
  ``` 
- cluster
- use product
  ```
  只上到stage
  ```


## Transmit Service
- newest version
- owners
  - Nick
- description: 
- cluster
- use product

## Rebate Service
- newest version
- owners
  - HungWen
  - 小朱
- description: 
- cluster
- use product

## Bonus Service
- newest version
- owners
  - Wilson
- description: 
  ```
  聲請bonus
  bonus 的狀態 prebonus(申請 達標 已發獎) postbonus(申請 領獎 驗證 解鎖)
  bonus 的規則
  ```
- cluster
- use product
  ```
  RB88(1.0.6)
  ```

## Auto Update Service
- newest version
- owners
  - 小豬
- description: 
- cluster
- use product
  - betway
  - paybnb sea agent app
  - paybnb agent app

## Reward Service
- newest version
- owners
  - Jacky
- description: 
- cluster
- use product

## Ranking Service
- newest version
- owners
  - Nick
- description: 
- cluster
- use product

## Mission Service
- newest version
- owners
  - Leo
- description: 
  ```
  要重新設計
  ```
- cluster
- use product
  - stage

## Achievement Service
- newest version
- owners
  - Ｃhien Yu
- description: 
- cluster
- use product
  - stage

## Trusted Domain Service
- newest version
- owners
  - Andrew 
- description:          
  - 黑白名單的 CRUD
- cluster
- use product

## Identity Service OAuth1.0
- newest version
- owners
- description: 
- cluster
- use product

## Game Service
- newest version
- owners
  - Andrew
- description: 
···
主要任務：統一的Game api給user,user 提供vendor id
1. 遊戲內容
2. 餘額查詢
3. 會員資料(如果會員資料在我們這邊)
下注功能改到bets service做
···
- cluster
- use product

## paybnb bo
- newest 1.1.1
- use service
  - role
  - oauth
  - paybnb service
  - transmit
## Paybnb Service
- newest version
- owners
  - ChienYu 
- description: 
- cluster
- use product
## paybnb api
- newest
- use service
  - paybnb service
  - transmit
  - oauth
## Paybnb Service sea

## Paybnb api sea
- use service
  - paybnb service
  - transmit
  - oauth

## cert Service
- description
  ```
  IOS app 包板
  ```

## bet Service

## 