---
permalink: /team/
layout: page
title: Team
---
<style>
        .tabs {
            display: flex;
            flex-direction: row;
            flex-wrap: wrap;
            justify-content: center;
            width: 97%;
            border-right: 2px solid #ccc;
            padding-right: 10px;
            overflow-x: none;
            background-color: black;
            padding: 10px;
            border-bottom: 3px solid darkgoldenrod;
        }
        .tabs button {
            flex-grow: 1;
            min-width: 50px;
            text-align: center;
            padding: 10px;
            background: none;
            border: none;
            padding: 10px;
            cursor: pointer;
            font-size: 16px;
            text-align: left;
            width: 10%;
            color: white;
            font-family: 'Baskerville', serif;
            padding: 10px 15px;
            cursor: pointer;
            border: none;
            background: none;
            font-size: 16px;
            transition: color 0.3s, border-bottom 0.3s;
            flex-shrink: 0;
        }
        .tabs button.active {
            background-color: darkgoldenrod;
            border-bottom: solid 2px white;
        }
        .content {
            flex-grow: 1;
            padding: 20px;
        }
        .content img {
            max-width: 100%;
        }
        .img_cont {
            display: flex;
            width: 100%;
            justify-content: space-between;
            flex-direction: row;
            margin: 20px 50px 20px 20px;
    }
        .img_item {
            position: relative;
            width: 23%;
            align-items: center;
            padding: 5px 15px 5px 0px;
            overflow: hidden;
        }

        .img_item img {
            height: 300px;
            width: 100%;
            border-radius: 50px;
            object-fit: cover;
            transition: transform 0.3s ease-in-out;
        }

        .img_item:hover img {
            transform: scale(1.1);
        }

        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            opacity: 0;
            transition: opacity 0.3s ease-in-out;
            border-radius: none;
        }

        .img_item:hover .overlay {
            opacity: 1;
        }

        .overlay span {
            font-weight: bold;
            font-size: 18px;
            font-family: MyCustomFont;
            margin-top: 190px;
        }

        .overlay p {
            font-size: 16px;
            margin-top: 5px;
        }
        .item_data {
            width: 100%;
            font-size: 16px;
            text-align: center;
    }
        .epithet{
            font-size: 24px;
            font-weight: bold;
            color: orange;
            text-shadow: 0 0 5px #ff8c00, 0 0 10px #ff8c00, 0 0 15px #ff4500;
            animation: flicker 0.1s infinite alternate;
        }
        @media (max-width: 768px)
    {
        .img_cont {
            display: flex;
            width: 100%;
            justify-content: space-between;
            flex-direction: column;
    }
        .img_item {
            width: 100%;
            align-items: center;
            padding: 5px 15px 5px 0px;
            margin-bottom: 5px;
    }
        img {
            height: 400px;
            width: 100%;
            object-fit: cover;
            border-radius: 50px 50px 50px 50px;
    }
        .item_data {
            width: 100%;
            font-size: 16px;
            text-align: center;  
    }
        .img_item:active .overlay {
            opacity: 1;
}

        .img_item:active img {
            transform: scale(1.1);
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.5);
}

    }
@keyframes flicker {
    0% { opacity: 0.8; text-shadow: 0 0 5px #ff8c00, 0 0 10px #ff8c00, 0 0 15px #ff4500; }
    50% { opacity: 1; text-shadow: 0 0 8px #ff8c00, 0 0 15px #ff4500, 0 0 20px #ff4500; }
    100% { opacity: 0.9; text-shadow: 0 0 6px #ff8c00, 0 0 12px #ff8c00, 0 0 18px #ff4500; }
}
@keyframes shine-light {
    0% { left: -100%; }
    100% { left: 100%; }
}
</style>    
<hr>
<div class="veil">
<br>
<center><p><h4 style="color: gray; font-size: 30px; font-family: MyCustomFont;">"A strong organisation needs an even stronger community to support it."</h4></p></center> 

<center><p><h4 style="font-style: italic; font-size: 22px;">Here is the list of our dedicated team members...</h4></p></center>
<br>
<br>

<div class="tabs">
        <button class="tablink" onclick="openTab(event, 'Tab1')">2024</button>
        <button class="tablink active" onclick="openTab(event, 'Tab2')">2023</button>
        <button class="tablink" onclick="openTab(event, 'Tab3')">2022</button>
        <button class="tablink" onclick="openTab(event, 'Tab4')">2021</button>
        <button class="tablink" onclick="openTab(event, 'Tab5')">2020</button>
        <button class="tablink" onclick="openTab(event, 'Tab6')">2019</button>
        <button class="tablink" onclick="openTab(event, 'Tab7')">2018</button>
        <button class="tablink" onclick="openTab(event, 'Tab8')">2017</button>
        <button class="tablink" onclick="openTab(event, 'Tab9')">2016</button>
        <button class="tablink" onclick="openTab(event, 'Tab10')">2015</button>
    </div>
    <div class="content">
    <div id="Tab1" class="tabcontent" style="display:none;">
            <p>Still Recruiting...</p>
    </div>
    <div id="Tab2" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2023_dad.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Dadhichi Das</span>
                <p style="font-weight: bold;">Technical (Club Head, 2025)
                <br><span class="epithet">Streamroller!</span></p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_neha.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Neharika Varma</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_joshna.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Joshna Anna Sam</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_rikan.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Rikan Mahakur</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
            </div>
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2023_arya.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Arya Niyogi</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_anshika.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Anshika Singhal</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_mayukh.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Mayukh Ghosh</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_abhinav.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Abhinav Raj</span>
                <p style="font-weight: bold;">Events</p>
                </div>
                </div>
            </div>
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2023_mridul.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Aditya Mridul</span>
                <p style="font-weight: bold;">Webmaster, Yantriki
                <br><span class="epithet">They didn't pay me for all this.</span></p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_niki.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Nikitha Kumaraguru</span>
                <p style="font-weight: bold;">Yantriki</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_bratanu.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Bratanu Saha</span>
                <p style="font-weight: bold;">Yantriki</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_linna.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Linna Rose Tojan</span>
                <p style="font-weight: bold;">Yantriki</p>
                </div>
                </div>
            </div>
        </div>
        <div id="Tab3" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2022_gayatri.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Gayatri P</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2022_kamble.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Aditya Pravin Kamble</span>
                <p style="font-weight: bold;">Technical
                <br><span class="epithet">The Unrealized Engineer!</span></p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2022_karan.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Karan Kumar Sahoo</span>
                <p style="font-weight: bold;">Technical
                <br><span class="epithet">Perseverance through skill issues!</span></p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2022_sanata.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Sanat Kumar Behera</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
            </div>
            <div class="img_cont">
            <div class="img_item">
                <img src="/profile_images/2022_vishal.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Vishal Meena</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2022_soumya.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Soumya Ranjan Jena</span>
                <p style="font-weight: bold;">Events (Co-ordinator, 2024-2025)</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2022_shibashis.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Shibashis Divyajyoti</span>
                <p style="font-weight: bold;">Hackduino (Co-ordinator, 2024-2025)</p>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
            </div>
            <br>
            <br>
            <p style="font-size: 30px; text-decoration: underline;">Brief Contributors: <br>
            <ul>
            <li>Shakya Ratna Wahane</li>
            <li>Suraj Pradhan</li>
            <li>Prasad Murmu</li>
            <li>Suraj Kumar Behera</li>
            </ul>
            </p>
        </div>
        <div id="Tab4" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2021_girija.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Girija Sankar Ray</span>
                <p style="font-weight: bold;">Technical (Club Head, 2023-2025)</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2021_saraf.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Aaditya Vicram Saraf</span>
                <p style="font-weight: bold;">Technical
                <br><span class="epithet">"You make an account on Onshape. Now know how to 3D model."</span></p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2021_pritipriya.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Pritipriya Dasbehera</span>
                <p style="font-weight: bold;">Technical, Events</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2021_sandipan.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Sandipan Samanta</span>
                <p style="font-weight: bold;">Technical
                <br><span class="epithet">Engineering easy :)</span></p>
                </div>
                </div>
            </div>
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2021_vishnu.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Vishnu Santosh Kumar</span>
                <p style="font-weight: bold;">Hackduino (Co-ordinator, 2023-2024)</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2021_abhishek.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Abhishek Singh</span>
                <p style="font-weight: bold;">Yantriki(Co-ordinator, 2024-2025)</p>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
            </div>
            <br>
            <br>
            <p style="font-size: 30px; text-decoration: underline;">Brief Contributors: <br>
            <ul>
            <li>S. Mahesh</li>
            <li>Rahul Madhav M</li>
            <li>Sreerag M</li>
            </ul>
            </p>
        </div>
        <div id="Tab5" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2020_aritra.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Aritra Mukhopadhyay</span>
                <p style="font-weight: bold;">Technical
                <br><span class="epithet">Lol! Tooo Much Skills!</span></p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Tanishaa Aswin</span>
                <p style="font-weight: bold;">Yantriki</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Upasana Das</span>
                <p style="font-weight: bold;">Yantriki</p>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
            </div>
        </div>
        <div id="Tab6" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2019_opj.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Oommen P. Jose</span>
                <p style="font-weight: bold;">Technical (Club Head, 2022-2023)
                <br><span class="epithet">Sweet guy!</span></p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2019_sarin.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Sarin C. Jacob</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2019_krishnakant.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Krishnakant Parida</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2019_vasanth.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">R Vasanth Kashyap</span>
                <p style="font-weight: bold;">Hackduino</p>
                </div>
                </div>
            </div>
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Sreehari C</span>
                <p style="font-weight: bold;">Yantriki (Co-ordinator, 2022-23)</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Yashaswini Gupta</span>
                <p style="font-weight: bold;">Yantriki</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Prajwal Roopamath M M</span>
                <p style="font-weight: bold;">Yantriki</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Aditi Pradhan</span>
                <p style="font-weight: bold;">Yantriki</p>
                </div>
                </div>
            </div>
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Ajay Krishna A</span>
                <p style="font-weight: bold;">Yantriki</p>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
            </div>
            <br>
            <br>
            <p style="font-size: 30px; text-decoration: underline;">Brief Contributors: <br>
            <ul>
            <li>Sandeepan Sahoo</li>
            </ul>
            </p>
        </div>
        <div id="Tab7" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2018_jyo.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Jyothish Kumar J.</span>
                <p style="font-weight: bold;">Technical (Club Head, 2019-2022)
                <br><span class="epithet">The one man gang and the first true roboticist.</span></p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2018_sourav.webp">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Sourav Mahto</span>
                <p style="font-weight: bold;">Technical
                <br><span class="epithet">Airborne Talents!</span></p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Shriman Keshri</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Debankit Priyadarshi</span>
                <p style="font-weight: bold;"></p>
                </div>
                </div>
            </div>
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Devansh Sharma</span>
                <p style="font-weight: bold;"></p>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
        </div>
        </div>
        <div id="Tab8" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Jyotirmoy Shivottam</span>
                <p style="font-weight: bold;">Technical</p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Abhinav Gupta</span>
                <p style="font-weight: bold;"></p>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Nitesh Kumar Patel</span>
                <p style="font-weight: bold;"></p>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
            </div>
        </div>
        <div id="Tab9" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/tooshy.jpg">
                <div class="overlay">
                <br>
                <span style="font-weight: bold;">Manabputra</span>
                <p style="font-weight: bold;">Club Head (2017-2019)</p>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
                <div class="img_item">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;"></span>
                </div>
                </div>
        </div>
        </div>
</div>
<br>
<br>
<p class="headings">Faculty In-Charge:</p>
<hr>
<br>
<img float="left" style="border-radius: 100px; border: solid 5px black; margin-right: 30px; border-radius: 10px;
    box-shadow: 0 0 15px rgba(255, 165, 0, 0.8), 0 0 30px rgba(255, 69, 0, 0.6); border-radius: 50px;" align=left src="/profile_images/subhankar.webp" height= "300" width= "300">
<br>
<p style="font-weight: bold; font-size: xx-large;">Dr. Subhankar Mishra</p>
<p>His visionary guidance inspires creativity and innovation, propelling the club members to push boundaries and excel in their projects. As <strong><em>Faculty-In-Charge</em></strong>, Dr. Subhankar Mishra cultivates a spirit of collaboration, empowering students to work together seamlessly towards their shared goals.
<br>
<br>
<center><a href="https://smlab.niser.ac.in/"><button style="border-radius: 5px; color: black; padding: 8px 16px; cursor: pointer;">Visit Website</button></a></center>
</p>
<br>
<br>
<br>
<br>
<script>
    document.addEventListener("DOMContentLoaded", function() {
    var tabcontent = document.getElementsByClassName("tabcontent");
    for (var i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    document.getElementById("Tab2").style.display = "block";
});
        function openTab(event, tabName) {
            var i, tabcontent, tablinks;
            tabcontent = document.getElementsByClassName("tabcontent");
            for (i = 0; i < tabcontent.length; i++) {
                tabcontent[i].style.display = "none";
            }
            tablinks = document.getElementsByClassName("tablink");
            for (i = 0; i < tablinks.length; i++) {
                tablinks[i].className = tablinks[i].className.replace(" active", "");
            }
            document.getElementById(tabName).style.display = "block";
            event.currentTarget.className += " active";
        }
    </script>
