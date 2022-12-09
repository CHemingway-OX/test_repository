# test_repository
## in this document I shall outline testing procedure for my efforts to make my research more reproducible.
for initial testing of git hub

### Steps for commiting my data to a repository
- create an account at a repository like github
- create a new project
- synchronize changes with project folders on my computer.

### In this section I'd like to collect milestone of making my research more reproducible
- [x] created an account on github
- [x] downloaded atom a markdown editor
- [ ] connect folder on Mac with github

### what a good `readme.md` file should contain:
- should be placed in the root of a directory so that anybody can use the file to know their way around
- specify software dependencies, versions, and where they should be installed
- provide the structure of the directory and tell people where to find things in the document
  - use separate directories for:
    - code
    - data
    - tables
    - figures
    - documents
    - raw data  
- give instructions to somebody that enters a project and what they should do.

### General notes on reproducible research
- raw data should be kep *raw*
- use scripts for repeating things, do not do things manually as this might introduce errors.
- be very explicit about instructions; be able to look back on analysis later!
- scripts must use comments to explain what they do

### Notes on automatation
- keep track of ordering and maintenance of dependencies
- why use text to document?
  - version control can track changes that are beeing made, not possible in the same way when using formatted text.
  - anyone can read the text without the use of commercial software
  - code can be used to generate and read text
