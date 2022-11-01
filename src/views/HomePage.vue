<template>
  <ion-page>
    <ion-app>
      <ion-content>
        <ion-grid>
          <ion-row> <span class="header">Home</span> </ion-row>
          <ion-row>
            <ion-col>
              <ion-card>
                <ion-card-header>
                  <ion-card-title>Kolam</ion-card-title>
                  <ion-card-subtitle>10</ion-card-subtitle>
                </ion-card-header>
              </ion-card>
            </ion-col>
            <ion-col>
              <ion-card>
                <ion-card-header>
                  <ion-card-title>Kolam Aktif</ion-card-title>
                  <ion-card-subtitle>8</ion-card-subtitle>
                </ion-card-header>
              </ion-card>
            </ion-col>
          </ion-row>
          <ion-row>
            <ion-col>
              <ion-card>
                <ion-card-header>
                  <ion-card-title>Ikan Hidup</ion-card-title>
                  <ion-card-subtitle
                    >182
                    <span class="child-subtitle">Ekor</span></ion-card-subtitle
                  >
                </ion-card-header>
              </ion-card>
            </ion-col>
            <ion-col>
              <ion-card>
                <ion-card-header>
                  <ion-card-title>Ikan Mati</ion-card-title>
                  <ion-card-subtitle
                    >89
                    <span class="child-subtitle">Ekor</span></ion-card-subtitle
                  >
                </ion-card-header>
              </ion-card>
            </ion-col>
          </ion-row>
          <ion-row>
            <ion-col>
              <ion-card>
                <ion-card-header>
                  <ion-card-title>Panen 2022</ion-card-title>
                  <ion-card-subtitle
                    >109
                    <span class="child-subtitle">Kg</span></ion-card-subtitle
                  >
                </ion-card-header>
              </ion-card>
            </ion-col>
            <ion-col>
              <ion-card>
                <ion-card-header>
                  <ion-card-title>Total Pakan</ion-card-title>
                  <ion-card-subtitle
                    >223
                    <span class="child-subtitle">Kg</span></ion-card-subtitle
                  >
                </ion-card-header>
              </ion-card>
            </ion-col>
          </ion-row>
        </ion-grid>

        <ion-grid>
          <ion-row> <span class="header">Total Berat Ikan</span> </ion-row>
          <ion-row class="ion-justify-content-start">
            <ion-slides pager="true" :options="slideOpts">
              <ion-slide>
                <ion-row>
                  <h1>
                    <ion-card>
                      <img
                        alt="Silhouette of mountains"
                        src="https://lh6.googleusercontent.com/proxy/XOemItRPdpqWiRnZ1dKYbPuXYFQ-PKOGLxoRd99-UdaRli1-yM6lx2qEFVL2fFAGif-u1wsdW9wW_6r-DIM_TvKYtOh9Jd3-HCcVGgtEAO2S4Hnw=w1200-h630-p-k-no-nu"
                        style="width: 150px; height: 180px"
                      />
                      <ion-card-header>
                        <div class="headerSlider">Lele</div>
                        <div class="ion-text-left weight">
                          <div class="blue">200 Kg</div>
                        </div>
                      </ion-card-header>
                    </ion-card>
                  </h1>

                  <h1>
                    <ion-card>
                      <img
                        alt="Silhouette of mountains"
                        src="https://lh6.googleusercontent.com/proxy/XOemItRPdpqWiRnZ1dKYbPuXYFQ-PKOGLxoRd99-UdaRli1-yM6lx2qEFVL2fFAGif-u1wsdW9wW_6r-DIM_TvKYtOh9Jd3-HCcVGgtEAO2S4Hnw=w1200-h630-p-k-no-nu"
                        style="width: 150px; height: 180px"
                      />
                      <ion-card-header>
                        <div class="headerSlider">Lele</div>
                        <div class="ion-text-left weight">
                          <div class="blue">200 Kg</div>
                        </div>
                      </ion-card-header>
                    </ion-card>
                  </h1>
                </ion-row>
              </ion-slide>
              <ion-slide>
                <ion-row>
                  <h1>
                    <ion-card>
                      <img
                        alt="Silhouette of mountains"
                        src="https://lh6.googleusercontent.com/proxy/XOemItRPdpqWiRnZ1dKYbPuXYFQ-PKOGLxoRd99-UdaRli1-yM6lx2qEFVL2fFAGif-u1wsdW9wW_6r-DIM_TvKYtOh9Jd3-HCcVGgtEAO2S4Hnw=w1200-h630-p-k-no-nu"
                        style="width: 150px; height: 180px"
                      />
                      <ion-card-header>
                        <div class="headerSlider">Lele</div>
                        <div class="ion-text-left weight">
                          <div class="blue">200 Kg</div>
                        </div>
                      </ion-card-header>
                    </ion-card>
                  </h1>

                  <h1>
                    <ion-card>
                      <img
                        alt="Silhouette of mountains"
                        src="https://lh6.googleusercontent.com/proxy/XOemItRPdpqWiRnZ1dKYbPuXYFQ-PKOGLxoRd99-UdaRli1-yM6lx2qEFVL2fFAGif-u1wsdW9wW_6r-DIM_TvKYtOh9Jd3-HCcVGgtEAO2S4Hnw=w1200-h630-p-k-no-nu"
                        style="width: 150px; height: 180px"
                      />
                      <ion-card-header>
                        <div class="headerSlider">Lele</div>
                        <div class="ion-text-left weight">
                          <div class="blue">200 Kg</div>
                        </div>
                      </ion-card-header>
                    </ion-card>
                  </h1>
                </ion-row>
              </ion-slide>
              <ion-slide>
                <ion-row>
                  <h1>
                    <ion-card>
                      <img
                        alt="Silhouette of mountains"
                        src="https://lh6.googleusercontent.com/proxy/XOemItRPdpqWiRnZ1dKYbPuXYFQ-PKOGLxoRd99-UdaRli1-yM6lx2qEFVL2fFAGif-u1wsdW9wW_6r-DIM_TvKYtOh9Jd3-HCcVGgtEAO2S4Hnw=w1200-h630-p-k-no-nu"
                        style="width: 150px; height: 180px"
                      />
                      <ion-card-header>
                        <div class="headerSlider">LELE</div>
                        <div class="ion-text-left weight">
                          <div class="blue">200 Kg</div>
                        </div>
                      </ion-card-header>
                    </ion-card>
                  </h1>

                  <h1>
                    <ion-card>
                      <img
                        alt="Silhouette of mountains"
                        src="https://lh6.googleusercontent.com/proxy/XOemItRPdpqWiRnZ1dKYbPuXYFQ-PKOGLxoRd99-UdaRli1-yM6lx2qEFVL2fFAGif-u1wsdW9wW_6r-DIM_TvKYtOh9Jd3-HCcVGgtEAO2S4Hnw=w1200-h630-p-k-no-nu"
                        style="width: 150px; height: 180px"
                      />
                      <ion-card-header>
                        <div class="headerSlider">NILA MERAH</div>
                        <div class="ion-text-left weight">
                          <div class="blue">200 Kg</div>
                        </div>
                      </ion-card-header>
                    </ion-card>
                  </h1>
                </ion-row>
              </ion-slide>
            </ion-slides>
          </ion-row>
        </ion-grid>

        <ion-grid>
          <ion-row> <span class="header">Kualitas Air</span> </ion-row>
          <ion-row class="ion-justify-content-start">
           <ion-card>
              <ion-card-header class="waterCondition">
                <div class="headerWaterC">pH</div>
                <ion-row>
                  <ion-col> Normal </ion-col>
                  <ion-col class="blue"> 6 Kolam </ion-col>
                </ion-row>
                <ion-row>
                  <ion-col> Abnormal </ion-col>
                  <ion-col class="blue"> 6 Kolam </ion-col>
                </ion-row>
              </ion-card-header>
            </ion-card>
            <ion-card>
              <ion-card-header class="waterCondition">
                <div class="headerWaterC">DO</div>
                <ion-row>
                  <ion-col> Normal </ion-col>
                  <ion-col class="blue"> 6 Kolam </ion-col>
                </ion-row>
                <ion-row>
                  <ion-col> Abnormal </ion-col>
                  <ion-col class="blue"> 6 Kolam </ion-col>
                </ion-row>
              </ion-card-header>
            </ion-card>
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
  IonCardSubtitle,
  IonCardTitle,
  IonSlides,
  IonSlide,
  IonPage,
} from "@ionic/vue";

export default defineComponent({
  name: "HomePage",
  components: {
    IonApp,
    IonContent,
    IonCol,
    IonGrid,
    IonRow,
    IonCard,
    IonCardHeader,
    IonCardSubtitle,
    IonCardTitle,
    IonSlides,
    IonSlide,
    IonPage,
  },
  setup() {
    const slideOpts = {
      initialSlide: 2,
      speed: 400,
    };
    return { slideOpts };
  },
});
</script>
<style>
* {
  font-family: Poppins;
}

.cardimg {
  height: 15px;
  width: 18px;
}

.header {
  font-weight: 600;
  font-family: Poppins;
  font-size: 24px;
  line-height: 36px;
  letter-spacing: 0.01em;
  text-align: left;
  margin: 10px 10px 0 20px;
}

ion-card-header {
  padding-top: 10px;
  padding-bottom: 0px;
  text-align: left;
}

ion-card {
  margin-top: 2px;
  margin-bottom: 5px;
  border-radius: 15px;
}

ion-card-title {
  font-size: 18px;
  color: black;
  margin-bottom: 0px;
}

ion-card-subtitle {
  font-weight: 700;
  font-size: 25px;
  text-transform: capitalize;
  color: black;
}

.child-subtitle {
  font-size: 20px;
}

ion-label {
}

.blue {
  color: #2c96f1;
}

.headerSlider {
  font-weight: 600;
  font-size: 20px;
  line-height: 27px;
  left: 50px;
  top: 201px;
  color: black;
}

.headerWaterC {
  font-weight: 600;
  font-size: 30px;
  left: 50px;
  color: black;
  margin-bottom: 10px;
}

.weight {
  padding-bottom: 15px;
  margin-bottom: 8px;
  font-weight: 700;
  text-align: left;
  font-size: 17px;
}

.waterCondition {
  color: black;
  font-family: Poppins;
  padding: 5px 15px 5px 15px;
  width: 170px;
}

.textWaterC {
  margin-bottom: 10px;
}
</style>
