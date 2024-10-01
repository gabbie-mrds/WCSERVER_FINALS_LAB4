<template>
    <div id = "skills">
        <div class = "container">
            <h3><b>{{ msg }}</b></h3>

            <div class = "row border border-black" >
                <div class = "col"> <h5><b>Training</b></h5></div>
                <div class = "col border border-black">
                    <ul>
                        <li>CompTia ITF+ (2023)</li>
                        <br>
                        <li>Cisco Certification in Introduction to Networks (2023/2024)</li>
                        <br>
                        <li>Cisco Certification in Cybersecurity Essentials (2024/2024)</li>
                    </ul>
                </div>
            </div>

            <br>
            <div class = "row border border-black">
                <div class = "col">
                   <h5><b>Seminars</b></h5>
                </div>
                <div class = "col border border-black">
                    <ul>
                        <li>SEO Rank and Rise (2024)</li><br>
                        <li>Remote: A New Normal Workplace (2023)</li>
                    </ul>
                </div>
            </div>

            <br>

            <div class = "row border border-black">
                <div class = "col"><h5><b>Technologies</b></h5></div>
                <div class = "col border border-black">
                    <ul>
                        <li>Programming</li><br>
                        <li>Data Management</li><br>
                        <li>Web Development</li>
                    </ul>
                </div>
            </div>

            <br>

            <div class = "row border border-black">
                <div class = "col"><h5><b>Programming Languages</b></h5></div>
                <div class = "col border border-black">
                    <ul>
                        <li>HTML</li><br>
                        <li>CSS</li><br>
                        <li>PHP</li><br>
                        <li>SQL</li><br>
                        <li>NoSQL</li><br>
                        <li>Python</li><br>
                        <li>Java</li><br>
                        <li>JavaScript</li>
                        
                    </ul>
                </div>
            </div>

        </div>
    </div>
</template>

<script>
    export default{
        name: "skills",
        data(){
            return{
                msg: "Skills Component"
            }
        }
    }
</script>