---
layout: page
permalink: /research/
title: research
nav: true
nav_order: 2
---

<!-- CSS styles -->

<style>
/* Common styles */
.abstract-button {
    cursor: pointer;
    padding: 5px 15px;
    border: 1px solid;
    background-color: transparent;
    text-align: center;
    outline: none;
    font-size: 14px;
    margin-bottom: 5px;
    border-radius: 4px;
    transition: all 0.3s ease;
}
.abstract-content {
    margin-top: 10px;
    text-align: justify;
    display: none;
    padding: 10px;
    border-radius: 4px;
    background-color: transparent !important; /* Force transparent background */
}

/* Light mode styles */
@media (prefers-color-scheme: light) {
    .abstract-button,
    .abstract-content,
    .publication {
        color: #000000;
    }
    .abstract-button {
        border-color: #000000;
    }
}

/* Dark mode styles */
@media (prefers-color-scheme: dark) {
    .abstract-button,
    .abstract-content,
    .publication {
        color: #ffffff;
    }
    .abstract-button {
        border-color: #ffffff;
    }
}

/* Ensure styles are applied regardless of HTML theme attribute */
html[data-theme='dark'] .abstract-button,
html[data-theme='dark'] .abstract-content,
html[data-theme='dark'] .publication {
    color: #ffffff;
}
html[data-theme='dark'] .abstract-button {
    border-color: #ffffff;
}

html:not([data-theme='dark']) .abstract-button,
html:not([data-theme='dark']) .abstract-content,
html:not([data-theme='dark']) .publication {
    color: #000000;
}
html:not([data-theme='dark']) .abstract-button {
    border-color: #000000;
}
    
</style>

<script>
// Function to hide all abstracts on page load
function hideAllAbstracts() {
    var abstracts = document.querySelectorAll('.abstract-content');
    abstracts.forEach(function(abstract) {
        abstract.style.display = 'none';
    });
}

// Function to toggle abstract visibility
function toggleAbstract(id) {
    var content = document.getElementById(id);
    if (content.style.display === "none" || content.style.display === "") {
        content.style.display = "block";
    } else {
        content.style.display = "none";
    }
}

// Call hideAllAbstracts when the page loads
document.addEventListener('DOMContentLoaded', hideAllAbstracts);
</script>


## publication

**[Selection and Behavioral Responses of Health Insurance Subsidies in the Long Run: Evidence from a Field Experiment in Ghana](/docs/AKS_Ghana_Published_Version_HE.pdf)** <br>
with Patrick Asuming and Hyuncheol Bryant Kim <br>
*Health Economics, 2024, 33(5): 992–1032.* <br>

<button class="abstract-button" onclick="toggleAbstract('abstract1')">Abstract</button>
<div id="abstract1" class="abstract abstract-content">
We study the effects of a health insurance subsidy in Ghana, where mandates are not enforceable. We randomly provide different levels of subsidy (1/3, 2/3, and full) and evaluate the impact at seven months and three years after the intervention. We find that a one-time subsidy increased insurance enrollment for all groups in both the short and long runs, but health care utilization in the long run increased only for the partial subsidy group. We find supportive evidence that ex-post behavioral responses rather than ex-ante selective enrollment explain the long-run health care utilization results.
</div> 
 {: style="text-align: justify"}
 
**[Addressing Vaccine Hesitancy using Local Ambassadors: A Randomized Controlled Trial in Indonesia](/docs/Vaccine_EER.pdf)** <br>
with Asad Islam, Gita Kusnadi, Jahen Rezki, Giovanni van Empel, Michael Vlassopoulos, and Yves Zenou <br>
*European Economic Review, 2024, 163, 104683* <br>

<button class="abstract-button" onclick="toggleAbstract('abstract2')">Abstract</button>
<div id="abstract2" class="abstract abstract-content">
In settings where resistance and rampant misinformation against vaccines exist, the prospect of containing infectious diseases remains a challenge. Can delivery of information regarding the benefits of vaccination through personal home visits by local ambassadors increase vaccine uptake? We conduct a door-to-door randomized information campaign targeted towards COVID-19 unvaccinated individuals in rural Indonesia. We recruited ambassadors from local villages tasked to deliver information about COVID-19 vaccines and promote vaccination through one-on-one meetings, using an interpersonal behavioral change communication approach. To investigate which type of ambassador—health cadres, influential individuals, and laypersons—is the most effective, we randomly vary the type of ambassador that delivers the information at the village level. We find that the overall vaccination take-up is quite moderate and that there are no differences in vaccination outcomes across the treatment groups. These results highlight the challenge of boosting vaccine uptake in late stages of a pandemic.
</div>
 {: style="text-align: justify"}
 
**[The Consequences of Child Market Work on the Growth of Human Capital](https://www.sciencedirect.com/science/article/pii/S0305750X15308731?via%3Dihub)** <br> 
with Asep Suryahadi and Daniel Suryadarma <br>
*World Development, 2017, 91: 144–155.* <br>

<button class="abstract-button" onclick="toggleAbstract('abstract3')">Abstract</button>
<div id="abstract3" class="abstract abstract-content">
The paper measures the effect of child market work on the long-term growth of human capital, focusing on the output of the human capital production: mathematics skills, cognitive skills, pulmonary function, and educational attainment. Our full sample is drawn from a rich longitudinal dataset Indonesia Family Life Survey (IFLS). We address endogeneity of child market work using provincial legislated minimum wage as the instrument. Our instrumental variable estimation shows that child labor negatively affects mathematics skills and pulmonary function, but not cognitive skills and educational attainment. We find heterogeneities in type of work. Those who work outside of family business have lower educational attainment than those working for family business.
</div>
 {: style="text-align: justify"}
 
 <br>

## working papers 

**Sink or Swim: Testing the Role of Science vs Religion in Raising Environmental Awareness in Indonesia** <br>
with Sarah Gultom, Umair Khalil, Wang Lee, Alyas Widita <br>
 
**Import Restriction, Price Shock, and Local Policy Responses: Evidence from Indonesia** <br>

**Unlocking Immunity: Strategies for Cost-Effective Promotion of COVID-19 Vaccination in Developing Countries** <br>
with Asad Islam, Hyuncheol Bryant Kim, and Deb Prakashi <br>
*Revise and resubmit, Journal of Health Economics* <br>

**Reaching the Last Mile: Results from a Randomised Controlled Trial to Promote COVID-19 Vaccine in Bangladesh** <br>
with Dinesh A., Tarannum B., Ahmedul K., Meerjady F., Diwakar M., Debayan P., Patrick O., Piyush B., Shafiun S., Hyuncheol K., and Asad I. <br>
*Revise and resubmit, Nature: Communications Medicine* <br>

<br>

## works in progress

**Anticipatory and Local Economic Impacts of Mineral Export Ban in Indonesia** <br>
<br>

**The Tyranny of Distance** <br>
with Arya Gaduh <br>

**Economic Crisis and Nation Building** <br>
with Arya Gaduh <br>

<script>
function toggleAbstract(id) {
    var x = document.getElementById(id);
    if (x.style.display === "block") {
        x.style.display = "none";
    } else {
        x.style.display = "block";
    }
}
</script>
