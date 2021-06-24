<template>
<div class="reasons">
    <b-container>
        <b-row>
            <b-col md="4">
                <h1>Top <strong>5 Reasons</strong><br> You Should<br><u>Apply</u></h1>
            </b-col>
            <b-col md="4" offset-md="4">
            </b-col>
        </b-row>
        <b-row>
            <b-col sm="6">
                <b-img src="https://puu.sh/HQKcn/861dca1f11.jpg" fluid />
            </b-col>
            <b-col sm="6">
                <table>
                    <tr>
                        <td>
                            <img src="https://puu.sh/HQKtk/43ba254eee.png">
                        </td>
                        <td>
                            <ul>
                                <h3>Learning</h3>
                                <p>Learn business trends and topics from industry experts who live and breathe business</p>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <img src="https://puu.sh/HQKy3/c7320c0b91.png">
                        </td>
                        <td>
                            <ul>
                                <h3>Resources</h3>
                                <p>Walk away with tools and resources to implement immediately in your practice</p>

                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <img src="https://puu.sh/HQKzV/d5bc7bf752.png">
                        </td>
                        <td>
                            <ul>
                                <h3>Networking</h3>
                                <p>Network with OD’s just like you in similar practice lifecycles and growth opportunities</p>

                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <img src="https://puu.sh/HQKA9/54a29873fe.png">
                        </td>
                        <td>
                            <ul>
                                <h3>Experience</h3>
                                <p>Experience being a part of a special elite group who are progressive and innovative</p>

                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <img src="https://puu.sh/HQKAn/3c35a2a708.png">
                        </td>
                        <td>
                            <ul>
                                <h3>Influence</h3>
                                <p>Directly influence the direction of Johnson & Johnson Vision Care research by being a part of a dedicated focus group</p>

                            </ul>
                        </td>
                    </tr>
                </table>
            </b-col>
        </b-row>
    </b-container>
    <scroll-link href="#regform" />

</div>
</template>

<script>
import ScrollLink from './ScrollLink.vue'
export default {
    components: {
        ScrollLink
    },

}
</script>

<style scoped>
strong {
    color: #006ecc;
}

h1 {
    text-align: left;
}

u {
    text-decoration-color: #ed1c24;
}

p {
    padding-top: 2rem;
}

.reasons {
    background-color: rgb(245, 245, 245);
    background-image: url("https://puu.sh/HQLrR/03ac6173d3.png");
    background-repeat: repeat;

}

table,
ul,
td {
    background-color: #ed1c24;
    color: white;
    text-align: left;
    font-size: 21px;
    padding-left: 2rem;
    padding-top: 0rem;
}

ul {
    padding-top: 1rem;
    padding-bottom: 1rem;
}

.b-btn-apply {
    padding: 1rem 5rem 1rem 5rem;
    margin: 3rem;
    font-size: 24px;
    letter-spacing: 0.5rem;
}
</style>
