<template>
	        <v-container grid-list-xl  fluid style="margin-top: 50px; margin-bottom: 50px;"> 
              <v-layout  align-center>
                <v-flex xs12 sm3 class="shadow-effect">
                  <v-card class="elevation-0 transparent card" > 
                    <img src="../assets/c1.jpg" height="300px" width="200px" >
                    <v-card-title primary-title class="layout justify-center title">
                      <div class="headline text-xs-center">Tests et exercices personnalisés</div>
                    </v-card-title>
                    <v-card-text>
                      Le fruit d’un savoir-faire qui met en valeur la différence des cas et des perturbations rencontrés chez les patients. 
                    </v-card-text>  
                  </v-card>
                </v-flex>
                <v-flex xs12 sm3 class="shadow-effect">
                  <v-card class="elevation-0 transparent card">
                    <img src="../assets/c2.jpg" height="300px" width="200px" >
                    <v-card-title primary-title class="layout justify-center title">
                      <div class="headline">Une prise en charge complémentaire</div>
                    </v-card-title>
                    <v-card-text>
                      Et harmonieuse basée sur l’interaction entre orthophonistes et professionnels. <br> <br>
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 sm3 class="shadow-effect">
                  <v-card class="elevation-0 transparent card">
                    <img src="../assets/c5.jpg" height="300px" width="200px" >
                    <v-card-title primary-title class="layout justify-center title">
                      <div class="headline text-xs-center"> Un réseau important</div>
                    </v-card-title>
                    <v-card-text>
                      Un annuaire contenant une liste de coordonnées de toutes les parties actionnaires impliquées dans la prise en charge orthophonique. <br><br>
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 sm3 class="shadow-effect">
                  <v-card class="elevation-0 transparent card">
					<img src="../assets/c4.jpg" height="300px" width="200px" >
                    <v-card-title primary-title class="layout justify-center title">
                      <div class="headline text-xs-center"> Restez branché</div>
                    </v-card-title>
                    <v-card-text>
                      Une actualité enrichissante contenant des nouveautés autour de plusieurs thématiques tournant autour l’orthophonie dans tous ses aspects. <br> <br>

                    </v-card-text>
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
</template>


<style scoped>
	.shadow-effect{
		padding: 0px;
		width: 100px;
		box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
		margin-left: 5px;
		margin-right: 5px;
	}
	.card{
		padding-left: 0px;
		padding-right: 0px;
	}
	.title{
		background: -webkit-linear-gradient(0deg, #1a237e 0%, #80deea 100%); 
        -webkit-background-clip:text;
        -webkit-text-fill-color:transparent; 
	}
</style>