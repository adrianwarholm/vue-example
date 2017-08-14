<template>
  <div class="home">
       <section class="hero">
            <div class="hero-body">
                 <div class="container">
                    <h1 class="title">{{ heading }}</h1>
                    <div class="is-two-thirds column is-paddingless">
                         <h2 class="subtitle is-4">{{ subheading }}</h2>
                    </div>
                    <a class="button is-large is-primary" id="learn">Learn More</a>
                 </div>
            </div>
       </section>
       <section class="section">
            <div class="container">
               <div class="columns pd is-desktop">
                    <div class="column is-1 has-text-centered">
                         <i class="fa fa-cog is-primary"></i>
                    </div>
                    <div class="column is-one-third-desktop">
                         <p class="title"><strong>We provide the best logistics, opportunities, and data for our clients so they can succeed!</strong></p>
                    </div>
                    <div class="column">
                         <p>Sign in with LinkedIn, Google, or Twitter to start using our services, APIs, and to join our network!</p>
                    </div>
               </div>
            </div>
            <div class="columns cd">
                 <div class="column">
                      <div class="card">
                           <div class="card-content">
                              <p class="title">"I think this is the best site ever created by a student for students. Absolutely stellar!"</p>
                              <p class="subtitle">– Christina Lewis Halpern</p>
                           </div>
                      </div>
                 </div>
                 <div class="column">
                      <div class="card">
                           <div class="card-content">
                              <p class="title">"I think this is the best site ever created by a student for students. Absolutely stellar!"</p>
                              <p class="subtitle">– Christina Lewis Halpern</p>
                           </div>
                      </div>
                 </div>
                 <div class=" column">
                      <div class="card">
                           <div class="card-content">
                              <p class="title">"I think this is the best site ever created by a student for students. Absolutely stellar!"</p>
                              <p class="subtitle">– Christina Lewis Halpern</p>
                           </div>
                      </div>
                 </div>
            </div>
       </section>
  </div>
</template>

<script>
export default {
  name: 'home',
  data(){
       return {
            heading: "Soaring to new heights",
            subheading: "Teens4Hire is the number one site in the world to hire talented minorities with high interests in the tech industry."
       }
 }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>
@import '../mq'

.section .container
     margin-bottom: 1.75em

.card-content
     padding: 1rem 3rem
     .title
          font-weight: 200

.hero
     background: url('../assets/bg.jpg')
     background-size: cover
     background-position: right bottom

.hero-body h1, .hero-body h2
     color: #fff !important

.hero .title
     margin-bottom: 0
     +mobile
          font-weight: bold
     +tablet
          font-size: 2.5rem
     +desktop
          font-size: 4rem
          margin-top: 2rem

.subtitle
     margin-bottom: 1.5rem
h2
     margin: 1.5rem 0 2rem 0 !important

.fa-cog
     font-size: 40px

#learn
     +desktop
          margin-bottom: 3rem

pd
     +tablet
          padding: 2em 0
</style>
