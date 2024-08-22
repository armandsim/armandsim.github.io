<!-- CSS styles -->

<style>
/* Common styles */
.abstract-button {
    cursor: pointer;
    padding: 5px 15px;
    border: 1px solid #000000 !important; /* Black border added and forced */
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
    display: none; /* Hide abstract content by default */
}

/* Force light mode styles */
body .abstract-button,
body .abstract-content,
body .publication {
    color: #000000 !important;
}
body .abstract-button {
    border-color: #000000 !important;
}
body .abstract-content {
    background-color: transparent !important;
}

/* Additional force for light mode */
html:not([data-theme='dark']) .abstract-button,
html:not([data-theme='dark']) .abstract-content,
html:not([data-theme='dark']) .publication {
    color: #000000 !important;
}
html:not([data-theme='dark']) .abstract-button {
    border-color: #000000 !important;
}

/* Styles for dark mode */
@media (prefers-color-scheme: dark) {
    body .publication,
    body .abstract-content,
    body .abstract-button {
        color: #ffffff !important;
    }
    body .abstract-button {
        border-color: #ffffff !important;
    }
    body .abstract-content {
        background-color: transparent !important;
    }
}

/* Highest specificity rule to ensure black border in light mode */
html:not([data-theme='dark']) body .abstract-button {
    border: 1px solid #000000 !important;
}

/* New style for paper spacing */
.paper-spacing {
    margin-bottom: 20px;
    transition: margin-bottom 0.3s ease;
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

// Modified function to toggle abstract visibility and adjust spacing
function toggleAbstract(id) {
    var content = document.getElementById(id);
    var paperSpacing = content.closest('.paper-spacing');
    if (content.style.display === "none" || content.style.display === "") {
        content.style.display = "block";
        paperSpacing.style.marginBottom = "40px";
    } else {
        content.style.display = "none";
        paperSpacing.style.marginBottom = "20px";
    }
}

// Call hideAllAbstracts when the page loads
document.addEventListener('DOMContentLoaded', hideAllAbstracts);
</script>


## publication

<div class="paper-spacing">
**[Selection and Behavioral Responses of Health Insurance Subsidies in the Long Run: Evidence from a Field Experiment in Ghana](/docs/AKS_Ghana_Published_Version_HE.pdf)** <br>
with Patrick Asuming and Hyuncheol Bryant Kim <br>
*Health Economics, 2024, 33(5): 992–1032.* <br>

<button class="abstract-button" onclick="toggleAbstract('abstract1')">Abstract</button>
<div id="abstract1" class="abstract abstract-content">
We study the effects of a health insurance subsidy in Ghana, where mandates are not enforceable. We randomly provide different levels of subsidy (1/3, 2/3, and full) and evaluate the impact at seven months and three years after the intervention. We find that a one-time subsidy increased insurance enrollment for all groups in both the short and long runs, but health care utilization in the long run increased only for the partial subsidy group. We find supportive evidence that ex-post behavioral responses rather than ex-ante selective enrollment explain the long-run health care utilization results.
</div> 
</div>
 {: style="text-align: justify"}
 
<div class="paper-spacing">
**[Addressing Vaccine Hesitancy using Local Ambassadors: A Randomized Controlled Trial in Indonesia](/docs/Vaccine_EER.pdf)** <br>
with Asad Islam, Gita Kusnadi, Jahen Rezki, Giovanni van Empel, Michael Vlassopoulos, and Yves Zenou <br>
*European Economic Review, 2024, 163, 104683* <br>

<button class="abstract-button" onclick="toggleAbstract('abstract2')">Abstract</button>
<div id="abstract2" class="abstract abstract-content">
In settings where resistance and rampant misinformation against vaccines exist, the prospect of containing infectious diseases remains a challenge. Can delivery of information regarding the benefits of vaccination through personal home visits by local ambassadors increase vaccine uptake? We conduct a door-to-door randomized information campaign targeted towards COVID-19 unvaccinated individuals in rural Indonesia. We recruited ambassadors from local villages tasked to deliver information about COVID-19 vaccines and promote vaccination through one-on-one meetings, using an interpersonal behavioral change communication approach. To investigate which type of ambassador—health cadres, influential individuals, and laypersons—is the most effective, we randomly vary the type of ambassador that delivers the information at the village level. We find that the overall vaccination take-up is quite moderate and that there are no differences in vaccination outcomes across the treatment groups. These results highlight the challenge of boosting vaccine uptake in late stages of a pandemic.
</div>
</div>
 {: style="text-align: justify"}
 
<div class="paper-spacing">
**[The Consequences of Child Market Work on the Growth of Human Capital](https://www.sciencedirect.com/science/article/pii/S0305750X15308731?via%3Dihub)** <br> 
with Asep Suryahadi and Daniel Suryadarma <br>
*World Development, 2017, 91: 144–155.* <br>

<button class="abstract-button" onclick="toggleAbstract('abstract3')">Abstract</button>
<div id="abstract3" class="abstract abstract-content">
The paper measures the effect of child market work on the long-term growth of human capital, focusing on the output of the human capital production: mathematics skills, cognitive skills, pulmonary function, and educational attainment. Our full sample is drawn from a rich longitudinal dataset Indonesia Family Life Survey (IFLS). We address endogeneity of child market work using provincial legislated minimum wage as the instrument. Our instrumental variable estimation shows that child labor negatively affects mathematics skills and pulmonary function, but not cognitive skills and educational attainment. We find heterogeneities in type of work. Those who work outside of family business have lower educational attainment than those working for family business.
</div>
</div>
 {: style="text-align: justify"}
 
 <br>

## working papers 

<div class="paper-spacing">
**[Sink or Swim: Testing the Role of Science vs Religion in Raising Environmental Awareness in Indonesia](/docs/jakarta_draft.pdf)** <br>
with Sarah Gultom, Umair Khalil, Wang Lee, Alyas Widita <br>

<button class="abstract-button" onclick="toggleAbstract('abstract4')">Abstract</button>
<div id="abstract4" class="abstract abstract-content">
Promoting awareness and encouraging pro-sustainability behaviors to mitigate climate and environmental issues can be challenging due to their polarizing nature. We conduct a large-scale online experiment in Jakarta, the world's fastest sinking city, to examine the impact of messenger identity and narrative style on awareness and behavior regarding land subsidence, a human-induced climate change phenomenon. We vary the messenger identity (an actor portraying either a religious leader or a scientist) and the narrative style of the message (religious vs. scientific). Our results show that exposure to an environmental video message, as opposed to a placebo, increases beliefs, trust in institutions, and pro-sustainability behaviors. The largest impacts arise when a scientist delivers a message embedded with a religious narrative, increasing participants' perceptions of the messenger as persuasive and trustworthy. The effects are more pronounced among individuals with low prior knowledge, high trust in authorities, and those less reliant on groundwater. However, we find limited evidence of heterogeneous treatment effects on actions. Our findings highlight the importance of carefully considering both the message and the messenger in communication strategies in a diverse population.
</div>
</div>
 {: style="text-align: justify"}
 
<div class="paper-spacing">
 **Import Restriction, Price Shock, and Local Policy Responses: Evidence from Indonesia** <br>
</div>
 
<div class="paper-spacing">
**Reaching the Last Mile: Results from a Randomised Controlled Trial to Promote COVID-19 Vaccine in Bangladesh** <br>
with Dinesh A., Tarannum B., Ahmedul K., Meerjady F., Diwakar M., Debayan P., Patrick O., Piyush B., Shafiun S., Hyuncheol K., and Asad I. <br>
*Revise and resubmit, Nature: Communications Medicine* <br>
</div>

<div class="paper-spacing">
**Promoting COVID-19 Vaccination in India** <br>
with Asad Islam, Hyuncheol Bryant Kim, and Deb Prakashi <br>
*Submitted* 
</div>

<br>

## works in progress

<div class="paper-spacing">
**Anticipatory and Local Economic Impacts of Mineral Export Ban in Indonesia** <br>
with Hyuk Son <br>
</div>

<div class="paper-spacing">
**The Tyranny of Distance** <br>
with Arya Gaduh <br>
</div>

<div class="paper-spacing">
**Economic Crisis and Nation Building** <br>
with Arya Gaduh <br>
</div>
