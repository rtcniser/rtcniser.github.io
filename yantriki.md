---

title: Yantriki
layout: page
permalink: /yantriki/

---
<style>
    .imgarea{
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        justify-content: space-around;
        align-items: stretch;
    }
    .imgcont {
        width: 45%;
        height: 300px;
    }
    .logo{
        height: 250px;
        width: 250px;
        border-radius: 50%;
    }
    .text {
        width: 100%;
        font-family: MyCustomFont
    }
    @media (max-width: 768px) {
        .imgarea{
        display: flex;
        flex-direction: column;
        flex-wrap: nowrap;
        justify-content: center;
        align-items: stretch;
    }
    .imgcont {
        width: 100%;
        height: 400px;
    }
    .logo{
        height: 250px;
        width: 250px;
        border-radius: 50%;
    }
    .text {
        width: 100%;
        font-family: MyCustomFont
    }
    .poster {
        width: 100%;
        height: 500px;
    }
@media (max-width: 768px) {
    .poster {
        width: 100%;
        height: 250px;
    }
}
</style>

<hr>
<br>
<center>
    <br>
    <p style="font-size: 20px">Yantriki is our inter-college robotics and technology magazine for nationwide yearly publication. College students all across India send their entries in the form of project blogs, research articles, tutorials or academic discussions in robotics. </p>
    <br>
<br>
<h2 style="font-family: MyCustomFont; text-decoration: underline;">Currently Conducting:</h2>
<br>
<h3>Edition 2:</h3>
<a href="{{ '/subpages/yantrikied2/' | relative_url }}">
<img class="poster" src="/images/yantrikied2_1000x290.jpg" style="object-fit: fill; border-radius: 80px; transition: background-color 0.3s, transform 0.3s;" onmouseover="this.style.backgroundColor='black'; this.style.transform='scale(1.05)'" onmouseout="this.style.backgroundColor='white'; this.style.transform='scale(1)'"></a>
<br>
<br>
<h2 style="font-family: MyCustomFont; text-decoration: underline;">Previous Editions:</h2>
<br>
<br>
<h3>Edition 1:</h3>
<a href="{{ '/subpages/yantrikied1/' | relative_url }}">
<img src="/images/Yantriki2-1024x428.png.webp" width="1000px" height="260px" style=" object-fit: fill; border-radius: 80px; transition: background-color 0.3s, transform 0.3s;" onmouseover="this.style.backgroundColor='black'; this.style.transform='scale(1.05)'" onmouseout="this.style.backgroundColor='white'; this.style.transform='scale(1)'"></a>
</center>
<br>
<br>
<br>
<br>
<h3>Powered By:</h3>
<br>
<center>
<div class="imgarea">
    <div class="imgcont">
    <img src="/images/niser.webp" class="logo">
    <div class="text">
    <br>
    <span>National Institute for Science Education and Research, Bhubaneswar</span>
    </div>
    </div>
    <div class="imgcont">
    <img src="/images/smlab.png" class="logo">
    <div class="text">
    <br>
    <span>Subhankar Mishra LAB, School of Computer Sciences, NISER</span>
    </div>
    </div>
</div>
</center>
