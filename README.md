# moodleUtils
Various python scripts to help with moodle tasks


## xlsx2glossary.py  Create a Moodle glossary from an xlsx script

### Usage:

1. Edit the GlossaryTemplate.xml to provide the glossary metadata (name and description)
2. Edit the entry template in this script to provide the desired entry metadata
3. Prepare an xlsx sheet with the terms and definitions arranged in columns with a header element indicating which one contains terms and which one contains definitions
4. Run the script: python xlsx2glossary.py to produce the glossary as output.xml
5. Import the xml file into your moodle instance

### Dependencies

1. lxml
2. openpyxl