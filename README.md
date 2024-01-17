# Introduction 
ARXML Generator is a tool to generate ARXML files from given yaml and markdown files for AUTOSAR 4.2.2.

This tool can accelerate the development of AUTOSAR software components by generating ARXML files from yaml and markdown files. The yaml files are used to describe the AUTOSAR software components data types(data structures), and the markdown files are used to describe the AUTOSAR software components interfaces(client-server, sender-receiver). The ARXML files generated by this tool can be imported into AUTOSAR tools such as ETAS ISOLAR.


# Getting Started
1. Python 3.10 or higher is required to run this tool.
2. Install the required packages by running the following command:
```bash
pip install -r requirements.txt
```

# Usage
``` bash
cd 5.Tool
python all.py
```
S
# Features
- Generate ARXML files from yaml and markdown files.
- Sender/Receiver and Client/Server interfaces are supported.
- Nested data structures are supported.
  - Array in Struct
  - Struct in Struct
  - Array in ArrayS