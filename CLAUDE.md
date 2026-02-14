# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **digital assets repository** for architectural design — not a software project. It contains CAD files, vector graphics, textures, materials, reference images, and parametric design scripts used in architectural visualization.

## Repository Structure

- **code/gh/** — Grasshopper parametric design definitions (.gh) for stairs, trusses, trees
- **linework/** — CAD linework, reusable blocks, line weight standards, precedent models (.3dm, .skp)
- **silhouettes/** — Vector silhouettes for rendering (buildings, cars, people, trees in .svg/.ai/.eps)
- **images/** — Photography reference library (grass, road, sky)
- **textures/** — Tileable textures for rendering
- **materials/maxwell/** — Maxwell Render material files (.mxm)
- **precedent/** — Reference building plans, layouts, stair studies (PDFs, notes)
- **partial/** — Work-in-progress project-specific assets
- **notes/** — Research notes

## Key Details

- Almost all files are binary (CAD, images, vectors, materials). Very little text/code content.
- Grasshopper files (.gh) are binary — they cannot be read or edited as text.
- No build system, no dependencies, no tests. This is a static asset collection.
- Git remote: `https://github.com/chirs/architecture_tools.git` on `master` branch.
