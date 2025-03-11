# Condensed Formula to IUPAC Name Converter
## Overview
This Python program converts condensed molecular formulas into their respective IUPAC names using cheminformatics tools. It helps automate chemical nomenclature, making it useful for students, researchers, and chemists.

## Why This Project?
Chemical naming is essential in research, industry, and academia. Manual conversion of condensed formulas to IUPAC names can be time-consuming and error-prone. This tool simplifies the process, ensuring accuracy and efficiency.

## Features
✔ Parses condensed molecular formulas
✔ Converts formulas to molecular structures
✔ Generates accurate IUPAC names using RDKit
✔ Handles a wide range of organic compounds
✔ Command-line interface for easy use

Installation
Make sure Python is installed, then follow these steps:

```
git clone https://github.com/yourusername/condensed-to-iupac.git

cd condensed-to-iupac

pip install rdkit
```

## Usage
Run the script with a condensed formula as input:
python convert.py "CH3CH2OH"
Example Output:
Ethanol

This program can handle more complex structures such as:
CH3COOH → Acetic acid
CH3CH(CH3)CH2OH → 2-Butanol
CH3CH=CH2 → Propene


## License
Apache License January 2004

