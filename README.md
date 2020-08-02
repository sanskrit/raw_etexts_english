## Intro
A repository containing important raw texts (some non-proofread). Processed (eg: transliterated) texts may be placed in other repos/ sites.

### Motivation
- Websites with critical digitized texts have disappeared in the past, to the frustration of users.
- It is easier to search multiple files encoded in plain text.

## Usage
- Clone this repo: `git clone https://github.com/sanskrit/raw_etexts_english.git --recursive --shallow-submodules`
- Initialize submodules if needed: `git submodule update --init --recursive --depth 1`
- Update submodules if needed: `git submodule foreach "(git checkout master; git pull --depth 1)&"`

## Contribution
- Fork this repo and send pull requests.
- Raise issues.
- Add submodule: `git submodule add --depth 1 -- https://github.com/indic-dict/something.git some/path`
### Conventions
Allowed formats in the order of decreasing preference: md (possibly with frontmatter), txt, itx, tex, html.

#### Preferred naming conventions:

- OCR files will be named: xyz_ocr.md or xyz_ocr.txt. 
- When they are being proofread, they will be renamed: xyz_proofreading_.md or txt.
- When fully proofread, they will be: xyz.md or xyz.txt

