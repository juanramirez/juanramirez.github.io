---
title: Development Portfolio
layout: collection
permalink: /portfolio/
collection: portfolio
entries_layout: grid
classes: wide
---

Most of my projects have been developed for [the companies I've worked or I work for](https://www.linkedin.com/in/juanramirez/). However, I have several _side projects_ to which I also dedicate some effort sometimes. In inverse chronological order, they are:

# NeuroLink
<img src="/assets/images/projects/neurolink.png" alt="NeuroLink" width="200"/>

**NeuroLink** is a project conceived at first as a personal rehab exercise after suffering a [brain tumor removal surgery](/abi/about-me/how-it-all-started/) in March 2020, and consequently _brain injury_ (also called [ABI](https://en.wikipedia.org/wiki/Acquired_brain_injury)); but also intended to help other people who can suffer this kind of experiences now or in the future.

**NeuroLink** aims to fill the big gap which I realized that existed between hospitalization and rehabilitation by connecting all these kinds of people:
* People who experienced these kind of damage at first-hand (we will call them **patients** from now on).
* People who care for them (**carers**), usually (but not always) their relatives. They also suffer from the patient's ABI, just in a different way.
* Neurology or neurological rehabilitation professionals, from doctors to practitioners (**professionals** from now on):

**NeuroLink** aims to be a _social network_ for all these people directly or indirectly affected by [ABI](https://en.wikipedia.org/wiki/Acquired_brain_injury) (or [neurological disorders](https://en.wikipedia.org/wiki/Neurological_disorder) in general).

### Tech stack and code organization

**Neurolink** aims to be built using a [client-server architecture](https://en.wikipedia.org/wiki/Client%E2%80%93server_model).

#### Neurolink-server
Neurolink-server is being built using Javascript, on top of [ExpressJS](https://expressjs.com). Check out the [GitHub repo](https://github.com/Inspiring-White/neurolink-server) for more details.
#### Neurolink-client
To be done. Ideally, I plan it to have both desktop and mobile web clients. This would allow using it as a webpage or modelling webviews for a mobile application, for example.

# On-duty organizer

<img src="/assets/images/projects/doctorplan.png" alt="On-duty organizer" width="200"/>

**On-duty organizer** (a.k.a. "DoctorPlan") is an open-source on-duty schedule organizer for hospital services made using Node JS. It takes into account doctor preferences, mandatory medical consultations and other factors to organize on-duty days for a hospital service using [evolutionary algorithms](https://en.wikipedia.org/wiki/Evolutionary_algorithm).

For the moment it is **only a command-line application**, but in the future I expect to have some time to build a web application around it, both for desktop and mobile devices.

Check out the [GitHub repo page](https://github.com/juanramirez/on-duty). Please take into account that documentation is also _in progress_.

# HillPace
<img src="/assets/images/projects/hillpace.png" alt="HillPace" width="200"/>

**HillPace** is an open-source running race planner for non-flat races made using Ruby. It's intended to take a GPX or TCX file from a route and a reference pace (the _reference pace_ would be the pace you are comfortable running to in a flat course of the same distance). Taking those data into account, HillPace can estimate planned paces by segments, based on configurable external factors like the climb grade of each segment.

The same as [On-duty organizer](#On-duty organizer), for the moment HillPace it's **only a command-line application**. In the future, I'd like to integrate it into a web application, where one could enter those inputs, generate a plan for the race and export it to a running smartwatch.

**HillPace** is a Ruby gem [available in Rubygems.org](https://rubygems.org/gems/hillpace).

Check out the installation guide, the user guide and the examples of use [on the GitHub repo page](https://github.com/juanramirez/hillpace).


