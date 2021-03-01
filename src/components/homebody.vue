<template>
    <div id="homebody">
        <h3>
            {{ msg }}
        </h3>
        <h4>
            Stanford Treehacks (hackathon)
        </h4>
        <p>
            During the Treehacks hackathon, I learned and experimented with multiple machine learning principles. The project my group
            worked on was an app that would help a user determine a general risk level of contracting COVID-19 in the user's location.
        </p>
        <br>
        <a href="https://devpost.com/software/covid-19-travel-app" target="_blank" rel="noopener"> Devpost Posting </a>
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