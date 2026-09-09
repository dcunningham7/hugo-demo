---
title: "Prep"
date: 2026-05-08T10:00:00-05:00
headline: "Hugo Demo Changelog"
tagline: ""
hide_page_title: true
breadcrumb_title: "Changelog"
hide_sidebar: false
#show_featured_story: false
show_featured_footer: false
#layout: "single"
#links: [[href: "/projects/", text: "Projects"],[href: "/org/workinggroups/", text: "Working Group"],[href: "/membership/", text: "Members"],[href: "/org/value", text: "Business Value"]]
#container: "container-fluid"
---

## Changelog

This page is unofficial personal notes. It is not affiliated with the Eclipse Foundation.

This demo is created to be ticket-shaped for the purposes of learning Hugo - content updates, PDFs, and small UI fixes on the Eclipse Fdn boilerplate site. It is not a new theme or a redesign.

Live demo: [hugo-demo-dylancunningham.netlify.app](https://hugo-demo-dylancunningham.netlify.app/)

## 2026-09-09

### Added
- Homepage copy in markdown for a pretend company
- PDFs in `static/`, linked from the homepage: `tickets.pdf`, `catsun.pdf`
- Event agenda: `data/en/default/agenda.yaml` and the theme `events/agenda` shortcode
- `YouTube` shortcode on the homepage to show a cute video of a cat
- Small style change to header `layouts/partials/head_custom.html` while keeping theme 

### Changed
- Replaced Eclipse boilerplate copy and site title/description/`baseURL` for the Netlify host
- Disabled featured footer with `show_featured_footer: false`
- Removed the boilerplate Google Tag Manager id from config

### Fixed
- Agenda `type` values match `types` ids; used `time` (not a `times` string) for single slots
