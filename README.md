# REPLACEX
Tool for text replacing.

The program replaces each line in "REPLACE WHAT" with corresponding line from "REPLACE WITH" field. The program will try to follow the document structure when replacing the text.

When line continuation has been requested, it will try to replace continued lines in the following matter: ABC, then A\nBC and lastly A\nB\nC with \n indicating a new line.

There are 5 line commands available:

- In all fields, %r? will force new line in the output.
- in the INPUT field, %n? can be used for no replace of the specific line.
- in the INPUT and REPLACE WITH fields, %s? can be used to skip the input line from any processing (it won't be in the output).
- in the REPLACE WHAT/WITH fields, %+? and %-? can be used on either beginning or at the end of the line to indicate a line continuation.

<img width="1924" height="1080" alt="REP" src="https://github.com/user-attachments/assets/05d4b4d1-0912-4e1c-9e83-d4d92cadeb80" />
