# DesignNote

## 前述
這裡記錄著一個從Unity開始寫專案的架構心路歷程，不會是主題式的文章，是在哪撞壁了或是在哪踩到泥沼後的反思，未必是優解，但學會了就是我的了

## God Object

## Separation of concerns (SoC）
關注點分離

## Architecture

## MVC/MVP/MVVM

## Rx

## Task
超長回調

## Clean Architecture
Robert C. Martin，也被稱為鮑勃叔叔

### 價值
* 有效測試策略
* Screaming architecture, 查看結構時，您會了解應用程序的功能，而不是查看技術細節
* 業務邏輯都在一個用例中，因此很容易找到並且不會在其他任何地方重複
* 拆分為微服務

### 成員
Entity
* 域對象

Usecase
* 業務操作：這是您可以對應用程序執行的操作。期望每個業務操作都有一個用例
* 用例不知道是誰觸發了它以及結果將如何呈現

Interfaces / Adapters
* 實現用例定義的接口



入門:
* [[譯]Android架構：Part1——那些年我們犯過的錯](https://codertw.com/%E7%A8%8B%E5%BC%8F%E8%AA%9E%E8%A8%80/657211/)
* [為什麼你需要Use Case/Interactors](https://medium.com/@nukisnuke/%E7%82%BA%E4%BB%80%E9%BA%BC%E4%BD%A0%E9%9C%80%E8%A6%81use-case-interactors-99de03696037)


## DI

## VIPER

## CQRS

## 領域驅動設計 Domain-driven design (DDD)

## WIP
尤其是像我這類從遊戲引擎開始的很容易從畫面開始思考，
