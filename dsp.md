# DSP & Audio Engine

## Overview

Soundboy explores real-time audio generation on a small, affordable
embedded platform.

The audio system is designed around experimentation: building different
sound generation approaches, understanding their limitations, and creating
an instrument that encourages exploration rather than simply recreating
existing workflows.

---

## Audio Architecture

The audio system is divided into separate components:


Sequencer

|

Voice Management

|

+-------------+
| |
FM Synth Sample Engine

|

Mixer

|

Audio Output


This separation allows different sound engines to be developed and tested
independently.

---

## Synthesis Experiments

### FM Synthesis

FM synthesis has been a major area of exploration within Soundboy.

The focus has been on understanding:

- Operator relationships
- Frequency ratios
- Modulation depth
- Envelope behaviour
- Creating expressive sounds with simple building blocks

The goal is not to recreate a specific synthesiser, but to explore how a
small number of parameters can produce a wide range of musical possibilities.

---

## Sample Playback

Alongside synthesis, Soundboy includes sample-based workflows.

This explores:

- Triggering recorded sounds
- Sequencing samples alongside synthesis
- Managing memory and playback constraints
- Combining generated and recorded audio

---

## Real-Time Constraints

Working with embedded hardware introduces practical limitations.

Areas of consideration include:

- CPU usage
- Audio buffer size
- Timing accuracy
- Memory management
- Latency

These constraints influence both the software design and the musical
experience.

---

## Sequencing & Timing

A musical instrument depends on timing feeling reliable and predictable.

Soundboy's sequencing system explores:

- Step-based sequencing
- Pattern playback
- MIDI timing
- Parameter changes
- Performance-focused interaction

The aim is to make complex behaviour feel simple from the user's perspective.

---

## Learning Through Prototyping

Many DSP decisions in Soundboy have been driven by experimentation:

- Testing different synthesis approaches
- Listening to the results rather than only measuring them
- Balancing technical complexity against musical usefulness

The process is as much about understanding the relationship between code,
sound and interaction as it is about the final implementation.

---

## Future Exploration

Possible areas for development:

- Additional synthesis methods
- Effects processing
- More advanced modulation systems
- Improved voice management
- External hardware integration
