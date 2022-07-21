<template>
<v-app id="home" :style="{background: $vuetify.theme.themes.dark.background}">
<Navbar/>
<v-container fluid>
  <v-row>
    <v-col cols="6">
      <v-img src="1.png" contain max-height="500"></v-img>
    </v-col>
    <v-col cols="6">
      <h5 class="red--text text-darken-4 top">Merhaba ben Bilge siteme hoşgeldin</h5>
      <h1 class="white--text">Mekatronik Mühendisi</h1>
      <p class="grey--text">Mekatronik mühendisi, üretim sürecindeki 
        değişiklikleri uygulamaya koymadan önce, montaj hattı verimliliği <br/>
         ve maliyet gibi faktörleri göz önünde bulundurarak, iyileştirmeler yapmak <br />
          için çeşitli yöntemlerle testler yapar. Potansiyel çözümleri geliştirmek
           için bilgisayar destekli tasarım yazılımı kullanır.

      </p>
      <v-btn tile color="#370617öö" dark>benim hakkımda</v-btn>

    </v-col>
  <v-col cols="12" class="padd">
    <div class="first" id="project">
      <v-row>
        <v-col cols="12">
          <div class="child bgColor1">
            <v-icon color="#780116" x-large class="ml-3">
              mdi-palette-swatch
            </v-icon>
            <h3 class="white--text ml-3 mt-4">Mekatronikte Yazılım</h3>
            <p class="grey--text ml-3 mt-6">
              Mekatronik, yazılımı makina ile birleştirme işlemi yapar.<br /> 
              Robotik sistemler
              buna en büyük öreklerdendir.
            </p>
            <v-btn color="#A7121D" dark text>
                    daha fazla
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
          </div>
          <div class="child bgColor2" >
            <v-icon color="#370617" x-large class="ml-3" dark>mdi-thumb-up</v-icon>
            <h3 class="white--text ml-3 mt-4">Yaptığım Bazı Yazılımlar</h3>
            <p class="grey--text ml-3 mt-6">
               Yaptığım bazı yazılımlara buradan ulaşabilirsiniz. <br /> 
               Lütfen sorularınız varsa iletişim kısmından bana ulaşın.
               
            </p>
            <v-btn class="a" color="#A7121D" dark text @click="a">
            <a href="https://github.com/bilgekosee">github hesabıma ulaşmak için tıkla</a>
              
              <v-icon right>mdi-arrow-right</v-icon>
            </v-btn>
          </div>
            <div class="child bgColor1">
              <v-icon color="#9d0208" x-large class="ml-3">mdi-book-open-page-variant</v-icon>
              <h3 class="white--text ml-3 mt-4">Kodlar Hakkında</h3>
              <p class="grey--text ml-3 mt-6">
                C, C++, C#, HTML, CSS, JavaScript, Vue.js <br/>
              </p>
              <v-btn color="#A7121D" dark text>
              daha fazla
              <v-icon right>mdi-arrow-right</v-icon>
            </v-btn>
            
          </div>
        </v-col>
        <v-col cols="12" class="mt-10">
          <div class="child1">
            <h2 class="darkred--text text-darken-4 mt-4 number">Necmettin Erbakan Üniversitesi</h2>
            <h3 class="darkred--text mt-4">Mekatronik Mühendisliği</h3>

          </div>
          <div class="child2 mRight">
            <v-row>
              <v-col cols="12" class="childcol">
                <div class="child2 mBuutton padding bgColor1">
                  <h1 class="red--text text--darken-4">Yabancı Dil</h1>
                  <p class="grey--text">B2 seviyesinde ingilizce</p>
                </div>
              </v-col>
              <v-col cols="12" class="childcol">
                <div class="child2  padding bgColor1">
                  <h1 class="red--text text--darken-4">Staj</h1>
                  <p class="grey--text">Toyota</p>
                </div>
              </v-col>
              
            </v-row>
          </div>
         <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="red--text text--darken-4">Bitirme Projesi</h1>
                        <p class="grey--text">Denge Robotu</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="red--text text--darken-4">2 ay</h1>
                        <p class="grey--text">ARGE deneyimi</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
        </v-col>
      </v-row>

    </div>
  </v-col>
  <v-col md="3" offset-md="3" id="about">
    <h4 class="white--text">KİMİM BEN?</h4>
    <p class="grey--text">Yeni mezun bir mekatronik mühendisiyim. Alanım gereği birden fazla dal 
      ile ilgili bilgim olmasına rağmen yazılım alanında yoğunlaşmayı tercih ettim.
    </p>
  </v-col>
  <v-col md="3" class="text-end">
    <v-btn tile color="#780116" dark>Tümünü Görüntüle</v-btn>
  </v-col>
  <v-col md="3" offset-md="3">
  <v-card class="pa-2 py-12" outlined tile height="450px" color="#370617">
    <v-img src="3.png" contain max-height=""></v-img>
  </v-card>
  </v-col>
  <v-col md="3">
    <v-card class="pa-2 py-12" outlined tile height="450px" color="#370617">
    <v-img src="4.png" contain max-height=""></v-img>
  </v-card>

  </v-col>
  <v-col md="3" offset-md="3">
    <v-btn color="white" dark text class="ml-n4">
      Nelerden hoşlanırım
    </v-btn><br/>
    <v-btn color="#6a040f" dark text class="ml-n4">
      Daha Fazla
      <v-icon right>mdi-arrow-right</v-icon>
    </v-btn>
  </v-col>
  <v-col md="3">
    <v-btn color="white" dark text class="ml-n4">
      denge robotu nedir?
    </v-btn><br/>
    <v-btn color="#6a040f" dark text class="ml-n4">
      Daha Fazla
      <v-icon right>mdi-arrow-right</v-icon>
    </v-btn>
  </v-col>
  <v-col cols="12" class="padd topInverse">
    <div class="second">
<div class="secondchild1" id="contact">
      <v-row>
        <v-col cols="7">
          <h1 class="white--text">
            Birlikte çalışmak istersen <br/> hadi hemen bana ulaş
          </h1>
          <p class="grey--text">
            iletişime tıklayarak bana ulaşabilirsin <br/>
          </p>
        </v-col>
        <v-col cols="5">
          <v-btn tile color="#03071e" dark class="mt-16">İletişim</v-btn>
        </v-col>
      </v-row>
    </div>
    </div>
    <v-toolbar class="topTolbar" color="#220901" dark flat>
      <div style="position: absolute; margin-left:auto; margin-right:auto; left:0; right:0; text-align:center">
      <v-btn text>ANASAYFA</v-btn>
      <v-btn text>PROJE</v-btn>
      <v-btn text>HAKKIMDA</v-btn>
      <v-btn text>İLETİŞİM</v-btn>
      </div>
    </v-toolbar>
    
  </v-col>
  </v-row>

</v-container>
<Footer />
</v-app>
</template>

<script>
  import Navbar from '../components/Navbar' 
  import Footer from '../components/Footer'
    export default{
        // eslint-disable-next-line vue/multi-word-component-names
        name: 'Home',

        components: {
            Navbar,
            Footer
        },
    }
</script>
<style scoped>
.top {
  margin-top: 180px;
}
.topInverse{
  margin-top: -250px;
}
.topTolbar {
  margin-top: 100px;
  text-align: center;
}
.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(
    to right, 
    #370617,
    #6a040f 50%,
    #9d0208 50%,
    #9d0208 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  background: #03071e;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
  display: inline-block;
  background-color: #220901;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color:#370617 ;
}
.bgColor2 {
  background-color:#6a040f ;
}
.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}

.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton{
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0px;
}
.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>