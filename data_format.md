The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be
interpreted as described in RFC [2119](https://www.ietf.org/rfc/rfc2119.txt).


Data Format
===========
This document specifies requirements for diagnostic data.

Encoding
--------
- All data MUST be UTF-8 encoded. 

Temporal Data
-------------
- MUST include both date and time components.
- MUST be in UTC.
- SHOULD have at least one second resolution.

Structure
---------
- Data SHOULD use name/value pairs instead of lists of bare values.
- Data SHOULD NOT use directly nested lists (e.g., multidimensional arrays).
- Nested structure SHOULD be encoded in yaml/json.
- Data MUST have an internal structure that is unambiguously parseable.
