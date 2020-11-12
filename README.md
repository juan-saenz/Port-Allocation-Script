# Port-Allocation-Script

This script helps facilitate to export all the port allocations from a cisco switch to an excel sheet. (currently limited to .xls)


## Requirements

```bash
sudo easy_install pip
```

```bash
pip install xlwt
```

```bash
pip3 install easygui
```

## Usage

Drag and drop python script in folder with all the other subfolders of schools that each contain complete MDF/IDF .txt files. 

```bash
python format_logs.py 
```

Next add the provided .xlam to your Excel Add-Ins to have the macro filter and sort the information to it's respective location.
