<template>
  <ion-page>
    <ion-app>
      <ion-content>
        <ion-fab vertical="bottom" horizontal="end" slot="fixed">
          <ion-fab-button>
            <ion-icon
              :icon="add"
              class="add-icon"
              style="color: white"
              size="large"
            ></ion-icon>
          </ion-fab-button>
        </ion-fab>
        <ion-grid>
          <ion-row class="ion-justify-content-between header">
            <ion-col size="3">Kolam</ion-col>
            <ion-col size="2">
              <ion-icon
                :icon="filter"
                size="small"
                style="margin-right: 10px; color: white"
              />
              <ion-icon :icon="funnel" size="small" style="color: white" />
            </ion-col>
          </ion-row>
          <ion-row>
            <ion-list>
              <ion-card>
                <ion-card-header>
                  <ion-row class="ion-justify-content-between line">
                    <ion-col size="3" class="head ion-text-justify"
                      >Alpha</ion-col
                    >
                    <ion-col size="3">
                      <ion-button class="btnAktif" fill="solid"
                        >Aktif</ion-button
                      >
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="calendarOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">01-09-2022</div>
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="todayOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">90 hari</div>
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="fishOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">200 Ekor</div>
                    </ion-col>
                  </ion-row>
                </ion-card-header>
              </ion-card>
              <ion-card>
                <ion-card-header>
                  <ion-row class="ion-justify-content-between line">
                    <ion-col size="3" class="head ion-text-justify"
                      >Beta</ion-col
                    >
                    <ion-col size="3">
                      <ion-button fill="solid" class="btnTdkAktif"
                        >Tidak Aktif</ion-button
                      >
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="calendarOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">01-09-2022</div>
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="todayOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">90 hari</div>
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="fishOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">200 Ekor</div>
                    </ion-col>
                  </ion-row>
                </ion-card-header>
              </ion-card>
              <ion-card>
                <ion-card-header>
                  <ion-row class="ion-justify-content-between line">
                    <ion-col size="3" class="head ion-text-justify"
                      >Charlie</ion-col
                    >
                    <ion-col size="3">
                      <ion-button class="btnAktif" fill="solid"
                        >Aktif</ion-button
                      >
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="calendarOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">01-09-2022</div>
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="todayOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">90 hari</div>
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="fishOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">200 Ekor</div>
                    </ion-col>
                  </ion-row>
                </ion-card-header>
              </ion-card>
              <ion-card>
                <ion-card-header>
                  <ion-row class="ion-justify-content-between line">
                    <ion-col size="3" class="head ion-text-justify"
                      >Delta</ion-col
                    >
                    <ion-col size="3">
                      <ion-button class="btnAktif" fill="solid"
                        >Aktif</ion-button
                      >
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="calendarOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">01-09-2022</div>
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="todayOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">90 hari</div>
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="fishOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">200 Ekor</div>
                    </ion-col>
                  </ion-row>
                </ion-card-header>
              </ion-card>
              <ion-card>
                <ion-card-header>
                  <ion-row class="ion-justify-content-between line">
                    <ion-col size="3" class="head ion-text-justify"
                      >Epsilon</ion-col
                    >
                    <ion-col size="3">
                      <ion-button class="btnAktif" fill="solid"
                        >Aktif</ion-button
                      >
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="calendarOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">01-09-2022</div>
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="todayOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">90 hari</div>
                    </ion-col>
                  </ion-row>
                  <ion-row class="item-icon">
                    <ion-col size="1">
                      <ion-icon :icon="fishOutline" />
                    </ion-col>
                    <ion-col size="5">
                      <div class="icon-detail">200 Ekor</div>
                    </ion-col>
                  </ion-row>
                </ion-card-header>
              </ion-card>
            </ion-list>
          </ion-row>
        </ion-grid>
      </ion-content>
    </ion-app>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import {
  IonApp,
  IonContent,
  IonCol,
  IonGrid,
  IonRow,
  IonCard,
  IonCardHeader,
  // IonCardSubtitle,
  // IonCardTitle,
  // IonSlides,
  // IonSlide,
  IonPage,
} from "@ionic/vue";
import { funnel, filter, add, todayOutline, calendarOutline, fishOutline } from "ionicons/icons";

export default defineComponent({
  name: "KolamPage",
  components: {
    IonApp,
    IonContent,
    IonCol,
    IonGrid,
    IonRow,
    IonCard,
    IonCardHeader,
    // IonCardSubtitle,
    // IonCardTitle,
    // IonSlides,
    // IonSlide,
    IonPage,
  },
  setup() {
    const slideOpts = {
      initialSlide: 2,
      speed: 400,
    };
    return { slideOpts, funnel, filter, add, todayOutline, calendarOutline, fishOutline };
  },
});
</script>
<style scoped>
* {
  font-family: Poppins;
}

ion-list ion-card {
  margin-bottom: 20px;
}

ion-icon {
  font-size: 24px;
  color: black;
}

.item-icon ion-col {
  margin: 0 5px 0 0;
  padding: 0;
}

.icon-detail {
  font-size: 16px;
  font-weight: 600;
  color: black;
  margin: 0;
  padding: 0;
}

.line {
  margin: 0 0 10px 0;
  padding: 0;
  border-bottom: 3px solid black;
}

ion-card-header {
  padding-top: 10px;
  padding-bottom: 15px;
  text-align: left;
}

ion-card {
  margin-top: 2px;
  margin-bottom: 5px;
  border-radius: 15px;
  width: 41vh;
}

.child-subtitle {
  font-size: 20px;
}

ion-item {
  margin: 0;
  padding: 0;
}

.headerWaterC {
  font-weight: 600;
  font-size: 30px;
  left: 50px;
  color: black;
  margin-bottom: 10px;
}

.head {
  font-size: 18px;
  margin-top: 15px;
  padding: 0;
  color: black;
  font-weight: 600;
}

.btnAktif {
  margin-bottom: 5px;
  padding: 1px;
  height: 40px;
  width: 100%;
}

.btnTdkAktif {
  margin-bottom: 5px;
  padding: 0;
  margin-right: 120px;
  height: 40px;
  transform: translateX(-35px);
}

.textWaterC {
  margin-bottom: 10px;
}

.add-icon {
  stroke-width: 20px;
}

ion-button.btnAktif {
  --background: #1b7c1a;
  --color: white;
}

ion-button.btnTdkAktif {
  --background: #952229;
  --color: white;
}

ion-fab-button{
  --ionicon-stroke-width: 100px;
}

.header{
  padding:10px;
}

</style>
