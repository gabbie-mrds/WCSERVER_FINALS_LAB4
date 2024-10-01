<template>
    <div id = "education">
        <div class = "container">
            <h3><b>Education Component</b></h3>

            <h5><b>College:</b></h5>
            <p>School: {{ college }}</p>
            <p>Years Attended: 2022 - Present</p>

            <h5><b>Senior High School</b></h5>
            <p>School: {{ shs }}</p>
            <p>Years Attended: 2020 - 2022</p>

            <h5><b>Junior High School</b></h5>
            <p>School: {{ jhs }}</p>
            <p>Years Attended: 2016 - 2020</p>

            <h5><b>Elementary School</b></h5>
            <p>School: {{ elem }}</p>
            <p>Years Attended: 2007 - 2016</p>

        </div>
    </div>
</template>

<script>
    export default{
        name: "education",
        data(){
            return{
                elem: "Achievers Special Education Center",
                jhs: "Republic Central Colleges",
                shs: "New Era University - Pampanga Branch",
                college: "Holy Angel University"
            }
        }
    }
</script>