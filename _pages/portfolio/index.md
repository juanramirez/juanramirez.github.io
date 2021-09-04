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
<img src="/assets/images/projects/neurolink/logo.png" alt="NeuroLink" width="200"/>

**NeuroLink** is a project conceived at first as a personal rehab exercise after suffering a [brain tumor removal surgery](/abi/how-it-all-started/) in March 2020, and consequently _brain injury_ (also called [ABI](https://en.wikipedia.org/wiki/Acquired_brain_injury)); but also intended to help other people who can suffer this kind of experiences like me, now or in the future.

**NeuroLink** aims to fill the big gap which seems to exist between medical release and rehabilitation by connecting all these kinds of people:
* People who experience these kind of damage at first-hand (we will call them **patients** from now on).
* People who care for them (**carers**), usually (but not always) their relatives. They also suffer from the patient's ABI, but _just in a different way_.
* Neurology or neurological rehabilitation professionals, from doctors to practitioners (**professionals** from now on):

**NeuroLink** aims to be a _social network_ for all these people directly or indirectly affected by [ABI](https://en.wikipedia.org/wiki/Acquired_brain_injury) (or [neurological disorders](https://en.wikipedia.org/wiki/Neurological_disorder) in general).

### Tech stack and code organization

**Neurolink** is being built using a [client-server architecture](https://en.wikipedia.org/wiki/Client%E2%80%93server_model).

#### Neurolink-server
Neurolink-server is being built using Javascript, on top of [ExpressJS](https://expressjs.com). Check out the [GitHub repo](https://github.com/Inspiring-White/neurolink-server) for more details.
#### Neurolink-client
Still to be done. Ideally, I plan it to have both desktop and mobile web clients. This would allow using it as a standalone webpage or modelling webviews for mobile applications, for example.

# On-duty-organizer

<img src="/assets/images/projects/doctorplan/logo.png" alt="DoctorPlan" width="200"/>

**On-duty organizer** (a.k.a. "**DoctorPlan**") is an open-source on-duty schedule organizer for hospital services made using NodeJS. I started it in 2017, when I saw that on-duty days organization consumed my wife (and also the rest of the doctors of the paediatric service in the hospital) a lot of time, energy and discussions. I thought that this problem was ideal to be solved using [evolutionary algorithms](https://en.wikipedia.org/wiki/Evolutionary_algorithm), which had strongly called my attention when I studied them in the career. Hence, *DoctorPlan* takes into account doctor preferences, mandatory medical consultations and similar factors to organize on-duty days assignation for a hospital service using evolutionary algorithms, and generates the best solution it can.

Theoretically, a similar approach could be used to organize on-duty days in any kind of professional service which require someone to be always on-duty.

For the moment, it's **only a command-line application**, but in the future I expect to have some time to build a client-server web application around it, both for desktop and mobile devices if possible.

Check out the [GitHub repo page](https://github.com/juanramirez/on-duty). Please take into account that documentation is also _in progress_.

# HillPace
<img src="/assets/images/projects/hillpace/logo.png" alt="HillPace" width="200"/>

**HillPace** is an open-source running race planner for non-flat races made using Ruby. I started it before running the [2015 Granada Half Marathon](https://www.strava.com/activities/301597005), because I had acceptable times in more or less flat half-marathons, but I didn't know how to plan a half marathon with those up and down segments.

It's intended to take a GPX or TCX file from a route and a _reference pace_ (which would be the pace you are comfortable running to in a flat course of the same distance). Taking those data into account, HillPace can estimate planned paces by segments, based on configurable external factors like the climb grade of each segment.

The same as [DoctorPlan](#On-duty-organizer), for the moment HillPace is **only a command-line application**. In the future, I'd like to integrate it into a web application, where one could enter those inputs, generate a plan for the race and export it to a running smartwatch.

**HillPace** is a Ruby gem [available in Rubygems.org](https://rubygems.org/gems/hillpace).

Check out the installation guide, the user guide and the examples of use [on the GitHub repo page](https://github.com/juanramirez/hillpace).


