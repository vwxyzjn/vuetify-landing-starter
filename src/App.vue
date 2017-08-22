<template>
  <v-app light>
    <v-toolbar class="blue">
      <v-toolbar-title v-text="title" class="white--text"></v-toolbar-title>
      <v-spacer></v-spacer>
    </v-toolbar>
    <main>
      <section id="content">
        <v-layout column align-center>
          <v-flex xs12 class="mt-5">
            <div id="title" class="display-3 orange--text text-xs-center"> Starter Template</div>
          </v-flex>
          <v-flex xs12 class="mt-3">
            <div id="subtitle" class="headline text-xs-center">A modern responsive front-end framework based on Material Design</div>
          </v-flex>
          <v-flex xs12 class="mt-3">
            <v-btn light large class="orange white--text" href="https://github.com/vwxyzjn/vuetify-landing-starter">Source Code</v-btn>
          </v-flex>
        </v-layout>
        
        <v-layout row wrap class="mt-5" >
          <v-flex xs12 sm4>
            <v-card class="elevation-0">
              <v-card-media height="45px" class="text-xs-center">
                <v-icon x-large class="blue--text">flash_on</v-icon>
              </v-card-media>
              <v-card-title primary-title>
                <div class="headline text-xs-center" style="width:100%">Speeds up development</div>
              </v-card-title>
              <v-card-text>
                We did most of the heavy lifting for you to provide
                a default stylings that incorporate our custom components.
                Additionally, we refined animations and transitions to 
                provide a smoother experience for developers.
              </v-card-text>
            </v-card>
          </v-flex>

          <v-flex xs12 sm4>
            <v-card class="elevation-0">
              <v-card-media height="45px" class="text-xs-center">
                <v-icon x-large class="blue--text">group</v-icon>
              </v-card-media>
              <v-card-title primary-title>
                <div class="headline text-xs-center" style="width:100%">User Experience Focused</div>
              </v-card-title>
              <v-card-text>
                By utilizing elements and principles of Material Design, 
                we were able to create a framework that incorporates components
                and animations that provide more feedback to users. Additionally,
                a single underlying responsive system across all platforms allow
                for a more unified user experience.
              </v-card-text>
            </v-card>
          </v-flex>

          <v-flex xs12 sm4>
            <v-card class="elevation-0">
              <v-card-media height="45px" class="text-xs-center">
                <v-icon x-large class="blue--text">settings</v-icon>
              </v-card-media>
              <v-card-title primary-title>
                <div class="headline text-xs-center" style="width:100%">Easy to work with</div>
              </v-card-title>
              <v-card-text>
                We have provided detailed documentation as well as specific code
                examples to help new users get started. We are also always open 
                to feedback and can answer any questions a user may have about 
                Materialize.
              </v-card-text>
            </v-card>
          </v-flex>
        </v-layout>
      </section>
      <div id="footer" class="orange darken-1 mt-5">
        <v-layout row wrap id="footer-layout" class="my-3">
          <v-flex xs12 sm6>
            <div class="headline white--text ml-3">Company Bio</div>
            <div class="white--text my-3 ml-3">
              We are a team of college students working on this project like 
              it's our full time job. Any amount would help support and continue 
              development on this project and is greatly appreciated.
            </div>
          </v-flex>
          <v-flex xs12 sm3>
            <div class="headline white--text ml-3">Settings</div>
            <div class="white--text my-3 ml-3">
              <a>Link1</a> <br>
              <a>Link2</a> <br>
              <a>Link3</a> <br>
              <a>Link4</a> <br>
            </div>
          </v-flex>
          <v-flex xs12 sm3>
            <div class="headline white--text ml-3">Connect</div>
            <div class="white--text my-3 ml-3">
              <a>Link1</a> <br>
              <a>Link2</a> <br>
              <a>Link3</a> <br>
              <a>Link4</a> <br>
            </div>
          </v-flex>
        </v-layout>
      </div>
      <footer class="orange darken-2">
        <v-layout row wrap id="footer-layout" class="my-2">
          <v-flex xs12>
            <div class="white--text ml-3">
              Made by Costa Huang
            </div>
          </v-flex>
        </v-layout>
      </footer>
    </main>
  </v-app>
</template>

<script>
  export default {
    data () {
      return {
        title: 'Your Logo'
      }
    }
  }
</script>

<style lang="stylus">
  @import './stylus/main'
</style>

<style>

@media (min-width: 800px) {
  .toolbar__title {
    margin-left: 15%;
  }
  #content {
    width: 70%;
    margin: auto;
  }
  #footer-layout {
    width:70%!important;
    margin:auto;
  }
}

#footer-layout {
  width: 100%;
}

#subtitle {
  font-weight: 200!important;
}


#footer {
  overflow: auto;
}
.card {
  background-color: #fafafa!important;
}
footer {
  overflow: auto;
}
a {
  color: #fff;
}
</style>

