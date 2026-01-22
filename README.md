# flutterflow-truncate-text
A small truncateText utility for FlutterFlow custom functions.

## What it does
Safely truncates a string to a maximum number of characters and appends `...` if needed.

## Why this exists
FlutterFlow doesn’t provide a simple built-in way to truncate dynamic text in custom logic without UI hacks.

## Usage in FlutterFlow
1. Create a new Custom Function in FlutterFlow and name it "truncateText"
2. Paste the function code
3. Define the arguments:
   - "input" (String)
   - "maxChars" (int)
4. Use it anywhere you need trimmed text (feeds, titles, previews)

## Preview
<img width="1538" height="863" alt="image" src="https://github.com/user-attachments/assets/e7f5a58d-e933-4e17-9f87-d8cbbd9825c4" />

## Example:
<img width="1193" height="533" alt="image" src="https://github.com/user-attachments/assets/d0b41206-d968-4523-81cb-40c0b7bc6221" />
