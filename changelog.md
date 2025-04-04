### 0.12.0

- Introduced a new environment variable `DISABLE_DICTIONARY`. When this variable is set to true, the functionality for adding words to the dictionary is disabled.
- **Enhanced Text Interaction:** In the language tool, highlighted text segments are now interactive. Clicking on these segments opens sidebar suggestion.
- **Improved Editing Experience:** During the editing process in the language tool, the highlight automatically disappears as it becomes invalid once modifications have been initiated.

### 0.11.0 

- chore: Added nightly builds on develop branch
- secops: dependabot - bump vite to 6 (resolves 6 dependabot warnings)
- chore: Github actions updated to create github release and tags 
- chore: added PR validation GH action
- feature: file upload
- feature: download translation as a file
- feature: tooltips all around

### 0.10.4

- fix: z-index

### 0.10.3

- dockerfile fix

### 0.10.1

- dockerfile fix

### 0.10.0 

- Added clear button to clear text boxes
- Updated development setup for ease of use
- Added auto full display alternative for shorter translations
- Added option to add words to dictionary for grammar checks

### 0.9.0

- State migrated from context to Zustand
- Improvements in AI translation prompt
- Added copy button for grammar checking
- Added SnackBar to inform of action sucess

### 0.8.0

- Added `LIBRETRANSLATE_LANGUAGES` and `LANGUAGE_TOOL_LANGUAGES` env variables to specify supported languages for LibreTranslate and LanguageTool respectively.

### 0.7.0

- Docker tagged releases

### 0.6.1

- Fix: silly mistake, added check on string masking

### 0.6.0

- Added `LIBRETRANSLATE_API_KEY` env variable to support API key authentication for LibreTranslate. [#3](https://github.com/kWeglinski/OmniPoly/issues/3)
- Fixed theme setting [#2](https://github.com/kWeglinski/OmniPoly/issues/2)

### 0.5.1

- Prevent crash on no language selected in language tool.