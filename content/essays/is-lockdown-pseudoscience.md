---
date: 2021-02-15T06:00:00Z
topics: ["COVID-19"]
title: "Is lockdown a pseudoscience?"
summary: The lockdown is causing death, mental crisis, and decades of financial chaos. To be worthwhile, infection rates should at least rise and fall when lockdowns are lifted and applied. They don't.
tags: ["lockdown"]
draft: false
---

{{< image src="/essays/images/astrology.png" caption="">}}

Science is brutally simple. Either a hypothesis explains the past and predicts the future, or it doesn't. If it does, we tentatively accept it. If it doesn't, we abandon it. If we don't abandon it, we call the result _pseudoscience_. Like astrology, or water divining. 

The lockdown hypothesis supposes that mandatory business closures and compulsory stay-at-home orders ("lockdowns") provide more control over the rate of spread of infection than can be obtained by people voluntarily altering their behaviour in response to common sense and straightforward guidance. If that is true, then at least three predictions must be observable: 

1. When no measures are applied, the rate of infection should not fall;
2. If measures are applied, the rate of infection should fall;
3. If measures are lifted, the rate of infection should rise.

Since, by the Government's own estimates, lockdowns kill hundreds of thousands of people,[^whatmighthavebeen] if lockdowns didn't do these things, we wouldn't tolerate them. And the benefit would have to be so obvious that it hit you between the eyes.

Science tests its predictions with experiments. To test these predictions, we might: take a population of 66 million people; introduce a novel lethal virus; apply and lift restrictions regularly; and look for evidence of a relationship between the date of changing restrictions and the rate of fatal infections. 

As it happens, we've done precisely that. So what were the results?

## Gathering the evidence 

But first, why fatal infections, and not "cases"? Because of the most basic ethical standards, as summed up in the Hippocratic oath:[^oath] we can't damage people who would not be affected by the disease in the name of people who might be affected by the disease with interventions that we aren't certain work. 

The "D" in "COVID-19" stands for "disease" --- the manifestation of significant symptoms arising from infection. "Cases" are not "disease". SAR-CoV-2 and its mutations cause no or mild symptoms in the vast majority.  It causes long term health issues in a relatively small number, but lockdown causes the deaths of hundreds of thousands of people. So we need to look at fatal infections when looking for evidence of effectiveness, at least in the first instance.

The Office for National Statistics doesn't publish data for the date on which people acquire fatal infections. They only publish it for the day their death is registered. But because we know the median elapsed time between exposure to infection and dying from infection is around 23 days,[^williams2020] and the median elapsed time between occurrance of death and registration of death in ONS statistics is around 4 days,[^ONSdeaths] we can work it out quite easily. The number of fatal infections is simply the number deaths, shifted backward 4 weeks.

## Seeing the evidence

To get our eye in before we look at whether lockdown events influenced the rate of fatal infection, it helps to understand some simple maths.

Infectious disease is potentially dangerous because it's an exponential phenomenon. The daily increase or decrease in infections is proportional to the number already infected. Like bank interest rate, very small changes in infection rate give rise to very large changes over time in the number infected.  The problem is, since the changes are relatively small and the time period is relatively short, it's very hard to see from a graph of daily infection numbers whether the infection rate is changing. Is the curvy graph more curvy, or less curvy? That's hard for our eyes to detect.

But there is a simple maths technique for making these tiny changes visible to our eyes. Because the dynamics are governed by power laws, when we take the log of the daily infection rate, tangent ('slope') in the resulting graph corresponds to the rate of infection at that moment.[^Hobbie2015] And our eye is very much better at seeing 'slope' than 'curviness'. When infection is rising, the slope points upward. If the rate of infection increases, the slope increases. If the infection growth rate is zero, the slope is level. If infection is falling, the slope points downward. If the rate of infection falls further, the slope steepens downward.

A sketch will make this more obvious. Figure 1 illustrates what the lockdown hypothesis predicts should happen to hypothetical death rates when restrictions are not applied, or applied and lifted, both as a normal curve of daily deaths, and the log-transform of those deaths. See how the slope is easier to see in the log-transformed (red) version? It's like an X-Ray machine for our data.

{{< image src="/essays/images/lockdown-example.png" caption="Figure 1. Illustrating the theoretical impact of lockdown events on infection rates. Small changes are much easier to see when the data is transformed into their log value.">}}

## So. Do they work?

{{< image src="/essays/images/fig1.png" caption="Figure 2. Daily and cumulative fatal infection rates. Source: Office for National Statistics. Deaths registered weekly in England and Wales, provisional (2021)">}}

Figure 2 shows the standard (blue) and log-transformed (red) graphs of daily fatal infections, from the start of the epidemic in February 2020 to the annual rise in seasonal illness that happens at the start of every Autumn. The first recorded death in the ONS data is 9th March, giving the first estimated date of fatal infection on 11th February.

{{< image src="/essays/images/fig2.png" caption="Figure 3. Daily and cumulative fatal infection rates from the 17th February 2020 to the start of the first lockdown on 23rd March. The rate of infection growth fell continuously and, by the start of lockdown, had fallen to zero.">}}

Prediction 1 says: _"When no controls are applied, the rate of infection should not fall"_. Remember---this means that a log-transformed plot of daily  fatal infection before lockdown is imposed should be a straight line. It's not. Figure 3 shows the fatal infection rate from the start of the epidemic until the first lockdown on 23 March. By the beginning of March, the slope of log-transformed infection rate was falling . By the night of Mr Johnstone's "stay at home" TV broadcast, it was almost horizontal. Without any mandatory controls in place, the infection growth rate had fallen to zero. This should not surprise you: after you heard about pangolins, did you wait until Mr Johnson told you to before washing your hands more often and taking more care around other people? No. Neither did 66 million other people.

{{< image src="/essays/images/fig3.png" caption="Figure 4. The infection rate didn't rise on any of the three occasions when restrictions were eased, and rose when mandatory use of masks was imposed.">}}

Prediction 2 says: *"If controls are applied, the rate of infection should fall"*.  Figure 4 shows the period from imposition of controls on 23rd March until the annual rise in seasonal respiratory infection that begins every year at the start of autumn. A 4 month fall in infections at a constant rate was preceded by the imposition of controls. But *that* was preceded by the rapid fall in the growth rate from a high value to zero before the start of lockdown #1 without any controls. Such coincidences are the engine of the tabloid horoscope. 

At the end of the summer, the Government introduced mandatory mask wearing. Because of the sensitivity of log-transformed data, it is possible to see changes in the rate of infection growth around that time. However, by that time, fatal infections had fallen to fewer than 100 per day, excess mortality had fallen below the 5 year average, and the UK was experiencing the highest heatwave excess mortality since 2003. ONS notes: _"Further work is required to explore how the concurrent risk of COVID-19 and heatwaves may have intersected to amplify these impacts"_.[^onsheatwave] 

Prediction 3 says: _"If controls are lifted, the rate of infection should rise"_. Here, the perception of a Government clown show driving a bus with a disconnected steering wheel is starkest. On three occasions (Figure 4 again), it lifted controls: the partial lifting of lockdown #1 on May 10th; reopening of retail around June 15th; and reopening the country on July 4th. In theory, the infection rate should have risen sharply on each occasion. It didn't on any occasion. The virus cleared the population in the way viruses have done for millions of years--at its own pace.

## Yes, but...[insert objection here]

Any lockdown enthusiast who views the predictive failure of their hypothesis and says: "Well, if you stand on one leg, shut one eye, and hold the graph up to a full moon, you can see a change on this date" is missing the point. To justify a policy that kills hundreds of thousands of people, the effect should be so clear that it leaps off the page. It is not.

It is at this moment of recognition that the difference between science and pseudoscience emerges. Science proceeds by deliberately trying to find evidence that falsifies a core proposition. When falsifying evidence is discovered, we alter the core proposition, or abandon it. It is the resistance of a hypothesis to deliberate attempts to break it, not protection of it from those attempts, that is the foundation of our confidence in predictions.

In pseudoscience, the goal isn't discovery of novel truths about the world, but rather the desire to hold certain beliefs about it. It avoids evidence that falsifies its core propositions and, when it encounters it, it invents an excuse that explains the failure under that circumstance. Science expands by saying more and more interesting things about the world. Pseudoscience expands by giving more and more excuses for its lack of explanatory power.

## Is lockdown a pseudoscience?

Did any benefits of lockdown "hit you between the eyes"? Were any of its propositions visible in the data? No. Yet lockdowns are bitterly defended with a pseudoscientific worldview exemplified by the moral rectitude of believers such as George Monbiot --- a journalist who has never missed a pay check while dispensing from his comfortable metropolitan London home withering prescriptions about the need to ban scepticism.[^monbiot2021] They have no familiarity with the scientific method. Hungarian philosopher Imre Lakatos summed up the limitations of their world view thus:[^Lakatos1973] 

{{< blockquote >}}
Many philosophers have tried to solve the problem of demarcation in the following terms: a statement constitutes knowledge if sufficiently many people believe it sufficiently strongly. But the history of thought shows us that many people were totally committed to absurd beliefs. If the strengths of beliefs were a hallmark of knowledge, we should have to rank some tales about demons, angels, devils, and of heaven and hell as knowledge. Scientists, on the other hand, are very sceptical even of their best theories. Newton’s is the most powerful theory science has yet produced, but Newton himself never believed that bodies attract each other at a distance. So no degree of commitment to beliefs makes them knowledge. Indeed, the hallmark of scientific behaviour is a certain scepticism even towards one’s most cherished theories. Blind commitment to a theory is not an intellectual virtue: it is an intellectual crime.
{{< /blockquote >}}

An intellectual crime. And perhaps a material one.

## Postscript 

Infection rate in epidemics follow a well understood curve, described mathematically by a function called a _Gompertz_ function. The great majority of outbreaks, including the UK, followed it and have been analysed in Rypdal (2020).[^rypdal] 

{{< image src="/essays/images/gompertz.png" caption="Figure 5. Fatal infection can be modelled by a Gompertz function. Arguably, some fatal infections were displaced by lockdown from March/April to May/June/July.">}}

There is an argument, and it is one that I accept, that the peak rate of fatal infection can be influenced by the effectiveness of changes in public behaviours that affect the transmissibility of the disease. To the extent that these prevented saturating hospital capacity, this would lower cumulative death rate. However, Bendavid, E. et al. (2021)[^bhattacharya2020] show that  enforcement offers no advantage over voluntary behaviour changes in the death rates experienced by countries implementing different severities of lockdown. Equally, while such considerations might alter the timing over a short period of the dates of deaths, there is no evidence (beside a consideration of avoiding saturating hospitals) that they alter the total number, as visible in Figure 5.





[^Hine2009]: Hine, D. (2009). The 2009 Influenza Pandemic: An independent review of the UK response to the 2009 influenza pandemic. [link](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/61252/the2009influenzapandemic-review.pdf)

[^whatmighthavebeen]: Lyon, R. (2021, 4 February) What might have been. [link]({{< ref "/essays/uk-rejected-lockdown.md" >}})

[^oath]: Hippocratic oath: _"I will abstain from all intentional wrong-doing and harm"_. See, for example: Wikepedia [link](https://en.wikipedia.org/wiki/Hippocratic_Oath)

[^rypdal]: Rypdal, K. and Rypdal, M. (2020) ‘A parsimonious description and cross-country analysis of covid-19 epidemic curves’, International Journal of Environmental Research and Public Health, 17(18), pp. 1–23. doi: 10.3390/ijerph17186487.

[^williams2020]: Williams, S. et al. (2020) ‘An Improved Measure of Deaths Due to Covid-19 in England and Wales’, SSRN Electronic Journal. doi: 10.2139/ssrn.3635548. [link](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3635548)

[^ONSdeaths]: Office for National Statistics (2020). Deaths involving COVID-19, England and Wales: deaths occurring in June 2020. [link](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/bulletins/deathsinvolvingcovid19englandandwales/deathsoccurringinjune2020#time-taken-for-the-deaths-in-march-to-june-to-be-registered)

[^Hobbie2015]: For an accessible introduction to exponential growth, see for example section 2.1 in Hobbie, R., & Roth, B. (2015). Intermediate Physics for Medicine and Biology (5th ed.). Springer

[^onsheatwave]: Office for National Statistics (2020). Heatwave mortality monitoring report: 2020. [link](https://www.gov.uk/government/publications/phe-heatwave-mortality-monitoring/heatwave-mortality-monitoring-report-2020)

[^monbiot2021]: Monbiot, G. (2021, January 27). Covid lies cost lives – we have a duty to clamp down on them. The Guardian. [link](https://www.theguardian.com/commentisfree/2021/jan/27/covid-lies-cost-lives-right-clamp-down-misinformation)

[^Lakatos1973]: Lakatos, I. (1980). The Methodology of Scientific Research Programmes: Volume 1. Cambridge University Press. For a fascinating lecture by Lakatos on the difference between science and pseudoscience, listen to his BBC Radio Talk here: [link](https://www.lse.ac.uk/philosophy/science-and-pseudoscience-overview-and-transcript/)

[^bhattacharya2020]: Bendavid, E. et al. (2021) ‘Assessing Mandatory Stay‐at‐Home and Business Closure Effects on the Spread of COVID‐19’, European Journal of Clinical Investigation, pp. 0–3. doi: 10.1111/eci.13484.