---
layout: post
title:  "Conference Timeline Tracking"
date:   2023-02-01 00:00:00 +0800
categories: jekyll update
---
<span id="demo" data-dates="2023-02-27 14:45 GMT"/> 

<script>
//countDownCell("demo");
function pad(num, size) {
    num = num.toString();
    while (num.length < size) num = "0" + num;
    return num;
}

function countDownCell(strDate, tagID){
   str = strDate;//document.getElementById(tagID).dataset.dates; //"2023-10-1";
   var countDownDate = new Date(str).getTime();

// Update the count down every 1 second
  var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();

  // Find the distance between now and the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in the element with id=tagID
  document.getElementById(tagID).innerHTML = days + "days " + pad(hours,2) + ":"
  + pad(minutes,2) + ":" + pad(seconds,2);

  // If the count down is finished, write some text
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "Passed";
  }
}, 1000);
}

</script>

Track of conference timelines.

|**SIGGRAPH Asia 2023** [URL](https://asia.siggraph.org/2023/submissions/)| | Countdown | 
|Abstract deadline | 2023-05-16|  |
|Papers deadline| 2023-05-23 23:59 AoE| <span id="sa23"/> <script>countDownCell("2023-05-23 23:59 GMT-12","sa23")</script> |
|Reviews released to authors| - |  |
|Rebuttals due| - |  |
|Author notification| - |  |
|Final papers due| - |  |
|Conference| - |  |
| | |
|**EGSR 2023** [URL](https://conferences.eg.org/egsr2023/)| |
|Abstract deadline | 2023-04-05 | 
|Papers deadline| 2023-04-12 | <span id="sr23"/> <script>countDownCell("2023-04-12 23:59","sr23")</script> |
|Reviews released to authors| 2023-05-15 |
|Rebuttals due| 2023-05-19 |
|Author notification| 2023-05-26 |
|Final papers due| 2023-06-09 |
|Conference| 2023-06-28 |
| | |
|**ICCV 2023** [URL](https://iccv2023.thecvf.com/) |  |
|Paper submission deadline | 2023-03-08 (23:59 UTC) | <span id="iccv23"/> <script>countDownCell("2023-03-08 23:59 GMT","iccv23")</script>  |
|Supplementary material deadline| 2023-03-15 (23:59 UTC) |
|Reviews released to authors| 2023-05-23 |
|Rebuttal due| 2023-05-31 (23:59 UTC)|
|Announcement of decisions | 2023-07-13 |
| | |
|**SIGGRAPH 2023** [URL](https://s2023.siggraph.org/program/technical-papers/) |  |
|Paper submission deadline | 2023-01-25 (22:00 UTC) | <span id="sig23"/> <script>countDownCell("2023-01-25 22:00 GMT","sig23")</script>  |
|Reviews released to authors| 2023-03-05 |
|Rebuttal due|  2023-03-10 (22:00 UTC)|
|Announcement of decisions | 2023-03-27 |
|Revised paper deadline | 2023-04-25 |
|Final version deadline | 2023-05-02 |
|Fastforward deadline | 2023-07-07 |
|Official publication date | 2023-07-23 |

