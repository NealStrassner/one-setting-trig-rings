# Two Sliding Rings: A Self-Checking Instrument that Reads Sine, Cosine and Tangent at One Setting (v1.0)

## Overview

This is an interactive browser-based tool accompanying a 2026 academic paper by Neal Strassner. Two identical rings, each marked with the sixty repeating last digits of the Fibonacci numbers, are slid over each other until they cross on an angle — and the instrument reads sine, cosine and tangent from that one setting.

## Key Functionality

At each setting the distance between the two centres, halved, is the **cosine**, the distance between the two crossings, halved, is the **sine**, and their ratio is the **tangent** — all from one position. Every reading is certified by the digits sitting under the crossings (Neal's Net). Finer rings of the same digits reach any decimal angle, and run backward the instrument reads an angle from a length.

## Core Controls

A slider, arrow keys, or the play button sweep the angle. Toggles show the cosine line between the centres, the sine line between the crossings, the net checksum, and the tangent. Every value is shown with its digit certificate, so the instrument gives the answer and checks it at the same time.

## Technical Details

The tool runs entirely offline with no external dependencies or data transmission. All values are computed from the ring's own anchors (the golden ratio and √3) by angle-addition and a small-angle series — **not** the browser's Math.sin/cos/tan — so the instrument certifies its own answers against the classical values. The source is a single readable HTML file available for inspection.

## Attribution & Access

**Creator:** Neal Strassner  
**Code:** Implemented by Claude (Anthropic) under Neal Strassner's direction  
**License:** CC BY 4.0  
**Paper (Zenodo):** https://doi.org/10.5281/zenodo.22833894  
**Repository:** https://github.com/NealStrassner/one-setting-trig-rings  
**Live Demo:** https://nealstrassner.github.io/one-setting-trig-rings/
