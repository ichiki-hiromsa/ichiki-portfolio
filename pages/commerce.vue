<template>
    <v-row>
      <v-col class="text-center">
        <section class="py-24">
          <div class="mx-auto">
            <h2>特定商取引法に基づく表記</h2>
            <v-card class="mx-auto mt-10 px-4" flat>
              <div class="d-flex">
                <p class="info-title">
                  事業者名
                </p>
                <p class="info-content">
                  市来浩勝
                </p>
              </div>
              <div class="d-flex">
                <p class="info-title">
                  代表者
                </p>
                <p class="info-content">
                  市来浩勝
                </p>
              </div>
              <div class="d-flex">
                <p class="info-title">
                  所在地
                </p>
                <p class="info-content">
                  〒534-0027 大阪府大阪市都島区中野町5-6-19-202
                </p>
              </div>
              <div class="d-flex">
                <p class="info-title">
                  電話番号
                </p>
                <p class="info-content">
                  請求があった際に遅滞なく開示します
                </p>
              </div>
              <div class="d-flex">
                <p class="info-title">
                  メールアドレス
                </p>
                <p class="info-content">
                  busi.ich.hir@gmail.com
                </p>
              </div>
              <div class="d-flex">
                <p class="info-title">
                  販売価格
                </p>
                <p class="info-content">
                  サービスごとのページに記載しています
                </p>
              </div>
              <div class="d-flex">
                <p class="info-title">
                  販売価格以外でお客様に発生する金銭
                </p>
                <p class="info-content">
                  サイトの閲覧・コンテンツ購入・ダウンロード等に必要となるインターネット接続料金、通信料金等はお客様の負担となります。
                </p>
              </div>
              <div class="d-flex">
                <p class="info-title">
                  キャンセル
                </p>
                <p class="info-content">
                  代金支払い完了後のキャンセルには、基本的に対応しておりません。
                </p>
              </div>
              <div class="d-flex">
                <p class="info-title">
                  お支払い方法
                </p>
                <p class="info-content">
                  クレジットカード決済（Stripe）
                </p>
              </div>
              <div class="d-flex">
                <p class="info-title">
                  代金支払時期
                </p>
                <p class="info-content">
                  申し込み時
                </p>
              </div>
              <div class="d-flex">
                <p class="info-title">
                  デジタルアイテム等の利用が可能となる時期
                </p>
                <p class="info-content">
                  購入に関するページに特別な定めを置いている場合を除き、購入取引完了後、直ちにご利用いただけます
                </p>
              </div>
            </v-card>
          </div>        
        </section>
      </v-col>
    </v-row>
  </template>
  
  <style>
  .py-24 {
    padding-top: 96px;
    padding-bottom: 96px;
  }
  
  h2 {
    font-size: 48px;
  }
  
  .info-title {
    width: 30%;
    border-bottom: solid 2px;
    padding-top: 16px;
    padding-bottom: 16px;
    text-align: left;
    font-weight: bold;
    font-size: 18px;
  }
  
  .info-content {
    width: 100%;
    border-bottom: solid 1px;
    text-align: left;
    padding-left: 6rem;
    padding-top: 16px;
    padding-bottom: 16px;
    font-size: 18px;
  }
  
  .mx-auto {
    margin-right: auto;
    margin-left: auto;
  }
  
  @media (min-width: 768px) {
    .px-4 {
      padding-left: 1rem;
      padding-right: 1rem;
    }
  }
  </style>