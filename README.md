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

## optional arguments:
    -h, --help show this help message and exit
    -u, --upload-file specify the path of the file you want to upload
    -d, --download-url specify the url that you want to download.

**Example1: Upload a file**
```
    # Upload a file to https://transfer.sh
    $./transfer -u /path/to/file
```

**Example2: Download a file**
```
    # Download a file from https://transfer.sh/1gYMVr/tranfer
    $./transfer -d https://transfer.sh/1gYMVr/tranfer
```
