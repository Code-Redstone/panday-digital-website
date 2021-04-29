<template>
    <v-container class="pb-10">
        <v-row>
            <v-col cols="12">
                <div class=" text-center Services-Font">
                <h1 class="white--text font-weight-bold text-xl-h1 text-lg-h2 text-md-h3 text-sm-h2 py-8">Full Service Digital Marketing Agency</h1>
                </div>
            </v-col>
            <v-col cols="4" sm="12" md="4" lg="4" xl="4" v-for="service in services" :key="service.id" >
                <v-card
                class="pa-10 Services-hover Services-Font"
                outlined
                shaped
                >
                    <h3 class="mb-5 blue--text text-center Services-Font font-weight-bold text-xl-h3 text-lg-h5 text-md-h6 text-sm-h4 pt-5">{{service.title}}</h3>
                    <p class="text-justify text-justify text-xl-h5 text-lg-h5 text-md-subtitle-1 text-sm-h5">{{service.discription}}</p>
                </v-card>
            </v-col>
        </v-row>
    </v-container>
</template>
<script>
export default {
    name:'FullService',
    data() {
        return{
            services: [
                
                {
                    id: 1,
                    title: 'Embody A "No Filter" Identity',
                    discription:' "Merlina and her Digital Marketing Manila team is very professional. She tells what needs to be done and manages the clients expectations. She delivers on timeand is ready to answer queries and explains her work. I am happy to have found the right team to work with on a long-term basis."'
                },
                {
                    id: 2,
                    title: 'Liberate The Widest Audience Reach',
                    discription:'We are centered on executing well-planned campaigns based on our globally-proven strategies. Even the most innovative product will fail without maximizing a hyper-targeted market. Rely on our calibre to assess patterns and to attain powerful audience links for your brand’s.'
                },
                {
                    id: 3,
                    title: 'Revolutionize With Successes',
                    discription:'Skip the trial and error. Let’s focus on materializing your efforts not just with intuitive guesses, but hard facts and data. Analytics is the key to win over mediocre practices. Learn about your market, anticipate your competitors’ moves, and calculate your next power moves with us.'
                },
            ],
        }
    },
}
</script>
<style>
</style>