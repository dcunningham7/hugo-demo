---
title: "Celestial Spec Site"
date: 2026-05-08T10:00:00-05:00
headline: "Working Spec Site for <br> Celestial Working Group."
tagline: "An unofficial demo for the purpose of practicing web development in Hugo."
hide_page_title: true
breadcrumb_title: "Demonstration Purposes Only"
hide_breadcrumb: false
hide_sidebar: false
#show_featured_story: false
show_featured_footer: false
#layout: "single"
#links: [[href: "/projects/", text: "Projects"],[href: "/org/workinggroups/", text: "Working Group"],[href: "/membership/", text: "Members"],[href: "/org/value", text: "Business Value"]]
#container: "container-fluid"
---


## What we do

Celestial Spec is a fictional working group. We publish a short spec and
run a pretend launch event. This site is an unofficial personal demo. It is
not affiliated with the Eclipse Foundation.

The page is built from the Eclipse Hugo boilerplate: copy in markdown, files
in `static/`, and theme shortcodes (YouTube, event agenda).

## Documents

- [Tickets (PDF)](tickets.pdf)
- [Event information (PDF)](catsun.pdf)

## Launch event

A fake agenda for the launch, from `data/en/default/agenda.yaml` and the
theme agenda shortcode:

{{< events/agenda >}}

## Shortcode 

The theme YouTube **shortcode**, including an overview of Celestial's latest event!:

{{< youtube "dg4dmNvxdu0" >}}

###### Note: This cat is not affiliated with Celestial (a fake company) or Eclipse Foundation (a real company).