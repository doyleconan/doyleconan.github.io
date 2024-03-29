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

|**SIGGRAPH 2024** [URL](https://s2024.siggraph.org/program/technical-papers/)| | Countdown | 
|Registration Deadline | 2024-01-23|  |
|Submission Deadline| 2024-01-24 22:00 GMT| <span id="sig24"/> <script>countDownCell("2024-01-24T22:00-0000","sig24")</script> |
|Reviews released to authors| 2024-03-05 |  |
|Rebuttals due| 2024-03-10 22:00 GMT| <span id="sig24r"/> <script>countDownCell("2024-03-10T22:00-0000","sig24r")</script> |
|Author notification| 2024-03-25 |  |
|Conference| 2024-07-28 |  |
| | |
|**CVPR 2024** [URL](https://cvpr.thecvf.com/Conferences/2024)| | Countdown | 
|Registration Deadline | 2023-11-03|  |
|Submission Deadline| 2023-11-10 23:59 PST| <span id="cvpr24"/> <script>countDownCell("2023-11-10T23:59-0800","cvpr24")</script> |
|Supplementary Deadline| 2023-11-17 23:59 PST| <span id="cvpr24s"/> <script>countDownCell("2023-11-17T23:59-0800","cvpr24s")</script> |
|Reviews released to authors| 2024-01-23 |  |
|Rebuttals due| 2024-01-30 23:59 PST| <span id="cvpr24r"/> <script>countDownCell("2024-01-30T23:59-0800","cvpr24r")</script> |
|Author notification| 2024-02-26 |  |
|Conference| 2024-06-19 |  |
| | |
|**PG 2023** [URL](https://pg2023.org/call-for-technical-papers)| | Countdown | 
|Abstract deadline | 2023-06-05|  |
|Papers deadline| 2023-06-08 23:59 AoE|  |
|Reviews released to authors| 2023-07-21 |  |
|Rebuttals due| 2023-07-28 |  |
|Author notification| 2023-08-12 |  |
|Final papers due| 2023-09-01 |  |
|Conference| 2023-10-10 |  |
| | |
|**SIGGRAPH Asia 2023** [URL](https://asia.siggraph.org/2023/submissions/)| | Countdown | 
|Abstract deadline | 2023-05-16|  |
|Papers deadline| 2023-05-23 23:59 AoE|  |
|Reviews released to authors| - |  |
|Rebuttals due| - |  |
|Author notification| - |  |
|Final papers due| - |  |
|Conference| - |  |
| | |
|**EGSR 2023** [URL](https://conferences.eg.org/egsr2023/)| |
|Abstract deadline | 2023-04-05 | 
|Papers deadline| 2023-04-12 |  |
|Reviews released to authors| 2023-05-15 |
|Rebuttals due| 2023-05-19 |  |
|Author notification| 2023-05-26 |
|Final papers due| 2023-06-09 |
|Conference| 2023-06-28 |
| | |
|**ICCV 2023** [URL](https://iccv2023.thecvf.com/) |  |
|Paper submission deadline | 2023-03-08 (23:59 UTC) |   |
|Supplementary material deadline| 2023-03-15 (23:59 UTC) |
|Reviews released to authors| 2023-05-23 |
|Rebuttal due| 2023-05-31 (23:59 UTC)|
|Announcement of decisions | 2023-07-13 |
| | |
|**SIGGRAPH 2023** [URL](https://s2023.siggraph.org/program/technical-papers/) |  |
|Paper submission deadline | 2023-01-25 (22:00 UTC) |  |
|Reviews released to authors| 2023-03-05 |
|Rebuttal due|  2023-03-10 (22:00 UTC)|   |
|Announcement of decisions | 2023-03-27 |
|Revised paper deadline | 2023-04-25 |
|Final version deadline | 2023-05-02 |
|Fastforward deadline | 2023-07-07 |
|Official publication date | 2023-07-23 |

