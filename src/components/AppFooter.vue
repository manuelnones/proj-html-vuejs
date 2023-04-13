<script>
export default {
    name: `AppFooter`,
    data() {
        return {
            addressLinks: [
                `382 NE 191st St # 87394 Miami, FL 33179-3899`,
                `+1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)`,
                `support@maxcoach.com`,
            ],

            exploreLinks: [
                `Start here`,
                `Blog`,
                `About us`,
                `Success story`,
                `Courses`,
                `Contact us`,
            ],

            informationLinks: [
                `Memebership`,
                `Purchase guide`,
                `Privacy policy`,
                `Terms of services`,
            ]
        }
    }
}
</script>

<template>
    <footer>

        <div id="footer-container">
            <div id="footer-left">

            </div>

            <div id="footer-right">

            </div>
        </div>

    </footer>
</template>

<style lang="scss" scoped>
footer {
    background-color: #F8F8F8;

    #footer-container {
        height: 400px;
        background-color: red;
        // /prova 
        display: flex;
        justify-content: space-between;
        width: 60%;
        margin: auto;
        padding-top: 60px;

        #footer-left {
            width: 250px;
            height: 300px;
            background-color: blue;
        }

        #footer-right {
            width: 400px;
            height: 300px;
            background-color: orange;
        }
    }
}
</style>