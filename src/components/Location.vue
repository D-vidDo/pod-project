<template>
<div class="location">
    <b-container fluid>
        <b-row>
            <b-col md="4">
                <h1>Location</h1>
            </b-col>
            <b-col md="4" offset-md="4">
            </b-col>
        </b-row>
    </b-container>
    <div>
    <b-img fluid src="https://puu.sh/HRiqt/d7afc26312.jpg" />
    </div>
    <b-container class="info">
        <h2>Ivey Business School</h2>
        <h3>1255 Western Road, Londonm Ontario, Canada N6G 0N1</h3>
        <h2><strong>ivey.uwo.ca</strong></h2>
    </b-container>
    <b-container class="info">
        <h2>Have questions?</h2>
        <h3>Contact: <strong>Reya Singh - dsingh28@ITS.JNJ.com</strong></h3>
        
    </b-container>
    
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
h1 {
    padding-top: 5rem;
    text-decoration: underline;
    text-decoration-color: #ed1c24;
}

img {
    margin-right: 10rem;
}

.info {
    text-align: left;
    padding-top: 2rem;
}

h2 {
    font-size: 24px;
    color: #ed1c24;
}

h3 {
    font-size: 16px;
}

strong {
    color: #006ecc;
    font-size: 24px;
}

</style>
