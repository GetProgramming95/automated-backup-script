# Automated Backup Script

This is a simple Bash script for creating compressed backups of recently modified files in a specified target directory. It creates a `.tar.gz` archive of all files changed within the last 24 hours and moves it to a destination directory.

## Features

- Validates input and directories
- Automatically timestamps backup files
- Compresses only recently modified files
- Uses standard Linux tools (`tar`, `date`, `pwd`, etc.)

## Usage

```bash
./backup.sh <target_directory> <destination_directory>
