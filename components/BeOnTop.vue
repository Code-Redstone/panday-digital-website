<template>
<v-container>
    <v-row>
        <v-col class="Text-center"  cols="12" >
            <div class="div text-center">
              <h3 class="black--text text--secondary font-weight-light text-xl-h4 text-lg-h5 text-md-h6 text-sm-h4 ">GROW TRAFFIC & INCREASE REVENUE</h3>
              <h2  class="black--text text--secondary text-xl-h2 text-lg-h4 text-md-h5 text-sm-h3 font-weight-bold py-5"> Be On the Top & Get More Traffic to Your Website</h2>
              <p class="black--text text--secondary text-h6 font-weight-light text-xl-h4 text-lg-h5 text-md-subtitle-1 text-sm-h5">As the top digital marketing agency in the Philippines, we are honored to illuminate your ideas when it comes to steering your digital journey forward. Here are our top-rated services that attest to our legacy for you.</p>
            </div>
        </v-col>            
        <v-col class="text-center" cols="4" sm="12" md="4" lg="4" xl="4" v-for="seo in seos " :key="seo.id" >
            <v-card 
            class="pa-8 Services-hover Services-Font rounded-xl"
            outlined
            >
                <v-img
                class="ma-auto"
                max-width="200"
                max-height="200"
                :src="seo.img"
                >
                </v-img>
                <h3 class="mb-5 font-weight-bold text-center Services-Font text-xl-h4 text-lg-h5 text-md-h6 text-sm-h4">{{seo.title}}</h3>
                <p class="text-justify text-xl-h5 text-lg-h5 text-md-subtitle-1 text-sm-h5">{{seo.discription}}</p>
            </v-card>
        </v-col>
    </v-row>
</v-container>
</template>

<script>
export default {
    name:'BeOnTop',
    data() {
        return{
            seos: [
          {
            id:1,
            img:'/_nuxt/assets/resources/seoseo.png',
            title:'Search Engine Optimization',
            discription:'Establish your website at the first place for its products or services that people instantly see when they search it online. This is your gateway to secure leads as the top trusted brand in your industry.',
          },
          {
            id:2  ,
            img:'/_nuxt/assets/resources/smm.png',
            title:'Social Media Marketing',
            discription:'Capture the world with your every move through maximizing these game-changer platforms. Once you master how to engage your audience in social media, your brand is bound to be unstoppable.',
          },
          {
            id:3  ,
            img:'/_nuxt/assets/resources/lseo.png',
            title:'Local SEO',
            discription:'People prioritize brands that offer them complete convenience through proximity and accessibility. Ensure that your local consumers find you first to influence their purchasing choices effectively.',
          },
          {
            id:4  ,
            img:'/_nuxt/assets/resources/wdd.png',
            title:'Web Design & Development',
            discription:'Aesthetics and website user-friendliness surely make your online relevance. Leave them wonderstruck with how you welcome them to your brand’s working grounds.',
          },
          {
            id:5  ,
            img:'/_nuxt/assets/resources/rm.png',
            title:'Reputation Management',
            discription:'Take control of the online conversation that empowers your brand. Cultivate strategies with us to shift the odds and elevate your brand with every audience interaction.',
          },
          {
            id:6  ,
            img:'/_nuxt/assets/resources/Ads.png',
            title:'Pay Per Click Management',
            discription:'Drive consistent traffic to your website by directly channeling your resources to your target consumers. Flourish in channels where it matters.',
          },
          {
            id:7  ,
            img:'/_nuxt/assets/resources/cdg.png',
            title:'Creatives Graphic Design',
            discription:'Nothing’s more captivating than images that express your brand’s capability. Invest to impress them with your new ideas or visual artistry that stands out.',
          },
          {
            id:8  ,
            img:'/_nuxt/assets/resources/cwm.png',
            title:'Content Writing & Marketing  ',
            discription:'Craft content that converts visitors to admirers. Transform curiosity into loyalty. The key is to be seen and heard, and we’re here to find the right words for you.',
          },
          {
            id:9  ,
            img:'/_nuxt/assets/resources/em.png',
            title: 'Email Marketing',
            discription:'Create personal conversations with your consumers beyond their inbox. Build your credibility with a cost-effective outline while maintaining impressive conversions.',
          },
        ],
        }
    }
}
</script>

<style>

</style>