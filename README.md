# Project-1-Lede-Program---Air-Pollution-New-York-vs-China
 
In early June 2023, I was in New York doing the Lede Prgram in Data Journalism at Columbia University. This coincided with Armaggedon-level ochre skies that smelt of charcoal due to wildfires in Canada. I wondered if the AQI level had ever been this bad while I was living in Beijing 2019-2022...I checked the AQI levels over the past three years, and yes it had been, many times, but I had never really taken notice of it. Why? Was it because the skies had never turned orange before in Beijing? Well they had, multiple times, especially in sandstorms. Was it the level of publicity New York's skies had gotten on the news, and how seriously everyone was treating it? Perhaps that was it - this was not normal by US standards, whereas in Beijing it's frequent enough to no longer make headlines. The Chinese government is also pushing legislation to cut down on air pollution - cleaner air and cleaner skies felt the norm while I was in Beijing, rather than the exception. 

I wondered if it was possible to compare what Chinese cities considered bad enough to attract attention, and what New York does. The html file shows my results - that although New York's air pollution levels are still much healthier than China on average, levels that are considered record-breaking by the two countries are **_slowly converging_**.   


<!DOCTYPE html>
<html >
<head>
    <title>How Bad Could It Be?</title>
<style>
  h1{font-family:Georgia}
  h3{font-family:Georgia}
  p{
  font-family:Georgia;
    margin: auto;
  width: 60%;
  padding: 10px;
  border-style: solid;
  border-color: whitesmoke;
  background-color: whitesmoke
}
body {
  background-image: url('smoke.jpeg');
  background-repeat: no-repeat; background-attachment: fixed;
  background-size: cover
}
img{margin: auto;
  border-radius: 25px;
  padding: 20px; 
  width: 900px;
  height: 600px;
}
.center{
  display: block;
  margin-left: auto;
  margin-right: auto;}
</style>
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
<meta name="viewport" content="width=device-width,initial-scale=1">
    <body>
<h1>How Bad Could It Be? </h1>
<h3>Comparing Air Pollution in China and New York</h3>

<img src="smog2.jpeg"
width = "750"
height = "500"
class="center">

<p>On June 6th, the from a cluster of wildfires drifted down 
from Canada into New York City. The city's smog was
<a href="https://www.youtube.com/watch?v=90XCv6gf_fI">worst in the world"</a> at the time - the air quality index reaching 200 during the night of June 6th.</p>

<p>But 'worst' is relative. China's smog is well-documented - 200 is a mild score for some cities. Having lived in Beijing for the past three years, the air quality index broke the 200 mark several times!</p>

<p>That's a serious problem. The <a href="https://www.who.int/health-topics/air-pollution#tab=tab_2">WHO</a> now recognizes air pollution as a major health threat worldwide, prolongued exposure causing around 7 million premature deaths each year.</p>

<p>China's cheap manufacturing industry, lax environmental regulation and 
dependence on coal-fired power stations meant smog was ubiquitous. But in recent years the government has taken steps to reduce air pollution, cutting down on coal-fired power 
stations and strengthening regulations on air pollution.</p>

<p>But it doesn't always work. The city of Huludao in China's industrial north-east still has a reputation for having 'the worst' air pollution in the country. The city's chemical processing  
plants churn out toxic waste into the atmosphere, locals <a href="https://mp.weixin.qq.com/s?__biz=MTc5MTU3NTYyMQ==&mid=2651096311&idx=1&sn=6c10ac4ea8e5c76fa8dc7a73258dc149&chksm=590695dd6e711ccb77e4d8e1eb66b5b81b5d00ccb18c149bcaff7d0ba4f0680e75bd117ff08b&mpshare=1&scene=1&srcid=0719xbHMZltjYVsH4BVduo5a&sharer_sharetime=1658375008818&sharer_shareid=844200f2439c517375505c42c00cea8a&exportkey=Af%2FyKesC3leOHjIkOUlHnIc%3D&acctmode=0&pass_ticket=tBX2gLbUhqiOQut%2BOFCZZCwGq%2BtTQ7m38guiXEEwrR9SEuhBiFDq6VeLuqflP%2Fyq&wx_header=0#rd">complaining</a> of regular sore throats, streaming eyes, and even nosebleeds. 
It got so bad by 2022 that Chinese environmental artist "Nut Brother" launched a <a href="https://www.economist.com/china/2022/08/18/the-creative-ways-chinese-activists-protest-pollution">campaign</a> to help the city.</p>

<p>In the past, 'the worst' levels of air pollution in New York have been nowhere near China's "worst". But climate change, and the wildfires that come with it, mean cities across the US (including <a href="https://www.bbc.co.uk/news/av/world-us-canada-54109381">San Francisco</a>) can expect both a new normal, and a new 'worst'. </p>

<p>For this project, I extracted data from <a href="https://aqicn.org/data-platform/register/">The World Air Quality Index Project</a> for four days in New York over the past four years with 
the highest air pollution, and saw how these compared to the worst four days over the past four 
years in Beijing and Huludao. This data was run through pandas, then turned into a chart using Datawrapper. 
Air pollution levels were measured by the level of <a href="https://www.health.ny.gov/environmental/indoors/air/pmq_a.htm">pm2.5</a> in the air, a particle created by burning coal, petrol, and wood -
a particle linked to increased rates of lung and cardiovascular disease when breathed in over a long period of time.</p>

<iframe title="Towering Over the Haze" aria-label="Grouped Column Chart" id="datawrapper-chart-r4YCP" src="https://datawrapper.dwcdn.net/r4YCP/11/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();
</script>

<p>When put together, there is a gradual convergence over four years - Huludao's worst day so far in 2023 is around 
half its personal worst in 2020, while New York's worst day has risen to meet the worst levels of these two Chinese cities.</p>

<p>Measuring 'the worst' does not account for distribution or averages....</p>

<iframe title="Annual Averages Are Lower and More Varied..." aria-label="Grouped Column Chart" id="datawrapper-chart-teoBZ" src="https://datawrapper.dwcdn.net/teoBZ/3/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();
</script>

<p>We are also only halfway through 2023, making for an incomplete data-point for this year - the worst in Beijing and Huludao could be later in the year.</p> 

<p>This is more about perceptions. Wildfires are expected to grow in frequency and severity as global temperatures rise. Meanwhile, China has dramatically <a href="https://www.bloomberg.com/news/articles/2022-06-14/china-s-clean-air-campaign-is-bringing-down-global-pollution#xj4y7vzkg">cut back</a> its air pollution.
In the future, perhaps America's 'worst' will be more regularly on par with China's.</p>
<p>Feel free to look through my <a href="https://github.com/Colvap/Lede-Program-2023---Air-Pollution-New-York-vs-Chinaworking">working</a> on GitHub!</p>

</body>