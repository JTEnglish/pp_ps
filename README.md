# pp_ps
The “pp_ps” tool is a re-implementation of the Linux tool “ps” which lists statistics for all the processes in the system.

## Usage
| Sort Options |
|--------------|
| -cpu         |
| -mem         |
| -pid         |
| -com         |

## System Requirements
This tool requires a linux based proc file structure to access the /proc/[pid]/stat and /proc/uptime files.
