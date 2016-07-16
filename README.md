# buildinfo-cases
### This repo consist of expected output " Ignoring `.buildinfo` while comparing `.changes` "
---
Test cases:

case-1: Contents are identical and files in `Files` are identical
=>  No differences

case-2: Contents are identical and files in `Files` differ
=> Differences of all files in `Files` including `.buildinfo`

case-3: Contents differ and files in `Files` identical
=> Differences of Contents including `.buildinfo` differences
