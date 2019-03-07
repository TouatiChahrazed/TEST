<template>
            <v-container grid-list-xl  fluid style="margin-top: 50px; margin-bottom: 50px;"> 
              <v-layout  align-center class="justify-center"> 
                <div class="w3-container w3-lobster justify-center">
                <p class="w3-xxxlarge titl"> Pourquoi OrthoSuivi? </p>
                <p class="w3-xxlarge titl"> La solution la plus innovante!</p>
                </div>
              </v-layout>
              <v-layout  align-center>
                <v-flex xs12 class="shadow-effect">
                  <v-card class="elevation-0 transparent card" > 
                    <v-card-text>
                      <blockquote>
                        <p class="quotation"> 
                          OrthoSuivi et l'outil le plus convenable pour suivre vos patients en dehors des séances de prise en charge permettant ainsi aux patients d'exercer les activités que vous prescrivez une fois chez eux.
                          vous aurez aussi accès  aux informations nécessaires de vos patients et à l'intégralité  des résultats des tests et des activités de ces derniers. De plus, vous trouverez dans OrthoSuivi des exercices et des outils innovants et personnalisables selon chaque patient et bien sûr les actualités et les nouveautés du domaine. 
                        </p>
                      </blockquote> 
                    </v-card-text>  
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
</template>


<style >

  .titl{
    background: -webkit-linear-gradient(0deg, #1a237e 0%, #80deea 100%); 
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent; 
  }

  blockquote{
  font-size: 30px;
  border-left: 10px solid #ccc;
  margin: .5em 10px;
  padding: 0 10px;
  quotes: "\201C""\201D""\2018""\2019";
  padding: 10px 20px;
  line-height: 1.4;
}

blockquote:before {
  content: open-quote;
  display: inline;
  height: 0;
  line-height: 0;
  left: -10px;
  position: relative;
  top: 30px;
  background: -webkit-linear-gradient(0deg, #1a237e 0%, #80deea 100%); 
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent; 
  font-size: 3em;
}
</style>