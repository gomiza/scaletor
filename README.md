# Scaletor

**Scaletor — A Thermodynamic Laboratory for Musical Scales**

Scaletor is an interactive computational environment for exploring the space of musical scales. It implements a thermodynamic model in which musical scales themselves are regarded as the sites of a finite statistical-mechanical system, each of which can be in an On or Off state.

The model combines combinatorial representations of musical scales with network structures describing relations between them. Musical and structural properties are encoded by interaction tracks and combined into an energy landscape that can be explored through Gibbs distributions, Glauber dynamics, and simulated annealing.

Scaletor currently implements the model for the complete collection of scales in the 12-tone equal temperament (12-TET) tuning system.

## Scaletor 1.0

Version 1.0 implements the mathematical framework developed in the manuscript

**Thermodynamic Formalism of Musical Scales**  
Ricardo Gómez Aíza

[Link to be added when the manuscript/preprint corresponding to Scaletor 1.0 is publicly available.]

The model includes interaction tracks involving:

- interval content;
- modes and mode classes;
- balance;
- entropy;
- interpolation between scales.

The interactions can be combined and independently calibrated through a modular track architecture. Scaletor also provides tools for restricting and freezing regions of the scale space and for exploring the resulting configurations dynamically.

Scaletor is written in [Processing](https://processing.org/) and is distributed as a standalone application for macOS, Windows, and Linux.

## Download

Scaletor is available in three interface sizes. Choose the version that best fits your display:

### Full

Designed for a display area of approximately **2500 × 1330**.

### Medium

Designed for displays up to approximately **1920 × 1080**.

### Small

Designed for displays up to approximately **1300 × 750**.

Each size is available for:

- macOS — Apple Silicon
- macOS — Intel 64-bit
- Windows — Intel 64-bit
- Linux — Intel 64-bit

The current stable version is **Scaletor 1.0.0**.

**Download Scaletor from the latest GitHub Release:**

https://github.com/gomiza/Scaletor/releases/latest

The earlier **v0.9.0** pre-release is retained in the repository for historical purposes and corresponds to an earlier stage in the development of Scaletor and its mathematical model.

All files included in each distribution package should be kept together with the executable.

## Installation

### macOS

Depending on your macOS security settings, the first execution of Scaletor may require removing the quarantine attribute.

Open Terminal, move to the directory containing `Scaletor.app`, for example:

`cd /Users/YourUserName/Applications/scaletor/`

(with your own user name the path that where Scaletor's files have been saved). Then execute

`xattr -d com.apple.quarantine Scaletor.app`

This normally needs to be done only once. Scaletor can subsequently be launched by double-clicking `Scaletor.app`.

Press Esc to quit the application.

For other operating systems, see the Processing instructions for exported applications.

# Hot keys

(A) Anchors the base note.

(M) Turns the external magnetic field On and Off.

(R) Changes the rule to play consecutive scales.

(+) Increases the speed at which scales are played.

(-) Decreases the speed at which scales are played.

(H) Changes the speed at which scales are played (min, medium, max).

(F) Freezes the selected scale.

(Del) Deletes the selected scale.

(T) Scrolls the GUI to the corners, in clockwise direction (only for medium and small displays).

(Arrows) Move the selected scale along the On scales.


# Mathematical model

The mathematical framework underlying Scaletor treats the complete collection of musical scales as a configuration space for a finite random field. Local interaction scores encode musical properties, and their combination determines a Hamiltonian energy function. Gibbs measures and Glauber dynamics are then used to explore configurations favored by selected combinations of musical criteria.

The framework also uses natural networks on the space of scales, including networks determined by scale length, modes, and interpolation. These structures allow interactions to encode both intrinsic properties of individual scales and relations among families of scales.

# Additional information

For more information visit [**Scaletor**'s official website](https://sites.google.com/im.unam.mx/scaletor).

**Author**  

Ricardo Gómez Aíza

Instituto de Matemáticas

Universidad Nacional Autónoma de México
