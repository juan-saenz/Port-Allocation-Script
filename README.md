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

```bash
pip install pyexcel pyexcel-xls pyexcel-xlsx
```

###### Windows
Download and install Visual Studio Code, download Python package from the Marketplace.

```bash
pip install xlwt
```

```bash
pip install pyexcel pyexcel-xls pyexcel-xlsx
```

## Usage

Drag and drop folders of log text files to the DRAG_CONFIGS_HERE of your cloned repository.

```bash
python format_logs.py 
```

Next add the provided .xlam to your Excel Add-Ins to have the macro filter and sort the information to it's respective location.

Shortcut for the Macro is defaulted to 
###### MAC OS
⌘ + ⌥ + X

###### Windows
Windows + Ctrl + X