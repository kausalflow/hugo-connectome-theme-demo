---
title: "Connectome Tutorials"
summary: "This is a set of tutorials on how to use the connectome Hugo theme."
images:
  - "/projects/undraw_video_influencer_-9-oyy.svg"
categories:
  - Tutorials
tags:
  - Introduction
  - Tutorials
members: # the makers of the tool
  - name: KausalFlow
    link: https://kausalflow.com
    description:
coordinators:
  - name: KausalFlow
    link: https://kausalflow.com
    description:
date: 2021-04-27T13:22:46+02:00
status: Done
sections:
  - tutorials
---

This is a set of tutorials on how to use the connectome Hugo theme.

{{< message class="link" title="I have been using this theme myself" >}}

[My public notes on data science](https://datumorphism.leima.is/) is built on top of this theme.

{{< /message >}}


The connectome Hugo theme is focusing on connecting notes with backlinks. Suppose a note A is linking to note B, note B should know that note A is linking to itself. In this setup, we immediately realize that we probably want to read about note A when viewing note B.


{{< figure src="../assets/tutorials/backlink-notes.jpg" >}}


The following is an example of such backlinks in this note {{< c "tutorials/embed-articles.md" >}}

{{< figure src="../assets/tutorials/backlink-box.png" >}}


What is more, the connectome Hugo theme also provides a {{< c "graph" "graph view of all the notes" >}}.

{{< figure src="../assets/tutorials/graph-of-notes.jpg" >}}

This website itself is a real-world example of this concept.

{{< figure src="/tutorials/assets/graph-of-connected-articles/graph.png" >}}

In this tutorial, we will demonstrate how to achieve this using the connectome Hugo theme.