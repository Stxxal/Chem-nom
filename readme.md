# Condensed Formula to IUPAC Name Converter
## Overview
This Python program converts condensed molecular formulas into their respective IUPAC names using cheminformatics tools. It helps automate chemical nomenclature, making it useful for students, researchers, and chemists.

## Why This Project?
Chemical naming is essential in research, industry, and academia. Manual conversion of condensed formulas to IUPAC names can be time-consuming and error-prone. This tool simplifies the process, ensuring accuracy and efficiency.

## Features
✔ Parses condensed molecular formulas </br>
✔ Converts formulas to molecular structures </br>
✔ Generates accurate IUPAC names using RDKit </br>
✔ Handles a wide range of organic compounds </br>
✔ Command-line interface for easy use

Installation
Make sure Python is installed, then follow these steps:

```
git clone https://github.com/yourusername/condensed-to-iupac.git

cd condensed-to-iupac

pip install rdkit
```

## Usage
Run the script with a condensed formula as input:</br>
```
python convert.py "CH3CH2OH"
```
</br>
Example Output:</br>
Ethanol</br>

This program can handle more complex structures such as:</br>
CH3COOH → Acetic acid</br>
CH3CH(CH3)CH2OH → 2-Butanol</br>
CH3CH=CH2 → Propene</br>


## License
Apache License January 2004

