<template>
  <v-container id="aboutContainer" fluid>
    <div id="aboutSession">
      <div>
        <h2 id="aboutTitle">
          About Us
        </h2>
      </div>
    </div>
    <v-layout row>
      <v-flex md2 />
      <v-flex md4>
        <h1 id="aboutCardTitle">
          Voluptatem dignissimos provident quasi corporis voluptates sit assumenda.
        </h1>
        <p id="aboutCardSubtitle">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </p>
        <div id="aboutCardText">
          <p>
            <v-icon color="green">
              mdi-checkbox-marked-circle-outline
            </v-icon>
            Uilamco laboris nisi ut aliquip ex ea commodo consequat.
          </p>
          <p>
            <v-icon color="green">
              mdi-checkbox-marked-circle-outline
            </v-icon>
            Duis aute irure dolor in reprehenderit in voluptate velit.
          </p>
          <p>
            <v-icon color="green">
              mdi-checkbox-marked-circle-outline
            </v-icon>
            Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate trideta storacalaperda mastiro dolore eu fugiat nulla pariatur.
          </p>
          <p>
            Ullamco laboris nisi ut aliquip ex ea commodo consequat.
            Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
            Excepeteur sint occaecat cupidatat  non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
          </p>
        </div>
      </v-flex>
      <v-flex md4>
        <v-img id="aboutImage" src="../../../imagens/about-img.jpg" />
      </v-flex>
      <v-flex md2 />
    </v-layout>
  </v-container>
</template>

<style>

#aboutContainer {
    margin-bottom: 0px;
    background-color: white;
}
#aboutImage {
    margin-top: 15px;
    margin-left: 50px;
    height: 500px;
    width: 1050px;
}
#aboutCardText{
   font-size: 18px;
   color: #787474;
   font-family: "sans-serif";
}
#aboutCardSubtitle{
   font-size: 18px;
   color: #787474;
   font-style: italic;
   font-family: "sans-serif";
}
#aboutCardTitle {
    padding-bottom: 10px;
    font-weight: normal;
    font-size: 30px;
    color:  #787474;
    font-family: "sans-serif";
}
#aboutTitle {
    font-weight: normal;
    color:  #787474;
    padding-bottom: 50px;
    font-size: 2.5rem;
    font-family: "Lato";
}
#aboutSession {
    padding-top: 50px;
    padding-bottom: 0px;
    justify-content: center;
    align-items: center;
    display: flex;
}
@media only screen and (max-width: 1851px) {
    #aboutImage {
        margin-top: 15px;
        margin-left: 50px;
        height: 100%;
        width: 100%;
    }
    #aboutCardTitle {
        padding-bottom: 10px;
        font-weight: normal;
        font-size: 30px;
        color:  #787474;
    }
    #aboutCardSubtitle{
        font-size: 18px;
        color: #787474;
        font-style: italic;
    }
    #aboutCardText{
        font-size: 17px;
        color: #787474;
    }
}
@media only screen and (max-width: 1475px) {
    #aboutImage {
        margin-top: 15px;
        margin-left: 50px;
        height: 100%;
        width: 100%;
    }
    #aboutCardTitle {
        padding-bottom: 10px;
        font-weight: normal;
        font-size: 25px;
        color:  #787474;
    }
    #aboutCardSubtitle{
        font-size: 17px;
        color: #787474;
        font-style: italic;
    }
    #aboutCardText{
        font-size: 16px;
        color: #787474;
    }
}
@media only screen and (max-width: 1280px) {
    #aboutImage {
        margin-top: 15px;
        margin-left: 50px;
        height: 95%;
        width: 100%;
    }
    #aboutCardTitle {
        padding-bottom: 10px;
        font-weight: normal;
        font-size: 20px;
        color:  #787474;
    }
    #aboutCardSubtitle{
        font-size: 13px;
        color: #787474;
        font-style: italic;
    }
    #aboutCardText{
        font-size: 13px;
        color: #787474;
    }
}
@media only screen and (max-width: 1024px) {
    #aboutImage {
        margin-top: 15px;
        margin-left: 25px;
        height: 90%;
        width: 100%;
    }
    #aboutCardTitle {
        padding-bottom: 10px;
        font-weight: normal;
        font-size: 15px;
        color:  #787474;
    }
    #aboutCardSubtitle{
        font-size: 10px;
        color: #787474;
        font-style: italic;
    }
    #aboutCardText{
        font-size: 10px;
        color: #787474;
    }
}
@media only screen and (max-width: 960px) {
    #aboutImage {
        margin-top: 15px;
        margin-left: 10%;
        margin-right: 10%;
        height: 80%;
        width: 80%;
    }
    #aboutCardTitle {
        padding-bottom: 0px;
        font-weight: normal;
        font-size: 20px;
        color:  #787474;
        margin-left: 10%;
        margin-right: 10%;
    }
    #aboutCardSubtitle{
        font-size: 15px;
        color: #787474;
        font-style: italic;
        margin-left: 10%;
        margin-right: 10%;
    }
    #aboutCardText{
        font-size: 15px;
        color: #787474;
        margin-left: 10%;
        margin-right: 10%;
    }
}
</style>

<script>
export default {
  name: 'HomeAboutUs'
}
</script>
