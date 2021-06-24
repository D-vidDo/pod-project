<template>
<div class="registration" id="regform">
    <b-jumbotron>
        <b-container fluid>
            <b-row>
                <b-col md="4">
                    <h1>Registration</h1>
                </b-col>
                <b-col md="4" offset-md="4">
                </b-col>
            </b-row>
        </b-container>
        <!-- </b-jumbotron> -->
        <b-container>
            <form>
                <div class="row">
                    <div class="col">
                        <input type="text" class="form-control" placeholder="First name">
                    </div>
                    <div class="col">
                        <input type="text" class="form-control" placeholder="Last name">
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        <input type="text" class="form-control" placeholder="E-Mail">
                    </div>
                    <div class="col">
                        <input type="text" class="form-control" placeholder="Practice Name">
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        <input type="text" class="form-control" placeholder="Address">
                    </div>
                    <div class="col">
                        <input type="text" class="form-control" placeholder="City">
                    </div>
                    <div class="col">
                        <input type="text" class="form-control" placeholder="Zip Code">
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        <input type="text" class="form-control" placeholder="Province">
                    </div>
                    <div class="col">
                        <input type="text" class="form-control" placeholder="Country">
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        Please Choose One:
                        <div>
                            <input class="form-check-input" type="radio" name="exampleRadios" id="IPO" value="option1" checked>
                            <label class="form-check-label" for="IPO">
                                Independent Practice Owner - OD
                            </label>
                        </div>
                        <div>
                            <input class="form-check-input" type="radio" name="exampleRadios" id="CPO" value="option2">
                            <label class="form-check-label" for="CPO">
                                Corporate Practice Owner - OD
                            </label>
                        </div>
                        <div>
                            <input class="form-check-input" type="radio" name="exampleRadios" id="NG" value="option3">
                            <label class="form-check-label" for="NG">
                                New Grad - OD
                            </label>
                        </div>
                        <div>
                            <input class="form-check-input" type="radio" name="exampleRadios" id="AO" value="option4">
                            <label class="form-check-label" for="AO">
                                Associate Optometrist - OD
                            </label>
                        </div>
                    </div>
                    <div class="col">
                        Please list three opportunities you see for the future of Optometry:
                        <input type="text" class="form-control" placeholder="Comment">
                    </div>
                </div>
                <b-button class="b-btn-apply" squared variant="primary"> <b>SUBMIT</b> </b-button>
            </form>
            <h3>Thank you for applying for OD 40/40.</h3>
            <h4>You will be contacted by Johnson & Johnson Vision Care marketing department regarding the application process and final 40 chosen attendees.</h4>

        </b-container>
    </b-jumbotron>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.registration {
    background-image: url("https://puu.sh/HRixq/25ab1954e4.jpg");
    background-size: cover;
    height: 120vh;
}

.form-control {
    padding: 2rem;
    margin: 1rem;
}

.form-check-label {
    color: white;
}

.b-btn-apply {
    padding: 1rem 5rem 1rem 5rem;
    margin: 3rem;
    font-size: 24px;
    letter-spacing: 0.5rem;
}

.row,
.col {
    color: white;
    text-align: left;
}

h1 {
    color: white;
    text-align: center;
    padding-top: 5rem;
    text-decoration: underline;
}

h3 {
    color: white;
}

h4 {
    color: white;
    font-size: 18px;
}
</style>
