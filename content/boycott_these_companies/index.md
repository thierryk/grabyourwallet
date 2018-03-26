---
title: "Boycott These Companies"
date: 2018-03-10T13:45:54-08:00
id: "boycott"
---

<style>
.content > ul > li > a {font-weight:600;}  
.content > ul > li {margin-bottom:30px;}  
dt {font-weight:600;color:#777;}
h2 {color:#333;}
h2 {margin-top:40px;padding-top:40px;} 
h3 {color:#555;padding-top:20px;}
dl {border-bottom:10px solid #ececec;padding-bottom:40px;}
dt:first-child,
dt:last-of-type {float:left;margin-right:10px;}
</style>

<p style="text-align:center;font-size:1.5rem;background:red;color:white;padding:5px 10px;" id="message"></p>

**If you are contacting a company about Trump products / affiliations, here's a sample of what you can say:**

> Hi. <br>I’m a customer of [CompanyName]. Unfortunately I can no longer do business with your company because it does business with the Trump family. <br>If your company were to no longer do this, I would enthusiastically return as a customer. <br>Please communicate my feedback to management.

**If you are contacting a company about its ties to the gun industry and/or NRA, here's a sample of what you can say:**

> Hi. <br>I’m a customer of [CompanyName]. Unfortunately I can no longer do business with your company due to its ties to the gun industry. <br>If your company were to sever these ties, I would enthusiastically return as a customer. <br>Please communicate my feedback to management.

Download a [printable PDF version of this list](companies-to-boycott.pdf).

Get the official #GrabYourWallet Chrome plug-in:
<a href="https://chrome.google.com/webstore/detail/grabyourwallet-official-p/aejhdceoomopkpcjclpfcjogibhjplcc">
<img style="margin-top:20px;width:100%;box-shadow: 2px 2px 5px #999;border: 1px solid #cecece;" src="/plugin.png">
</a>

**Table of Content**

{{< readfile file="/content/boycott_these_companies/companies-to-boycott.md" markdown="true" >}}

<script>
// From https://gist.github.com/Almoullim/2e7a4858428cc40c60a9431342adbcfb
var _MS_PER_DAY = 1000 * 60 * 60 * 24;
// Array of month Names
var monthNames = new Array("January","February","March","April","May","June","July","August","September","October","November","December");
var now = new Date();
// a and b are javascript Date objects
function dateDiffInDays(a, b) {
  // Discard the time and time-zone information.
  var utc1 = Date.UTC(a.getFullYear(), a.getMonth(), a.getDate());
  var utc2 = Date.UTC(b.getFullYear(), b.getMonth(), b.getDate());
  return Math.floor((utc2 - utc1) / _MS_PER_DAY);
}
// starting date
var a = new Date("2016-10-23"),
    b = new Date(),
    difference = dateDiffInDays(a, b);
// Plug the message into the page
var message = document.getElementById("message");
message.innerHTML = "Today&mdash;" + monthNames[now.getMonth()] + " " + now.getDate() + ", " + now.getFullYear() + "&mdash;is day number <b> " + difference + "</b> of the #GrabYourWallet Boycott";
</script>
