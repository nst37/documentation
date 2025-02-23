---
title: Upgrade a Drupal Site to the Latest Version of Drupal
subtitle: Introduction
description:
tags: [code, launch, migrate, site, updates]
contributors: [wordsmither]
layout: guide
permalink: docs/guides/drupal-hosted
anchorid: drupal-hosted
editpath: drupal/drupal-hosted/01-introduction.md
reviewed: "2022-12-12"
contenttype: [guide]
innav: [true]
categories: [overview, migrate]
cms: [drupal8, drupal9, drupal10]
audience: [development]
product: [--]
integration: [--]
---

This guide will show you how to migrate a site that meets the following criteria to the latest version of Drupal:

| <i class="fa fa-cloud"></i><br/> Current Host | <i class="fa fa-wrench"></i><br/> How Site Was Created <Popover title="Site Creation" content="What is the method you used to create the site?" /> | <i class="fa fa-exclamation-circle"></i><br/> Additional Requirements <Popover title="Additional Requirements" content="Any other features that must be in place, or that are desired." /> |
|:---------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|                   Pantheon                    |                                                                     Dashboard                                                                      |                                                                                             --                                                                                             |

<Alert title="Note" type="info" >

This guide is intended for those who do not have access to Multidev.  If you do have access, use [Upgrade a Drupal Site with Multidev to the latest version of Drupal Using Multidev](/guides/drupal-hosted) instead.

</Alert>

<Partial file="drupal/see-landing.md" />

<Partial file="drupal/commit-history.md" />

This doc uses the following aliases:

- **Alias:** `D8_SITE`
  - **Site Name:** `best-drupal8-site-ever`
- **Alias:** `DRUPAL_SITE`
  - **Site Name:** `best-drupal-site-ever`

## Requirements

<Partial file="drupal/upgrade-site-requirements-new.md" />
