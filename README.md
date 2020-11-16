# Port-Allocation-Script

This script helps facilitate to export all the port allocations from a cisco switch to an excel sheet. (currently limited to .xls)


## Requirements

###### MAC OS
```bash
sudo easy_install pip
```

```bash
pip install xlwt
```

###### Windows
Download and install Visual Studio Code, download Python package from the Marketplace.

```bash
pip install xlwt
```

## Usage

Drag and drop python script in folder with all the other subfolders of schools that each contain complete MDF/IDF .txt files. 

```bash
python format_logs.py 
```

Next add the provided .xlam to your Excel Add-Ins to have the macro filter and sort the information to it's respective location.
