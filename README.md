I'm a postdoctoral researcher in computational cosmology at the [AstroParticule & Cosmologie Laboratory (APC, CNRS/IN2P3)](https://apc.in2p3.fr/) in Paris, working on instrumental systematics, data analysis, map-making, and fast spherical-harmonic methods for the next generation of Cosmic Microwave Background experiments.

---

## Research Focus

- **Beam systematics** — how an imperfect optical response leaks into the maps, and how to model it before it becomes a bias
- **Map-making** — turning time-ordered detector data into polarised sky maps, and keeping the operators linear enough to invert
- **Spherical harmonics algorithms** — fast, accurate transforms on HEALPix and other grids on the sphere
- **Accelerated pipelines** — JAX and GPU implementations of the above, differentiable where it helps
- **Local LLMs** — running open-weight models on my own hardware and building the tooling around them: tool-calling agent loops, quantised inference with `llama.cpp` and MLX, speculative decoding, and semantic memory over vector search
- Occasionally other stuff — games in Godot and Pygames, news collections and analysis, predictive financial tools

---

## Main Projects

| Project | What it does |
|---|---|
| [**FURAX**](https://github.com/CMBSciPol/furax) | JAX-based framework for CMB component separation and map-making |
| [**tod_generation_mapbased_beam**](https://github.com/ArtemBasyrov/tod_generation_mapbased_beam) | Sample-based TOD generation: convolves polarised I/Q/U maps with a pixelated beam along the scan ([docs](https://tod-generation-mapbased-beam.readthedocs.io/en/latest/index.html)) |
| [**HP2SPH_python**](https://github.com/ArtemBasyrov/HP2SPH_python) | Fast, accurate HEALPix ↔ `alm` transforms via a double Fourier sphere, NUFFT and Slevinsky's FSHT — scalar and spin-2 |
| [**sparse_beam_matrix_creation**](https://github.com/ArtemBasyrov/sparse_beam_matrix_creation) | Builds a beam matrix at map level, skipping harmonic space entirely |
| [**LLM_tools**](https://github.com/ArtemBasyrov/LLM_tools) | Tool-calling agent harness for locally hosted LLMs — file edits, code intelligence, git, search, memory |


---

## Contributor

| Project | What it does |
|---|---|
| [**Commander**](https://github.com/Cosmoglobe/Commander) | Bayesian end-to-end CMB analysis by Gibbs sampling |
| [**s2fft**](https://github.com/astro-informatics/s2fft) | Differentiable, accelerated spherical transforms |
| [**jax-healpy**](https://github.com/CMBSciPol/jax-healpy) | JAX implementation and extension of `healpy` |

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JAX](https://img.shields.io/badge/JAX-A8B9CC?style=flat&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Numba](https://img.shields.io/badge/Numba-00A3E0?style=flat&logo=numba&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Fortran](https://img.shields.io/badge/Fortran-734F96?style=flat&logo=fortran&logoColor=white)
![Julia](https://img.shields.io/badge/Julia-9558B2?style=flat&logo=julia&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Specialties:** CMB Analysis | Beam Systematics | Map-Making | Spherical Harmonic Transforms | Automatic Differentiation | HPC | Local LLM Tooling

If the problem demands it, I'll learn the language.

---

## 📍 Paris, France &nbsp;|&nbsp; 🌌 CMB
