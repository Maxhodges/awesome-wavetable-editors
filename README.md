# Awesome Wavetable Editors

A curated list of tools for creating, editing, converting, and exploring wavetables for software synths, hardware synths, modular gear, and experimental sound design.

This list focuses on wavetable-specific tools rather than general-purpose audio editors. It includes dedicated editors, browser generators, synths with strong built-in wavetable editing, hardware-oriented utilities, and format/conversion notes.

Short notes are preferred over a giant feature matrix. Where a project looks abandoned, experimental, or hardware-specific, that's flagged inline.

## Contents

- [Dedicated wavetable editors and generators](#dedicated-wavetable-editors-and-generators)
- [Synths with useful built-in wavetable editors](#synths-with-useful-built-in-wavetable-editors)
- [Hardware and modular-oriented tools](#hardware-and-modular-oriented-tools)
- [Format and compatibility notes](#format-and-compatibility-notes)
- [Related resources and forum threads](#related-resources-and-forum-threads)
- [Contributing](#contributing)

## Dedicated wavetable editors and generators

- **[CarveToy](https://www.carvetoy.online/)** — Browser-based tool for creating and sharing custom wavetables. Good for quick experimentation and modular-style wavetable generation without installing anything.
  _Status: free / browser-based_

- **[WaveForge](https://icalchemy.com/wavetable-generator)** (IC Alchemy) — Free browser-based wavetable generator with four creation modes: freehand drawing, harmonic/additive, math formulas, and image-to-wavetable. Real-time oscilloscope and 3D spectral views, frame morphing, and 32-bit float WAV export compatible with Serum, Vital, and Ableton Wavetable.
  _Status: free / browser-based_

- **[Sonic Academy NODE](https://www.sonicacademy.com/products/node)** — Dedicated visual wavetable editor/generator. Vector-based waveform editing for creating unique wavetables: drawing, morphing, importing samples, and exporting to common software synth formats.
  _Status: commercial_

- **[Ocean Swift Wavetable Creator](https://oceanswift.net/product/wavetable-creator/)** — Dedicated macOS/Windows wavetable creator focused on export compatibility across hardware, modular environments, and software synths. Includes crossfade/blending techniques and robust export options.
  _Status: commercial_

- **[Lambda Synthetics Wavetable Designer](https://lambdasynthetics.com/wavetable-designer/)** — Browser-based wavetable design tool. Demo mode disables downloading. Worth tracking, especially if it continues developing hardware-friendly export options.
  _Status: commercial / browser-based_

- **[Fine Increments Free Wavetable Generator](https://www.fineincrements.com/free-wavetable-generator)** — Simple browser-based generator for creating and exporting standard WAV wavetables. Designed for Wavefield but also targets synths like Serum, Vital, Pigments, and Massive. Lightweight quick tool rather than a deep editor.
  _Status: free / browser-based_

- **[AudioTerm](https://modwiggler.com/forum/viewtopic.php?t=195396)** (by Mathias Gurk) — Free Windows FFT-based wavetable generator and resynthesis utility. Analyzes samples and builds wavetables (KTERM/XFORM modes), assembles single cycles, and exports WAV for common synths. Powerful but not beginner-friendly; no official site — distributed via the ModWiggler thread.
  _Status: free / Windows-only / legacy_

- **[WaveEdit](https://github.com/AndrewBelt/WaveEdit)** — Free, cross-platform, open-source wavetable and bank editor originally made for the Synthesis Technology E352 Cloud Terrarium and E370 Quad Morphing VCO. The official Synthesis Technology page (`synthtech.com/waveedit`) went offline in April 2026 and the project is defunct, but the open-source code remains on GitHub and is still useful for hardware/modular workflows and WaveEdit-style banks.
  _Status: defunct (official site offline April 2026) / source on GitHub_

## Synths with useful built-in wavetable editors

These are full synths, not lightweight editors — but their built-in wavetable editing is good enough to use as a design/export tool.

- **[Vital](https://vital.audio/)** — Free/paid wavetable synth with a surprisingly deep built-in editor. Supports graphical manipulation of waveforms, harmonics, and phases, plus converting samples to wavetables. Useful even if you only use it to design and export tables. ([Wavetable editor docs](https://davidmvogel.com/docs/Vital/UserGuide/Wavetable-Editor))
  _Status: free / commercial_

- **[u-he Zebralette 3](https://u-he.com/products/freeware/zebralette/)** — Free synth built around a single, very deep oscillator with a genuinely excellent wavetable/spectral editor: spline-based editing, Bézier handles, freehand drawing, warping/morphing, and additive synthesis. Exports the pure wavetable as WAV for use in other synths. One of the best free design-and-export tools available.
  _Status: free_

- **[Surge XT](https://surge-synthesizer.github.io/)** — Free, open-source synth (Win/macOS/Linux, VST3/AU/CLAP/LV2/standalone) with a wavetable oscillator and a script ("wtscript") oscillator that generates wavetables from Lua, with FFT helpers. Exports to `.wav`, `.wt`, Serum, and Bitwig `.wt` formats — useful as a programmable wavetable factory.
  _Status: free / open source_

- **[Vaporizer2](https://github.com/VASTDynamics/Vaporizer2)** (VAST Dynamics) — Free, open-source (GPL-3.0) hybrid wavetable/additive synth with a deep built-in wavetable editor: draw mode with Bézier curves, plus frequency shift, smoothing, bend, and bloat on single cycles. VST2/VST3/AU/AAX/CLAP/LV2 and standalone on Win/macOS/Linux.
  _Status: free / open source_

- **[Xfer Serum / Serum 2](https://xferrecords.com/products/serum-2)** — One of the standard wavetable editor workflows. Real-time wavetable editor for creating waveforms from scratch or editing existing ones, plus sample import, spectral editing, morphing, and formula-based generation. Serum 2 is a free upgrade for Serum 1 owners.
  _Status: commercial_

- **[Kilohearts Phase Plant](https://kilohearts.com/docs/wavetables)** — Modular synth with a full built-in wavetable editor: draw partials or freehand frames, morph between keyframes, and import/convert samples to wavetables. Best if you like modular plugin workflows.
  _Status: commercial_

- **[Tone2 Icarus](https://www.tone2.com/icarus-wavetables.html)** — Hybrid wavetable synth with a deep wavetable editor (100+ tools), additive/spectral editing, draw-your-own waveforms, and one-click resynthesis of audio into wavetables. Imports/exports tables to other synths. More a full workstation than a lightweight editor.
  _Status: commercial_

- **[u-he Hive / UHM](https://u-he.com/products/hive/)** — Supports procedural wavetable generation via `.uhm` (u-he math) scripts: readable text files that build wavetables from formulas and commands. Not visual, but powerful for formulaic/algorithmic design; the UHM format is shared across u-he synths.
  _Status: commercial_

- **[Waldorf Nave](https://waldorfmusic.com/nave-ios/)** — Wavetable synth with a 3D wavetable editor: draw and edit tables, analyze audio files, and even generate wavetables from typed speech (the "Talk" function). Especially notable on iPad; also available as desktop VST/AU/AAX.
  _Status: commercial_

## Hardware and modular-oriented tools

Format compatibility is one of the most painful parts of wavetable work, so these are worth including — but they aren't the main focus of the list.

- **[Wavearium](https://github.com/dotKokott/wavearium)** — WaveEdit-like editor for viewing, searching, creating, and collecting wavetables. Currently focused on the Piston Honda MkIII format. Relevant for Eurorack users, but looks early/unfinished: no releases, tiny repo activity, few stars.
  _Status: experimental / low activity_

## Format and compatibility notes

Wavetable compatibility is messy. Different synths expect different frame counts, sample lengths, bit depths, and file layouts, so a table that loads cleanly in one synth may import wrong (or not at all) in another.

Things that commonly differ between targets:

- number of frames per wavetable
- samples per frame
- supported bit depth
- whether the target uses one WAV file, multiple WAV files, folders, banks, RAW files, or proprietary formats
- whether it supports Serum/Vital-style WAV tables
- whether it can import single-cycle waves
- whether it interpolates between frames
- whether conversion is needed before loading into hardware

## Related resources and forum threads

- **[Synthstrom Audible forum: Wavetable creation tools](https://forums.synthstrom.com/discussion/4406/wavetable-creation-tools)** — Existing forum discussion/index attempt. Useful but not a structured list.
- **[WaveEdit Online](https://waveeditonline.com)** — Community site hosting 100+ free WaveEdit-format wavetable banks (E352/E370 and compatible). Handy source of ready-made tables to import or convert.
- **[KVR Audio: Easiest VST to create custom wavetables?](https://www.kvraudio.com/forum/viewtopic.php?t=627271)** — Representative recommendation thread; KVR is also where older utilities like Audio-Term and WaveEdit forks get discussed.
- **[ModWiggler: WaveEdit wavetable share thread (2026 and beyond)](https://www.modwiggler.com/forum/viewtopic.php?p=4462998)** — Active modular/hardware thread sharing tables for Multiwave, Piston Honda MkIII, Kermit MkIII, and E352/E370, with practical format/conversion discussion.
- **[ModWiggler: Loading custom wavetables on Piston Honda MkIII](https://modwiggler.com/forum/viewtopic.php?t=225848)** — Explains the PH MkIII file layout (eight `1.wav`–`8.wav` files, X/Y/Z slider mapping) — a good concrete example of how messy hardware wavetable formats get.

## Contributing

Pull requests are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

Good additions include dedicated wavetable editors, browser-based generators, synths with serious built-in wavetable editing, conversion utilities, hardware-specific tools, and documentation about wavetable formats and compatibility.

## License

[CC0 1.0 Universal](LICENSE) — to the extent possible under law, contributors have waived all copyright and related rights to this curated list.
