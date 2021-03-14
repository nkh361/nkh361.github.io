<template>
    <div id="homebody">
        <h3>
            {{ msg }}
        </h3>
       <br>
       <h4>
            Stanford Treehacks (hackathon)
        </h4>
        <p>
            During the Treehacks hackathon, I learned and experimented with multiple machine learning principles. The project my group
            worked on was a study on the COVID-19 cases in New York City. With the data in hand, we studied and used statistical analyses to find correlation in 
            COVID-19 cases and public transportation throughout the five boroughs. 
        </p>

        <a href="https://devpost.com/software/covid-19-travel-app" target="_blank" rel="noopener"> Devpost Posting </a>
        <h4>
          Chicago crime data app
        </h4>
        <p>
          The purpose of this app is to advise users of their surroundings and overall allow safer commuting around Chicago. The app will periodically inform users of the crime frequency 
          and most recurring category of crime around a given destination or their own given location.
        </p>

        <a href="https://github.com/nkh361/chicago-crime-analyses" target="_blank" rel="noopener"> Repository link </a>
    </div>
</template>

<script>
export default {
    name: 'homebody',
    props: {
        msg: String
    }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
</style>
