## Structures.csv table contant

structures.csv file column content explanation with there headings:

### Structure_ID

each structure has an unique ID.
"HOME" means this is not a particular structure or no structure is selected.

### Structure_Type

type of structure

### Structure_Name

Structure name

### Groups

Group name the structure belongs to. a structure can have several groups. In that case they are ; separated.

### Latitude

Latitude of the structure.

### Longitude

Longitude of the structure.

### Path

File path for the documents for corresponding structure. path can be local or google drive files. A structure can have several document paths. In that case, they will be new line separated.



### Title

Document title of the corresponding paths. Each path has its own title. A structure can have several document title. In that case, the title will be new line separated.



## How to display in right panel



path can can be file (like google doc, spreadsheet, slides, pdf etc) or folder. 
if path is file display it , a floating button of top right corner will open the file in new browser tab.

if path is folder, show a button to open the folder in new browser tab.

display olny the files/folders that can be access.

at start of webpage  or when no structure is selected in map display, display paths of "HOME" structure id.