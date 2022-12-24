# Childrens Book Creator

Given a text / book, rewrites it into the style of a formatted children's picture book (as a docx file).

An example input file can be found in the 'input_files' folder and an example output file can be found in the 'output_files' folder

- Uses <b>ChatGPT</b> AI to simplify and rewrite the text into the style of a children's book.
- Uses <b>DALL-E</b> AI to create images that relate to the text.


### How to set up:
1) Install dependencies in 'requirements.txt' file
2) Create an account with ChatGPT and with DALL-E (2 seperate accounts)
3) In the 'config.toml' file, update the values with your login details

### How to use:
1) Place input texts into the 'input_files' folder, as a '.txt' file.
2) Run command
3) The output file (as a '.docx' file) will be created in the 'output_files' folder


```
Usage: python createdoc.py [-h] -i INPUT_FILE -n BOOK_NAME

Options:
  -h, --help                                        show this help message and exit
  -i INPUT_FILE, --input_file INPUT_FILE            Name of input file
  -n BOOK_NAME, --book_name BOOK_NAME               Name of output book
```