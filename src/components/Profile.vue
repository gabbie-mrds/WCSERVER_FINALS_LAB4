<template>
    <div id = "profile">
        <div class = "container">
        
        <h3><b>Profile Component</b></h3>
        <div class = "row">
            <div class = "col">
                <img src = "../assets/prof-photo.png">
            </div>
            <div class = "col">
                <h5><b>Objective:</b></h5>
                <p>{{ obj }}</p>
                <h5><b>Name:</b></h5>
                <p>{{ name }}</p>
                <h5><b>Address:</b></h5>
                <p>{{ add }}</p>
                <h5><b>Contact Number:</b></h5>
                <p>{{ ph_num }}</p>
                <h5><b>Email:</b></h5>
                <p>{{ email }}</p>
                <h5><b>Course:</b></h5>
                <p>{{ course }}</p>
            </div>
        </div>
            
        </div>
    </div>
</template>

<script>
    export default{
        name: "profile",
        data(){
            return{
                obj: "To obtain a responsible and ambitious position with a forward-thinking company where my knowledge and competencies will be put to good use, as well as to continue to grow.",
                name: "Gabrielle Mae Rose S. Delos Santos",
                add: "Pampang, Angeles City, Pampanga 2009",
                ph_num: "+63 929-819-3934",
                email: "gabmrds@gmail.com",
                course: "Bachelor of Science in Information Technology",
                
            }
        }
    }
</script>
