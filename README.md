transfer.sh
===========

https://transfer.sh/

transfer.sh (https://transfer.sh/) is a service to
share your files.
You can upload you files on that web site.

With transfer (a simpe wrapper for transfer.sh),
you can easily upload/download your files from the command-line

# Features

  - Share files just with a URL
  - Upload up to 5 GB
  - Files are stored for 14 days
  - For free

# Usage

usage: transfer [-h] [-u FILE]
  -h, --help show this help message and exit
  -u, --upload-file specify the path of the file you want to upload

**Example1: Upload a file**
```
    # Upload a file to https://transfer.sh
    $./transfer -u /path/to/file
```
