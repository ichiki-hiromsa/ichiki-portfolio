<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="8">
      <v-card>
        <v-card-title class="headline justify-center">
          Self-introduction
        </v-card-title>
        <v-row>
          <v-col cols="12" md="5" class="pa-0 imageContent">
            <!-- <img src="/illust.png" alt="似顔絵" width="250" height="250"> -->
            <img class="image" src="/illust.png" alt="似顔絵">
          </v-col>
          <v-col cols="12" md="7" class="pa-0">
            <v-card-text>
              <p>1992年生まれの大阪出身、大阪在住のエンジニア。</p>
              <p>大学では素粒子宇宙物理学を専攻し、就職を機にIT業界へ。</p>
              <p>大手のSIerで3年を過ごし、2021年からフリーランスへ転向。</p>
              <p>現在は、エージェント経由で企業に入って仕事をしつつ、</p>
              <p>個人で開発も請けている。</p>
              <p>エンジニアの価値向上を目的に、<br>勉強会やオンラインコミュニティの運営も行なっている。</p>
            </v-card-text>
          </v-col>
        </v-row>
      </v-card>
      <v-card class="mt-8 pb-2">
        <v-card-title class="headline justify-center">
          Achievements
        </v-card-title>
        <v-card class="mx-2 mt-2">
          <div class="d-flex">
            <div style="width:50%;" class="pa-4">
              <div>
                <p class="achievements-title">高須クリニックLINEbot</p>
                <p>主にLIFFの実装を担当しました</p>
              </div>
            </div>
            <div style="width:50%;" class="achievements-container">
              <div class="achievements-wrap">
                <v-btn href="https://liff.line.me/1645278921-kWRPP32q/?accountId=xax6608y" target="_blank" outlined class="to-line-bot-btn">
                  <span>LINEbot</span>
                  <v-icon style="right:0">mdi-pan-right</v-icon>
                </v-btn>
              </div>
            </div>
          </div>
        </v-card>
        <v-card class="mx-2 mt-2">
          <div class="d-flex">
            <div style="width:50%;" class="pa-4">
              <div>
                <p class="achievements-title">ラブラボLINEbot</p>
                <p>シナリオの実装を担当しました</p>
              </div>
            </div>
            <div style="width:50%;" class="achievements-container">
              <div class="achievements-wrap">
                <v-btn href="https://page.line.me/?accountId=rublab&openerPlatform=native&openerKey=keep" target="_blank" outlined class="to-line-bot-btn">
                  <span>LINEbot</span>
                  <v-icon style="right:0">mdi-pan-right</v-icon>
                </v-btn>
              </div>
            </div>
          </div>
        </v-card>
        <v-card class="mx-2 mt-2">
          <div class="d-flex">
            <div style="width:50%;" class="pa-4">
              <div>
                <p class="achievements-title">保育ギフトLINEbot</p>
              </div>
            </div>
            <div style="width:50%;" class="achievements-container">
              <div class="achievements-wrap">
                <v-btn href="https://lin.ee/0RHbs3x" target="_blank" outlined class="to-line-bot-btn">
                  <span>LINEbot</span>
                  <v-icon style="right:0">mdi-pan-right</v-icon>
                </v-btn>
              </div>
            </div>
          </div>
        </v-card>
      </v-card>
      <v-card class="mt-8 pb-2">
        <v-card-title class="headline justify-center">
          Services
        </v-card-title>
        <v-card class="mx-2 mt-2">
          <div class="d-flex">
            <div style="width:50%;" class="pa-4">
              <div>
                <p class="achievements-title">勉強会</p>
                <p>月に一度、もくもく会を開催しています<br>開催日等は右のリンクのオープンチャットにて告知しています</p>
                <p>時期によりますが、集まったメンバーで共同開発をすることもあります。</p>
                <p>共同開発の成果物の<a href="https://reserve-30096.web.app/">予約システム</a></p>
                <p>参加費：1,000 円（税込）</p>
              </div>
            </div>
            <div style="width:50%;" class="achievements-container">
              <div class="achievements-wrap">
                <v-btn href="https://line.me/ti/g2/Y02gbPoBTyc1tfegp5qr-UgQeGo-9nWlWMjTcQ?utm_source=invitation&utm_medium=link_copy&utm_campaign=default" target="_blank" outlined class="to-line-bot-btn">
                  <span>LINK</span>
                  <v-icon style="right:0">mdi-pan-right</v-icon>
                </v-btn>
              </div>
            </div>
          </div>
        </v-card>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
import { mdiLock } from '@mdi/js';
export default {

}
</script>

<style scoped>
.achievements-title {
  font-weight: bold;
  font-size: 24px;
}

.to-line-bot-btn {
  background-color: #00D051;
  color: white;
  border-radius: 1.5rem;
}

.achievements-container {
  padding: 16px;
  display: flex;
  justify-content: center;
}

.achievements-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
}

.image{
  width: 70%;
}

.imageContent{
  align-items: center;
  justify-content:
  center;display: flex;
}
</style>