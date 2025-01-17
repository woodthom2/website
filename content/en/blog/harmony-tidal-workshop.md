---
title: Harmony and TIDAL workshop
description: Collaborating with another team in the Wellcome Trust Data Prize
date: 2023-08-18
categories: ["harmony", "events"]
image: /images/harmony-tidal-workshop.jpg


aliases:
  - "/harmony-and-tidal-workshop/"
url: "/ai-in-mental-health/harmony-and-tidal-workshop/"
---


On Thursday, August 17th, 2023, the Harmony and [TIDAL](https://github.com/AmeliaES/TIDAL) teams teamed up to run a workshop at [University College London](https://www.ucl.ac.uk/) to allow researchers to try out their software tools. The workshop was attended by researchers interested in using these tools to study child and adolescent [mental health](/ai-in-mental-health/), and other areas in social science research, from the effects of gambling addiction to asking questions about nature vs nurture in twin studies.

[You can read more about the event on the Centre for Longitudinal Studies' website.](https://cls.ucl.ac.uk/events/mental-health-data-tools-workshop/)

{{< image src="/images/tidal.png" alt="TIDAL" title="TIDAL" >}}

{{< image src="/images/logo-dark-blue.png" alt="Harmony" title="Harmony" >}}

## Aim of the workshop

The aim of the workshop was to give participants hands-on experience with Harmony and TIDAL, and to demonstrate how they can be used to answer research questions about mental health, covering the following topics.

* How to use Harmony to harmonise questionnaires and create comparable measures of mental health symptoms.
* How to use TIDAL to explore trajectories of mental health [problems](/discover-data/emotional-problems-datasets-and-studies) over time.

The participants were given the opportunity to practice using Harmony and TIDAL on a simulated dataset. They also had the chance to ask questions and get help from the Harmony and TIDAL teams.

## Data used in the workshop

The data used in the workshop was synthetic data that had been simulated based on the following two UK [cohort studies](/item-harmonisation/harmony-a-free-ai-tool-for-cross-cohort-research/):

* Avon Longitudinal Study of Parents and Children (ALSPAC)
* 1970 British Cohort Study (BCS70)

The ALSPAC is a study of over 14,000 children who were born during the early 1990s from the Avon region in England. The BCS70 is a study of around 17,000 people born in England, Scotland, and Wales in a single week of 1970.

Both cohorts administered similar (but not identical) questionnaires to study mothers at various points as their children were growing up. In BCS70, the Rutter parent behaviour questionnaire was administered, whereas in ALSPAC, the Rutter scale was administered initially, but the Strengths and Difficulties Questionnaire (SDQ) was used from the age 7 assessment onwards. In both cohorts, there were ages where the administration of these questionnaires overlapped, particularly ages 5 and 10.

The synthetic data was created to mimic the real data from these two cohorts. It was created using a statistical method called bootstrapping. Bootstrapping involves repeatedly sampling data from the real data and then using the sampled data to create a new dataset. This process is repeated many times to create a large number of simulated datasets.

## Outcome of the workshop

After becoming familiar with both Harmony and TIDAL, participants were able to use both Harmony and TIDAL to harmonise the Rutter and SDQ items within ALSPAC, to create trajectories of total difficulties/problems. We collected participants' manually harmonised items and plan to compare these with Harmony's cosine scoring to understand how well Harmony performs compared to human experts.

## Conclusion

The workshop was a great success and participants learned a lot about how to use these powerful tools. We've also gathered a great deal of user testing experience on both these tools. If you are interested in using Harmony or TIDAL to study child and adolescent mental health, please visit [harmonydata.ac.uk](https://harmonydata.ac.uk) and [the TIDAL repo](https://github.com/AmeliaES/TIDAL) and [the TIDAL app](https://tidal.shinyapps.io/tidalapp/) for more information.

## About Harmony

Harmony is a software tool using [natural language processing](https://naturallanguageprocessing.com/) and [Transformer](https://harmonydata.ac.uk/how-does-harmony-work) [models](https://harmonydata.ac.uk/semantic-text-matching-with-deep-learning-transformer-models) (LLMs) that can be used to harmonise questionnaires and create comparable measures of mental health symptoms. It is a valuable tool for researchers who want to study mental health across different populations and settings.

Harmony uses natural language processing to identify and match items across questionnaires. This process is more accurate and efficient than traditional methods of harmonisation. Harmony also provides a number of features that make it easy to use, such as a user-friendly interface, responsive design, and [Python](https://www.python.org/) and [R](https://www.r-project.org/) bindings and REST [API](https://harmonydata.ac.uk/releasing-harmony-api).

If you are interested in learning more about Harmony, please check out some of our [videos](/videos) and [blog posts](/blog).

## About TIDAL

TIDAL stands for Tool to Implement Developmental Analyses of Longitudinal Data. TIDAL is designed to facilitate work trajectories and remove barriers to implementing [longitudinal research](/item-harmonisation/harmony-a-free-ai-tool-for-longitudinal-study/) to researchers without specialist statistical backgrounds, enabling them to address questions like:

* How [mental](/discover-data/mental-illness-datasets-and-studies) health is changing over specific periods of time.
* When mental health is improving or worsening at the fastest rate (points of acceleration).
* How variable mental health responses are over time within individuals (stability).
