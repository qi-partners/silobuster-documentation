# Sanitize URLs

## Assigned to:
- github_user

## Description
This is a small but tricky story to sanitize and validate URLs.

## Requirements

### Objectives

- If the provided value is not a valid URL, see if the value is a string and _contains_ a valid URL.
- Encodings must be correct
- Final stored values must include the protocol (id, "https://")

### Constraints
Make a list of the limitations/things the code can _not_ do.
- 

## Resources
Insert all the materials needed to complete this code.
- URL Specification (https://www.w3.org/Addressing/URL/url-spec.txt)
- Possible headstart for validation in JS (https://gist.github.com/dperini/729294)
- Implements the above in Python (https://miguendes.me/how-to-check-if-a-string-is-a-valid-url-in-python)
- Beautiful Soup Documentation https://beautiful-soup-4.readthedocs.io/en/latest/

## Documentation Protocol
First, include a readme that describes what your code does and explains difficult bits.

README:
URLs can be checked for validity and used in deduplication by downloading the text with the Python package "Beautiful Soup". if errors occur in retrieving the page:
  1. The URL may have an error (fatal),
  2. The page may be temporarily down,
  3. The page may have changed since it was entered in the source record.
If no errors occur, the page will be downloaded to a temeporary file.  The temporary file will be analyzed to determine matching with any of the terms for use by the dedupe modules.  

Second, use descriptive variables and method names so that the code is readable and obvious.


Third, comment each function or method along with inputs and returns, and use other inline comments to make particularly opaque or unavoidably clever code clear.

A story is absolutely __not__ complete until time has been spent at the end revewing, updating, and tidying up documentation.

## Get Help
Questions? Check around to see who's available, and ask:
- cskyleryoung
- devcshort
- greggish

### Washington State Resource Data SiloBuster 08/2022
