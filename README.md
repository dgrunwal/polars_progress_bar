# Polars Progress Bar

A practical guide and toolkit for implementing progress tracking and debugging techniques with **Polars** data processing workflows.

## Overview

This repository demonstrates how to effectively monitor, debug, and time Polars DataFrame operations in Jupyter notebooks. While Polars is optimized to avoid iteration, this project shows you how to add progress indicators and timing information when needed.

## Features

- 🐛 **Debugging Techniques** - IPython magic commands and debugging strategies
- ⏱️ **Timing Tools** - Automatic execution time tracking with `ipython-autotime`
- 📊 **Progress Bars** - Integration with `tqdm` for visual progress indicators
- 🔄 **Multi-step Workflows** - Manual progress tracking for sequential operations
- 🔗 **Hybrid Approaches** - Combining tqdm with Polars for file loading workflows

## Quick Start

### Installation

```bash
pip install polars tqdm ipython-autotime