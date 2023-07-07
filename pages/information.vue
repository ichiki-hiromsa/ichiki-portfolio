<template>
  <v-row>
    <v-col class="text-center">
      <section class="py-24">
        <div class="mx-auto">
          <h2>事業者情報</h2>
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
  width: 20%;
  border-bottom: solid 2px;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: left;
  font-weight: bold;
  font-size: 20px;
}

.info-content {
  width: 100%;
  border-bottom: solid 1px;
  text-align: left;
  padding-left: 6rem;
  padding-top: 16px;
  padding-bottom: 16px;
  font-size: 20px;
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