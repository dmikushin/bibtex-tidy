# Changelog

### v1.3.1

- add --quiet and --no-backup CLI options

### v1.3.0

- Duplicate checking now checks whole title rather than just the first 50 characters.

### v1.3.1

- #12 Added --quiet and --no-backup

### v1.4.0

- #13 Allow multiple files on CLI. This will output multiple tidied files (ie this does not combine them) e.g. bibtex-tidy file1.bib file2.bib
- #14 Add .pre-commit-hooks.yaml
- #15 Add option for trailing commas
- #16 Option to remove empty fields
- Add --no-lowercase option to prevent bibtex-tidy from changing case of field names and entry types

### v1.4.1

No changes, aside from correcting version number at top of bibtex-tidy.js

### v1.4.2

- #17 Restore --help option
- Support for older browsers and node versions

### v1.5.0

- Breaking change: paragraphs within field values will now be preserved
- #18 --enclosing-braces option added to preserve case when compiling BibTeX
- #19 --wrap option added for wrapping long values

### v1.6.0

- #20 added --max-authors option for truncating long list of authors

### v1.6.1

- Improve CLI help text for --max-authors

### v1.7.0

- #23 #28 Prevent adding enclosing brace on each tidy
- `--remove-dupe-fields` / `removeDuplicateFields` option added
- Better generation of CLI command in Web UI
- Improved man page
- Handle CRLF/CR line endings
- Handle empty entry key
- Handling empty entries

### v1.7.1

- Add --version CLI option

### v1.8.0

- Better handling of invalid CLI params
- New higher performance bibtex parser
- Better handling of comments
- #38 Fix "-" in input args not being interpreted as stdin
- #41 Set minimum node 12
- #51 Remove invalid windows filename chars
- #47 Fix parsing for concatenate after literal
- Retain whitespace in quoted values
- #47 Do not trim braced values if concatenated
- #32 Sort month and numeric values
- #27 Do not escape math expressions
- #44 Option to generate standardised keys

### v1.8.1

No changes, aside from correcting version number at top of bibtex-tidy.js

### v1.8.2

Add type definitions

### v1.8.3

No changes, aside from correcting version number at top of bibtex-tidy.js

### v1.8.4

Remove npm prepare script

### v1.8.5

- New release process, including tagging releases (#75)

### Unreleased

- removal of DUPLICATE_KEY
- DUPLICATE_ENTRY now has a 'rule' property (can be key, doi, citation, or abstract)
- add --blank-lines option to separate entries with a blank line
