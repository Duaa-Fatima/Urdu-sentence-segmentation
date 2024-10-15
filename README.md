# Urdu Sentence Segmentation

This project focuses on segmenting Urdu text into sentences. The goal is to develop an efficient sentence segmentation technique that handles challenges such as space insertion and omission, and accurately identifies sentence boundaries. The project includes custom segmentation methods and a comparison with the UrduHack library's segmentation results.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Implementation Details](#implementation-details)
6. [Evaluation](#evaluation)
7. [Results](#results)
8. [Future Work](#future-work)
9. [Contributing](#contributing)
10. [License](#license)

## Project Overview

Sentence segmentation is a crucial step in natural language processing, particularly for languages like Urdu, where text boundaries are not always explicitly marked. This project involves:
- Implementing a custom Urdu sentence segmentation technique.
- Tackling segmentation challenges such as space insertion and omission.
- Comparing the segmentation results with the UrduHack library's output.

## Features

- **Custom Sentence Segmentation**: Implements a method to segment Urdu sentences based on sentence enders (like ".", "؟", "!").
- **Handling Segmentation Challenges**: Addresses issues like extra spaces between words or missing spaces after sentence enders.
- **Evaluation with UrduHack**: Compares the performance of the custom segmentation technique against the UrduHack library's results.

## Installation

To run this project, you need Python 3.x and the following libraries:
- `UrduHack`
- `re` (Regular Expressions)
- `SentencePiece` (optional, if encoding/decoding is used)

You can install UrduHack via pip:
```bash
pip install urduhack
