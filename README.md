# ro-crate-editor-profile-tools

Tools for deriving RO-Crate Editor Profiles from schemas and other utilities

## Convert a SOSS-crate to a profile

Call the script passing an RO-Crate Metadata File (-c) and an output path (-p)

Eg
```
node soss2profile.js -c ro-crate-metadata.json -p ../crate-o/src/profiles/test-profile.json
```