<template>
<v-container>
    <v-row>
        <v-col cols="12" class="custom-height">
            <h3 class="font-weight-bold text-xl-h4 text-lg-h5 text-md-h6 text-sm-h4 pt-5">Digital Marketing Proposal</h3>
        </v-col>
        <v-col cols="12 " class="py-0">
            <p class="ma-0 font-weight-light text-xl-h4 text-lg-h5 text-md-subtitle-1 text-sm-h5">Fields marked with an * are required </p>
        </v-col>              
        <v-col cols="6" class="custom-width">
            <v-text-field label="Full Name" auto-grow outlined rows="2" row-height="15">
            </v-text-field>
        </v-col>
        <v-col cols="6" class="custom-width">
            <v-text-field label="Business Name" auto-grow outlined rows="2" row-height="15">
            </v-text-field>
        </v-col>
        <v-col cols="6" class="custom-width">
            <v-text-field label="Email" auto-grow outlined rows="2" row-height="15">
            </v-text-field>
        </v-col>
        <v-col cols="6" class="custom-width">
            <v-text-field
            label="Phone" 
            auto-grow outlined 
            rows="2" 
            row-height="15">
            </v-text-field>
        </v-col>
        <v-col cols="12 " class="pb-0">
            <p class="font-weight-medium mb-0 mt-5 text-xl-h4 text-lg-h5 text-md-subtitle-1 text-sm-h5">What services can we provide you?</p>
        </v-col>
        <v-col cols="12 " class="">
            <v-container>
                <v-row>
                    <v-col cols="6" class="py-0">
                        <v-checkbox
                        label="Search Engine Optimization"
                        color="blue "
                        value="optimization"
                        hide-details
                        ></v-checkbox>
                    </v-col>
                    <v-col cols="6" class="py-0">
                        <v-checkbox
                        label="Online Reputation Management"
                        color="blue "
                        value="reputation_management"
                        hide-details
                        ></v-checkbox>
                    </v-col>
                    <v-col cols="6" class="py-0">
                        <v-checkbox
                        label="Web Design & Development"
                        color="blue "
                        value="web_development"
                        hide-details
                        ></v-checkbox>
                    </v-col>
                    <v-col cols="6" class="py-0">
                        <v-checkbox
                        label="Social Media Management"
                        color="blue "
                        value="media_management"
                        hide-details
                        ></v-checkbox>
                    </v-col>
                    <v-col cols="6" class="py-0">
                        <v-checkbox 
                        label="Search Engine Marketing"
                        color="blue "
                        value="marketing"
                        hide-details
                        ></v-checkbox>
                    </v-col>
                    <v-col cols="6" class="py-0">
                        <v-checkbox
                        label="Content Writing Management"
                        color="blue "
                        value="content_writing"
                        hide-details
                        ></v-checkbox>
                    </v-col>
                    <v-col cols="12" class="custom-width">
                        <v-text-field
                        label="E-mail"
                        auto-grow 
                        outlined 
                        rows="2" 
                        row-height="15">
                        </v-text-field>
                    </v-col>                         
                </v-row>
            </v-container>
        </v-col>
        <v-col cols="12">
            <v-btn  color="blue "
            class="px-15 py-10"
            elevation="1"
            > <span class=" white--text font-weight-light text-justify text-xl-h6 text-lg-h6 text-md-subtitle-2 text-sm-h5">Here from an expert</span>
            </v-btn>             
        </v-col>
    </v-row>
</v-container>
</template>

<script>
export default {
     name:'RegestrationForm',
}
</script>

<style>

</style>