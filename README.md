# Welcome to Souffleur
## A cross platform remote control for presentations

This repo contains tools to help speakers and trainers during presentations. The underlying idea is to show slide-based notes on a smartphone or tablet. This device also acts as a remote control, as it can send commands to the presenting computer to show the next or previous slide. The Souffleur server receives these commands and sends corresponding key strokes. It also serves the slides notes. They are passed to the server in a json file. So, Souffleur does not depend on a particular presentation software. Still, my tool PPTNotesExtractor can read notes in PowerPoint slides and save them in the json format.

So far the following components are available:

**tools\PPTNotesExtractor**: a tool to extract PowerPoint presentation notes

**server**: The Souffleur server