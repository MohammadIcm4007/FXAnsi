# FXAnsi

FXAnsi is a lightweight and simple C and C++ library that provides extensive support for ANSI colors and effects in the terminal.

## Features

- Supports various ANSI colors with different bit depths (8-bit, 16-bit, 24-bit)  
- Easy customization of colors and effects  
- No external dependencies  
- Suitable for developing colorful and dynamic command-line applications  
- Includes terminal control functions such as cursor movement and screen clearing

## Installation

If you only need the predefined ANSI variables (like `ANSI_RED`, `ANSI_BOLD`, etc.), it's enough to include the `fxansi.h` header in your project.

However, if you also want to use the utility functions that generate ANSI codes (such as `build_ansi()` or `build_ansi_bg()`), you must add both the source files and the header to your project.

---

This project is licensed under the [BSD 3-Clause License](https://opensource.org/licenses/BSD-3-Clause).
