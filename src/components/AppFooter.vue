<script>
import InfoCompany from './InfoCompany.vue';

export default {
    name: 'AppFooter',
    components: {
        InfoCompany
    },
    data() {
        return{
            footer: [
                {
                    "title": "BOOKINGS",
                    "info": "502 New Design Str,",
                    "info2": "Melbourne, San Francisco,",
                    "info3": "CA 94110, United States Of America Australia",
                    "info4": "T: 1123-456-789",
                    "info5": "Email: demo@example.com",
                },
                {
                    "title": "INFORMATION",
                    "info": "Produce Support",
                    "info2": "Checkout",
                    "info3": "Report Abuse",
                    "info4": "Redeem Voucher",
                    "info5": "Order Status",
                },
                {
                    "title": "SUPPORT",
                    "info": "Policies & Rules",
                    "info2": "Privacy Policy",
                    "info3": "License Policy",
                    "info4": "My Account",
                    "info5": "Locality",
                },
                {
                    "title": "NEWSLETTER",
                }
            ]
        };
    }
}
</script>

<template>
    <InfoCompany v-for="singleInfo in footer" :title="singleInfo.title" :info="singleInfo.info" :info2="singleInfo.info2" :info3="singleInfo.info3" :info4="singleInfo.info4" :info5="singleInfo.info5"></InfoCompany>
    <div class="background-000">
        <div class="copyright">
            <h4><i class="fa-regular fa-copyright"></i> 2023 All Rights Reserved. Developed By TemplateMela</h4>
        </div>
    </div>
</template>

<style scoped lang="scss">
.copyright{
    width: 100%;
    text-align: center;
    padding: 30px 0;
    border-top: 1px solid rgb(118, 118, 118);
}
</style>