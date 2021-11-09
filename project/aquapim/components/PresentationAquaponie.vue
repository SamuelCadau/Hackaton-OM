<template>
    <b-container>
        <b-row class="mt-3"> 
            <h1 class="mx-auto">L'AQUAPONIE</h1>
        </b-row>

        <b-row class="mx-auto schema mt-3">


            <b-col class="mt-5 col1">
                <p>0 changement d'eau <br/>
                    0 intrant chimique <br/>
                    Autonomie = Peu d'entretien
                </p>
            </b-col>

            <b-col >
                <b-img id="schema-gif" class="mx-auto" src="../static/schema.gif"  fluid-grow />
            </b-col>

            <b-col class="mt-5 col2">
                <p>
                    Parlement Européen: <br/>
                    "Une des 10 technologies qui pourraient changer nos vies"
                </p>
            </b-col>

            
        </b-row>
        
    </b-container>
</template>

<style>

h1{
    font-family: "Poppins-Bold";
    color:#3e602f;
}

.col1{
    border-top-style: groove;
    border-left-style: groove;
}

.col2{
    border-bottom: groove;
    border-right: groove;
}

.schema {
    
    font-family: "Poppins-Medium";
    font-size: 20px;
}

#schema-gif {
    width: 500%;
}

</style>