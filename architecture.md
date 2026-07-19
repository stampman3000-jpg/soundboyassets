# Architecture

## Overview

Soundboy is structured as a collection of independent systems designed to
allow experimentation and iteration.

The aim is to keep the hardware layer, user interface and audio generation
separated so ideas can be tested quickly without rewriting the whole system.

---

## System Overview
![Soundboy architecture](assets/photos/Generated%20Image%20July%2018,%202026%20-%208_45AM.jpg)
---

## Core Systems

### Input Layer

Handles buttons, encoders and external MIDI input.

Responsibilities:
- Detect user actions
- Translate hardware events into commands
- Provide consistent input to the rest of the system

---

### Sequencer

The sequencer is responsible for:
- Pattern playback
- Timing
- Step triggering
- Parameter changes

---

### Audio Engine

The audio layer currently explores:

- FM synthesis
- Sample playback
- Basic synthesis engines
- Audio mixing

The architecture is designed to allow additional engines to be added
without changing the sequencer.

---

## Design Philosophy

A key goal of Soundboy is maintaining flexibility during experimentation.

The project prioritises:
- Fast iteration
- Clear separation of systems
- Learning through prototypes
- Building interfaces that encourage exploration
