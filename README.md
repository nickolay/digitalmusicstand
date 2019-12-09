# Digital Music Stand

A simple PDF viewer to organize music sheets.

<img src="./.github/digitalmusicstand_001.jpg" />

Usage is similar to Sublime. Press `P` and perform a fuzzy search.

## Get

Download from the [release page](https://github.com/PatWie/digitalmusicstand/releases). THe single binary contains all files.
Or build it yourself:

```bash
git clone https://github.com/PatWie/digitalmusicstand.git
cd digitalmusicstand
go build
```

## Usage

```bash
./digitalmusicstand --sheets /path/to/pdfs --port 3000
```

The files in the sheet directoy need to follow the convention `interpret_title.pdf`. Whitespaces should be replaced by '-'.

Point your browser to `http://localhost:3000`

