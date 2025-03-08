# ComfyUI GUI Research by NAI-00 [uriel Deveaud]
A collection of ideas and research about ComfyUI Open Source Software, mainly oriented towards GUI and basic features

> **Work in Progress** [Last Updated: 08-03-2025]()

<img src="https://img.shields.io/badge/Comfy-UI-red" /> <img src="https://img.shields.io/badge/User-Interface-purple" /> <img src="https://img.shields.io/badge/Gsoc-2025-blue" /> 

## :radio_button: Introduction

This current documentation is intended to present various concepts and research papers about **ComfyUI**[^1], an open source software, node based editor and automation pipeline builder.

Here, i want to present specific [topics](#):
- **Node Concepts**, how a generic node would behave into the gui
- **Media Productivity**, including audio and Video editing, Animations, VFX Post-production...
- **Custom nodes Structure**, including control panels and columns
- **Javascript Extensions**, including themes, controls and previews

## :radio_button: Preliminary observations

Using pipelines for automation allows building complex workflows, using source, processing and output nodes. Nodes can be categorized into several types, simple nodes which only offer one type of data and complex nodes which manage several types of data (example: images and text). In most cases it is possible to group nodes together to build a single, ready-to-use node. But it is not possible at the time of this document to edit the content of grouped nodes. This is therefore one of the strong points of this research. see [here](grouped_nodes.md)

[^1]: **ComfyUI** is the free and open source software
