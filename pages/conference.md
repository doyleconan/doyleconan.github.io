---
layout: post
title:  "Conference Timeline Tracking"
date:   2023-02-01 00:00:00 +0800
categories: jekyll update
---
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
    document.getElementById(tagID).innerHTML = "Passed";
  }
}, 1000);
}

</script>

Track of conference timelines.

|**SIGGRAPH 2026** [URL](https://s2026.siggraph.org/program/technical-papers/)| | Countdown |
|Registration Deadline | 2026-01-15|  |
|Submission Deadline| 2026-01-22 23:59 AoE| <span id="sig26"/> <script>countDownCell("2026-01-22T23:59-1200","sig26")</script> |
|Conference| 2026-07-19 to 2026-07-23 |  |
| | |
|**CVPR 2026** [URL](https://cvpr.thecvf.com/Conferences/2026)| | Countdown |
|Abstract Deadline | 2025-11-07 23:59 AoE|  |
|Submission Deadline| 2025-11-13 23:59 AoE| <span id="cvpr26"/> <script>countDownCell("2025-11-13T23:59-1200","cvpr26")</script> |
|Supplementary Deadline| 2025-11-20 23:59 AoE| <span id="cvpr26s"/> <script>countDownCell("2025-11-20T23:59-1200","cvpr26s")</script> |
|Reviews released to authors| 2026-01-22 |  |
|Rebuttals due| 2026-01-29 23:59 AoE| <span id="cvpr26r"/> <script>countDownCell("2026-01-29T23:59-1200","cvpr26r")</script> |
|Author notification| 2026-02-20 |  |
|Conference| 2026-06-03 to 2026-06-07 |  |
| | |
|**ICCV 2025** [URL](https://iccv.thecvf.com/) | | Countdown |
|Paper registration deadline | 2025-03-03 23:59 HST| <span id="iccv25reg"/> <script>countDownCell("2025-03-03T23:59-1000","iccv25reg")</script> |
|Paper submission deadline | 2025-03-07 23:59 HST| <span id="iccv25"/> <script>countDownCell("2025-03-07T23:59-1000","iccv25")</script> |
|Reviews released to authors| 2025-05-09 |  |
|Rebuttal due| 2025-05-16 23:59 HST| <span id="iccv25r"/> <script>countDownCell("2025-05-16T23:59-1000","iccv25r")</script> |
|Announcement of decisions | 2025-06-20 |  |
|Conference| 2025-10-19 to 2025-10-23 |  |
| | |
|**SIGGRAPH Asia 2026** [URL](https://asia.siggraph.org/2026/submissions/technical-papers/)| | Countdown |
|Abstract deadline | 2026-05-05 23:59 AoE| <span id="siga26a"/> <script>countDownCell("2026-05-05T23:59-1200","siga26a")</script> |
|Papers deadline| 2026-05-12 23:59 AoE| <span id="siga26"/> <script>countDownCell("2026-05-12T23:59-1200","siga26")</script> |
|Conference| 2026-12-01 to 2026-12-04 |  |
| | |
|**SIGGRAPH Asia 2025** [URL](https://asia.siggraph.org/2025/submissions/technical-papers/)| | Countdown |
|Abstract deadline | 2025-05-16 23:59 AoE|  |
|Papers deadline| 2025-05-23 23:59 AoE|  |
|Conference| 2025-12-15 to 2025-12-18 |  |
| | |
|**EGSR 2026** [URL](https://egsr2026.inria.fr/)| | Countdown |
|Abstract deadline | 2026-04-08 23:59 AoE| <span id="egsr26a"/> <script>countDownCell("2026-04-08T23:59-1200","egsr26a")</script> |
|Papers deadline| 2026-04-15 23:59 AoE| <span id="egsr26"/> <script>countDownCell("2026-04-15T23:59-1200","egsr26")</script> |
|Reviews released to authors| 2026-05-11 |
|Rebuttals due| 2026-05-15 23:59 AoE| <span id="egsr26r"/> <script>countDownCell("2026-05-15T23:59-1200","egsr26r")</script> |
|Author notification| 2026-05-25 |
|Final papers due| 2026-06-10 |
|Conference| 2026-07-01 to 2026-07-03 |
| | |
|**PG 2025** [URL](https://pg2025.nccu.edu.tw/)| | Countdown |
|Abstract deadline | 2025-05-30 23:59 AoE|  |
|Papers deadline| 2025-06-06 23:59 AoE|  |
|Author notification| 2025-08-08 |  |
|Final papers due| 2025-08-23 |  |
|Conference| 2025-10-14 to 2025-10-17 |  |

