<template>
<div class="agenda">
    <b-container fluid>
        <b-row>
            <b-col md="4">
                <h1>Agenda</h1>
            </b-col>
            <b-col md="4" offset-md="4">
            </b-col>
        </b-row>
    </b-container>
    <b-container>
        <b-row>
            <b-col style="col-centered">
                <b-card class="redcard" title="Dr. Scot Morris" img-src="https://puu.sh/HRicp/54871f8581.jpg" img-alt="Image" img-top>
                    <b-card-header class="header">
                        January 11 & 12, 2018
                    </b-card-header>
                    <b-img src="https://puu.sh/HRiku/9ca46c1b1c.png" />
                    <b-img src="https://puu.sh/HRil4/345d976276.png" />
                    <b-img src="https://puu.sh/HRilu/993382fe66.png" />
                    <b-card-text>
                        Dr. Scot Morris, OD, well known speaker, author, editor and educator will take attendees through a day of learning on everything from designing your vision & business niche to patient flow, financial basics and operational efficiency.
                    </b-card-text>
                </b-card>
            </b-col>
            <b-col style="col-centered">
                <b-card class="bluecard" title="Kevin Wilhelm" img-src="https://puu.sh/HRidc/18203243fe.png" img-alt="Image" img-top>
                    <b-card-header class="header">
                        May 8 & 9, 2018
                    </b-card-header>
                    <b-img src="https://puu.sh/HRiku/9ca46c1b1c.png" />
                    <b-img src="https://puu.sh/HRil4/345d976276.png" />
                    <b-img src="https://puu.sh/HRilu/993382fe66.png" />
                    <b-card-text>
                        Meeting marketing guru, Kevin Wilhelm. Current president of Marketing4ECPs, Kevin is a serial entrepreneur, brand ambassador, educator and marketing facilitator. Attendees will learn how to dominate in a digital based world as well as learn the basics of traditional marketing, in office design, merchandising and the value of partnering with everyone from supplier partners to services.
                    </b-card-text>
                </b-card>
            </b-col>
            <b-col style="col-centered">
                <b-card class="redcard" title="Trudi Charest" img-src="https://puu.sh/HRidj/001627976e.jpg" img-alt="Image" img-top>
                    <b-card-header class="header">
                        Nov 15 & 16, 2017
                    </b-card-header>
                    <b-img src="https://puu.sh/HRiku/9ca46c1b1c.png" />
                    <b-img src="https://puu.sh/HRil4/345d976276.png" />
                    <b-img src="https://puu.sh/HRilu/993382fe66.png" />
                    <b-card-text>
                        Trudi Charest has been a leading educator and speaker in the eyecare industry for decades. She brings an extensive background of experience from retail to wholesale to clinical. She also has an HR background working as a corporate trainer/ recruiter for a large eyecare group. This day will be all about people! Content will focus on the best HR techniques for small business as far as finding good staff, training, motivating as well as understanding how performance drives revenue and growing a strong team and culture. We will also focus on networking and buying groups as well as setting prevention measures for your practice from theft, fraud and HR legalities every business owner needs to know.
                    </b-card-text>
                </b-card>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
.agenda {
    background-image: url("https://puu.sh/HQLrR/03ac6173d3.png");
    background-repeat: repeat;
}
h1 {
    padding-top: 5rem;
    text-decoration: underline;
    text-decoration-color: #ed1c24;
}

.col-centered {
    float: none;
    margin: 0 auto;
}

.redcard {
    background-color: #ed1c24;
    color: white;
}

.bluecard {
    background-color: #006ecc;
    color: white;
}

.header {
    font-size: 36px;
}
</style>
