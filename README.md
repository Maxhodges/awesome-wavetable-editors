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

- **[WaveEdit](https://github.com/AndrewBelt/WaveEdit)** — Free, cross-platform, open-source wavetable and bank editor originally made for the Synthesis Technology E352 Cloud Terrarium and E370 Quad Morphing VCO. The official Synthesis Technology page (`synthtech.com/waveedit`) went offline in April 2026 and the project is defunct, but the open-source code remains on GitHub and is still useful for hardware/modular workflows and WaveEdit-style banks.
  _Status: defunct (official site offline April 2026) / source on GitHub_

- **[CarveToy](https://www.carvetoy.online/)** — Browser-based tool for creating and sharing custom wavetables. Good for quick experimentation and modular-style wavetable generation without installing anything.
  _Status: free / browser-based_

- **[Sonic Academy NODE](https://www.sonicacademy.com/products/node)** — Dedicated visual wavetable editor/generator. Vector-based waveform editing for creating unique wavetables: drawing, morphing, importing samples, and exporting to common software synth formats.
  _Status: commercial_

- **[Ocean Swift Wavetable Creator](https://oceanswift.net/product/wavetable-creator/)** — Dedicated macOS/Windows wavetable creator focused on export compatibility across hardware, modular environments, and software synths. Includes crossfade/blending techniques and robust export options.
  _Status: commercial_

- **[Lambda Synthetics Wavetable Designer](https://lambdasynthetics.com/wavetable-designer/)** — Browser-based wavetable design tool. Demo mode disables downloading. Worth tracking, especially if it continues developing hardware-friendly export options.
  _Status: commercial / browser-based_

- **[Fine Increments Free Wavetable Generator](https://www.fineincrements.com/free-wavetable-generator)** — Simple browser-based generator for creating and exporting standard WAV wavetables. Designed for Wavefield but also targets synths like Serum, Vital, Pigments, and Massive. Lightweight quick tool rather than a deep editor.
  _Status: free / browser-based_

- **Audio-Term** — Older Windows wavetable/spectral resynthesis utility. Powerful and weird, but not beginner-friendly. Still mentioned by people doing deeper wavetable generation work.
  _Status: Windows-only / needs verification (canonical link)_

- **[WaveForge](https://icalchemy.com/wavetable-generator)** (IC Alchemy) — Free browser-based wavetable generator with four creation modes: freehand drawing, harmonic/additive, math formulas, and image-to-wavetable. Real-time oscilloscope and 3D spectral views, frame morphing, and 32-bit float WAV export compatible with Serum, Vital, and Ableton Wavetable.
  _Status: free / browser-based_

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

- **[Arturia Pigments](https://www.arturia.com/products/software-instruments/pigments/)** — Wavetable + sample + virtual-analog synth with a built-in wavetable editor. Imports audio and parses it to its format (2048 samples/single-cycle, up to 256 frames), and is a common export target for dedicated editors like NODE.
  _Status: commercial_

- **[Ableton Live Wavetable](https://www.ableton.com/en/live/)** — Live's built-in Wavetable device lets you drag and drop audio to turn it into a wavetable and import existing wavetables. Convenient if you already work in Live, though it's a player/synth rather than a deep editor.
  _Status: commercial (bundled with Live)_

- **[Bitwig Studio](https://www.bitwig.com/)** — The Polymer and Grid environments include wavetable oscillators with 100+ built-in tables and custom wavetable import. Strong for modular-style patching workflows.
  _Status: commercial_

- **Xfer Serum / Serum 2** — One of the standard wavetable editor workflows. Strong for sample import, spectral editing, morphing, formula-based generation, and export.
  _Status: commercial / needs verification (Serum 2 docs)_

- **Kilohearts Phase Plant** — Modular synth environment with wavetable editing/generation. Best if you already like modular plugin workflows.
  _Status: commercial / needs verification (docs link)_

- **Tone2 Icarus** — Deep wavetable synth with serious additive/spectral editing tools. More of a full synth workstation than a lightweight editor.
  _Status: commercial / needs verification (docs link)_

- **u-he Hive / UHM** — Supports script-based/procedural wavetable generation using UHM files. Not visual, but powerful for formulaic or algorithmic wavetable design.
  _Status: commercial / needs verification (docs link)_

- **Waldorf Nave** — Wavetable synth with visual/3D wavetable editing, especially notable on iOS.
  _Status: commercial / needs verification (docs link)_

- **Korg modwave / modwave native** — Can import custom wavetables and Serum-format libraries. Relevant for hardware users and people moving between plugin and hardware workflows.
  _Status: commercial / hardware / needs verification (docs link)_

## Hardware and modular-oriented tools

Format compatibility is one of the most painful parts of wavetable work, so these are worth including — but they aren't the main focus of the list.

- **[Wavearium](https://github.com/dotKokott/wavearium)** — WaveEdit-like editor for viewing, searching, creating, and collecting wavetables. Currently focused on the Piston Honda MkIII format. Relevant for Eurorack users, but looks early/unfinished: no releases, tiny repo activity, few stars.
  _Status: experimental / low activity_

- **WaveEdit forks / custom builds** — Some hardware workflows point users toward WaveEdit or modified WaveEdit versions. Deserves a small section once specific forks are verified.
  _Status: needs verification_

- **Erica Synths Graphic VCO tools** — Possible hardware-specific format/export notes.
  _Status: needs verification_

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
- **KVR Audio threads** — Useful for older recommendations like Audio-Term, WaveEdit forks, and obscure utilities. _Needs specific thread links._
- **ModWiggler threads** — Useful for modular/hardware-specific format notes. _Needs specific thread links._

## Contributing

Pull requests are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

Good additions include dedicated wavetable editors, browser-based generators, synths with serious built-in wavetable editing, conversion utilities, hardware-specific tools, and documentation about wavetable formats and compatibility.

## License

[CC0 1.0 Universal](LICENSE) — to the extent possible under law, contributors have waived all copyright and related rights to this curated list.
