---
title: "FireworksWeb Introduction"
teaching: 60
exercises: 30
# questions:

objectives:

# keypoints:

---

The Fireworks team has created a web-based fireworks application. Fireworks is a longstanding CMS event display tool that interacts with [MiniAOD](https://twiki.cern.ch/twiki/bin/view/CMS/MiniAOD){: target="_blank"} files and allows the user to significantly customize the event display. The following 5 "explorations" can be done offline by anyone referencing this short exercise TWiki.

## Introduction

Fireworks often requires (somewhat) cumbersome installation or heavy network usage over X11 forwarding, which creates some hurdle in quickly analyzing the events of interest. The FireworksWeb allows users to circumvent all of the installation and simply use web to directly open up a file such as `/store/.../some/miniaod.root` and directly start analyzing the event.

Please take a look at the CMS Offline and Computing week [presentation](https://indico.cern.ch/event/1087821/) from Alja for overview of the project.

## Opening FireworksWeb

There are two instances of the website running currently.

- [http://fireworks.cern.ch](http://fireworks.cern.ch/){: target="_blank"}
- [https://fireworks-open.cern.ch/cms/](https://fireworks-open.cern.ch/cms/){: target="_blank"}

The main features are the same. The first is the more general use case and accesses files stored on the CERN [EOS](https://twiki.cern.ch/twiki/bin/view/CMS/EOS){: target="_blank"} space. The latter can access files from the CERN Open Data Portal.

> ## Try Me!
>  Visit the [https://fireworks-open.cern.ch/cms/](https://fireworks-open.cern.ch/cms/) webpage, and click "View Fireworks" for one of the example samples. You will see some messages on the next screen as Fireworks loads the file, and then an event viewer will appear. Click and drag on the main image to manipulate it, and explore the various buttons and fields that you can see in the viewer.
{: .challenge }