# GLF-Grafem

## About
Grafem is a robust and highly versatile Neo-Grotesque sans-serif, engineered for both striking visual impact and functional clarity. Rooted in the principles of mid-century industrial typography, it seamlessly balances mechanical precision with contemporary design sensibilities. The letterforms are built on a solid, geometric foundation characterized by low-contrast strokes, which grants the typeface a strong, almost monolinear presence. The horizontal terminals (the straight cuts at the ends of the strokes) provide a clean, disciplined, and no-nonsense aesthetic.

## Building the Fonts Manually

If you prefer to compile the font files locally on your machine from the raw source data, follow these steps:

### Prerequisites
Make sure you have **Python 3.10 or higher** installed on your system.

### Installation
Open your terminal and install the required font engineering tools via pip:
```bash
pip install fontmake glyphsLib fontbakery[googlefonts] gftools
```

### Build Instructions
Run the following command to generate desktop-ready OpenType and TrueType fonts:
```bash
# Create destination directories
mkdir -p fonts/ttf fonts/otf

# Compile the .glyphs source file
fontmake -g sources/GLF_Grafem.glyphs -o ttf --output-dir fonts/ttf/
fontmake -g sources/GLF_Grafem.glyphs -o otf --output-dir fonts/otf/
```
The compiled files will appear inside the newly created `fonts/` directory.

## License
This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
https://openfontlicense.org

## Contributors
Sidiq Kamal Nurmawan <sidiq.nurmawan@gmail.com>
Erwin Wirianata <wirianata.erwin@gmail.com>
