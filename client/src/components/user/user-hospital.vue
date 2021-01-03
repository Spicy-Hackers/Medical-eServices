<template>
    <div >
        <b-dropdown id="dropdown-1" text="Location" class="m-md-2">
            <b-dropdown-item>Tunis</b-dropdown-item>
            <b-dropdown-item>Ariana</b-dropdown-item>
            <b-dropdown-item>Ben Arous</b-dropdown-item>
            <b-dropdown-item>Manouba</b-dropdown-item>
            <b-dropdown-divider></b-dropdown-divider>
        </b-dropdown>
        <b-container class="bv-example-row">
            <b-row class="justify-content-md-center">
                <b-col cols="12" md="auto">
                    <h4>Here is the Hospital Component</h4>
                    <div class="mt-4">
                        <b-card v-bind:img-src="require('../.././assets/clinic.png')" img-alt="Card image" img-left class="mb-3">
                            <b-card-text>
                                <b>Hospital : </b>Ben Arous Hospital
                            </b-card-text>
                            <b-card-text>
                                <b>Phone Number : </b>72156708
                            </b-card-text>
                            <b-card-text>
                                <b>email : </b>benarous-hospital@gmail.com
                            </b-card-text>
                            <b-card-text>
                                <b>Adress : </b>Ben Arous
                            </b-card-text>
                            <b-card-text>
                                <b>Disponibility : </b>12h/24 from monday to saturday
                            </b-card-text>
                        </b-card>

                        <b-card v-bind:img-src="require('../.././assets/clinic.png')" img-alt="Card image" img-right>
                            <b-card-text>
                                <b>Hospital : </b>Ben Arous Hospital
                            </b-card-text>
                            <b-card-text>
                                <b>Phone Number : </b>72156708
                            </b-card-text>
                            <b-card-text>
                                <b>email : </b>benarous-hospital@gmail.com
                            </b-card-text>
                            <b-card-text>
                                <b>Adress : </b>Ben Arous
                            </b-card-text>
                            <b-card-text>
                                <b>Disponibility : </b>12h/24 from monday to saturday
                            </b-card-text>
                        </b-card>
                    </div>
                </b-col>
            </b-row>
        </b-container>
        <router-view/>
    </div>
    
</template>

<script>

export default {
    name: 'UserHospital',
    data () {
        return {
            img: 'assets/clinic.png'
        }
    },
    components: {

    }   
}
</script>

<style>

</style>