# Saturn ASCII Art

A small Python script that draws a shaded Saturn and its rings directly in the terminal using colored ASCII characters.

## Requirements

- Python 3.6 or newer
- A terminal that supports ANSI 24-bit (truecolor) color escape codes
- No third-party Python packages are required; the script uses only Python's standard library

## Run

Open a terminal in the folder containing the script and run:

```bash
python Saturn_ASCII_style.py
```

On Windows, you can also use:

```powershell
py Saturn_ASCII_style.py
```

The script prints the artwork in the terminal; it does not create an image file. For the full-width result without line wrapping, use a terminal window at least 150 characters wide. Windows Terminal and most modern terminal emulators support the color output.

## Customize

The drawing dimensions and appearance are set in the script's loops and lighting calculations. Adjust the `range(...)` values to change its size, or edit the brightness and ring conditions to change the shading and rings.
