Testing Mkdocs
==============

Version 1.1.Mark1

This repo is a sandbox for testing MkDocs.

Important notes:
---------------
- The index.md file must begin with a lower case "i"
- Gradle is not needed for deploying the docs.

Committing
--------------
The build_and_upload_docs bash script must be run from the docs directory.

Updating
---------
Push the changes out to github.  The bash script will create a clone and then run
the mkdocs process on the clone, then the mkdocs process pushes the reults to the
gh-pages branch on github.

