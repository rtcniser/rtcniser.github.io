---
permalink: /team1/
layout: page
title: Team
---
<style>
        .tabs {
            display: flex;
            flex-direction: row;
            width: 97%;
            border-right: 2px solid #ccc;
            padding-right: 10px;
            overflow-x: none;
            background-color: black;
            padding: 10px;
            border-bottom: 3px solid darkgoldenrod;
        }
        .tabs button {
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
    }
        .img_item {
            width: 23%;
            align-items: center;
            padding: 5px 15px 5px 0px;
    }
        img {
            height: 300px;
            width: 100%;
            border-radius: 50px 50px 50px 50px;
    }
        .item_data {
            width: 100%;
            font-size: 16px;
            text-align: center;
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
        <button class="tablink" onclick="openTab(event, 'Tab310')">2015</button>
    </div>
    <div class="content">
    <div id="Tab1" class="tabcontent" style="display:none;">
            <img src="image2.jpg" alt="Image 2">
    </div>
    <div id="Tab2" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2023_abhinav.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Abhinav Raj</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_mridul.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Aditya Mridul</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_arya.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Arya Niyogi</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_dad.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Dadhichi Das</span>
                </div>
                </div>
            </div>
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2023_joshna.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Joshna Anna Sam</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_anshika.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Anshika Singhal</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_linna.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Linna Rose Tojan</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_mayukh.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Mayukh Ghosh</span>
                </div>
                </div>
            </div>
            <div class="img_cont">
              <div class="img_item">
                <img src="/profile_images/2023_neha.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Neharika Varma</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2023_niki.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Nikitha Kumaraguru</span>
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
        <div id="Tab3" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2022_gayatri.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Gayatri P</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2022_kamble.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Aditya Pravin Kamble</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2022_karan.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Karan Kumar Sahoo</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2022_sanata.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Sanat Kumar Behera</span>
                </div>
                </div>
            </div>
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2022_soumya.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Soumya Ranjan Jena</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2022_vishal.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Vishal Meena</span>
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
        <div id="Tab4" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2021_abhishek.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Abhishek Singh</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2021_girija.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Girija Sankar Ray</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2021_pritipriya.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Pritipriya Dasbehera</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2021_sandipan.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Sandipan Samanta</span>
                </div>
                </div>
            </div>
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2021_saraf.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Aaditya Vicram Saraf</span>
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
        <div id="Tab5" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2020_aritra.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Aritra Mukhopadhyay</span>
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
        <div id="Tab6" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2019_vasanth.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">R Vasanth Kashyap</span>
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
        <div id="Tab7" class="tabcontent">
            <div class="img_cont">
                <div class="img_item">
                <img src="/profile_images/2018_jyo.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Jyothish Kumar J.</span>
                </div>
                </div>
                <div class="img_item">
                <img src="/profile_images/2018_sourav.webp">
                <div class="item_data">
                <br>
                <span style="font-weight: bold;">Sourav Mahto</span>
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
</div>


<script>
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

