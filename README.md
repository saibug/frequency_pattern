## Description
Nagios plugin to check number of lines that contain pattern

## Requirements
- python >= 3.6
- pygtail >= 0.11.1

## Usage
python3 check_frequency_pattern --help

```
usage: check_frequency_pattern [-h] --logfile LOGFILE --pattern PATTERN [--critical CRITICAL] [--warning WARNING]

options:
  -h, --help            show this help message and exit
  --logfile LOGFILE, -l LOGFILE
                        path log file
  --pattern PATTERN, -p PATTERN
                        pattern to check

  --critical CRITICAL, -c CRITICAL
                        critical threshold
  --warning WARNING, -w WARNING
                        warning threshold
```
