# moodleUtils

Various python scripts to help with moodle tasks

## xlsx2glossary.py

Create a Moodle XML glossary from a xlsx document

### Usage:

1. Clone the repository to your local system and set it as the working directory
2. Edit the GlossaryTemplate.xml to provide the glossary *metadata* (Name and Description of the glossary)
3. Edit the entry template in the [script](xlsx2glossary.py) to provide the desired entry metadata
4. Prepare an [xlsx sheet](terms.xlsx) with the terms and definitions arranged in columns as follows: a header element
   indicating which one contains *terms* and which one contains *definitions*
5. Run the script, e.g., python3 xlsx2glossary.py to produce the glossary as output.xml
6. Import the xml file into your moodle instance

### Dependencies

1. lxml
2. openpyxl