# Language-Translator
This Python script is a command-line interface (CLI) tool designed for language translation. It leverages the translate library to provide easy and customizable translation functionality.
**Features**
Translate text from one language to another.
Supports specifying both source and target languages via command-line arguments.
Defaults to translating into English if no target language is specified.
**How It Works**
The script uses the argparse library to parse command-line arguments:
--from_lang: Specifies the source language of the text (optional).
--to_lang: Specifies the target language for translation (defaults to English if not provided).
Prompts the user to input the text they want to translate.
Uses the translate library's Translator class to perform the translation.
Handles exceptions gracefully in case of translation errors and outputs the result.
**Usage**
Run the script using Python with optional arguments for source and target languages:
    python translator.py --from_lang <source_language> --to_lang <target_language>
**Example**
    python translator.py --to_lang Spanish
    Input:
    Enter text to translate: Good morning, everyone.
    Output:
    Buenos días, a todos.
**Requirements**
Python 3.x
translate library
Install dependencies using:
pip install translate


