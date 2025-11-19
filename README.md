# panbuild
Scripts and templates for Pandoc processes

Input file is assumed to be Markdown, so no extension required.

## Dependencies
- `pandoc>=2.14`
- `texlive-xetex`
- `texlive-base`
- `markdown`

To install all dependencies copy and paste the following:
```
sudo apt install pandoc texlive-xetex texlive-base
```

## Usage

```
./panbuild.sh {INPUT_FILE} {OUTPUT_FORMAT}
```

## Header Requirements



```yaml
---
author:         Your Name
email_address:  Your Email
title:          Microchip MCP4822
project_name:   Name of the Project
subtitle:       HAL and Driver Documentation
org_name:       My Company
org_motto:      The motto or something
revision:       0.1
##############################################
# Only 1 of the following 3 lines can be true
formal_report:  true
documentation:  true
kpmreport:      true
#############################################
draft:          true
toc:            true
lof:            true
lot:            true
grayscale:      true
---
```
