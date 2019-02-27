# Processing backlog or replication packages for the Review of Economic Studies
## Where we are now
Replication packages for each accepted manuscript are stored in a ZIP file on Dropbox, with mostly consistent naming conventions. These ZIP files are created manually and uploaded to the publisher's website.
## Where we want to be
All packages stored on https://zenodo.org/ with metadata and DOI so that they are citable. Those packages that are small enough should also be on https://github.com/restud-replication-packages
## User stories
- As a _reader_, I want to be able to _browse_ replication packages easily, so that I get _inspired_ for doing similar work.
- As a _data editor_, I want to _accept GitHub repos_ as submissions so that I can _encourage tech savvy authors_ to submit.
- As a _production manager_, I want _easy upload_ to our repos so that I _don't make any mistakes_ during manual work with ZIP files.
- As an _author_, I want the _submission process to be smooth_ so that I can _focus on my research_.
- As a _reader_, I want to have _precise citation_ (inlcuding DOI) easily availabe so that I can _give credit_ to researchers.

## Tasks
- Explore Github and Zenodo API.
- Explore folder and file structure in Restud backlog.
- Build a datastore of metadata of replication packages. (zenodo UI? submisssion form in .docx format? new, structured submission form?)
- Develop/test tool to upload ZIP files to GitHub as new repos.
- Develop/test tool to pull these repos over to Zenodo and publish them with a DOI.