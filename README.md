As part of the C preprocessor, the de-comment program will accomplish the following tasks: 

1. Remove a comment. The fact that a comment is a token delimiter. After removing a comment, the C preprocessor must make sure that a white space character is in its place.
2. Line numbers. After removing a comment, the C preprocessor sometimes must insert blank lines in its place to preserve the original line numbering.
3. String and character literal boundaries. The preprocessor must not consider the character sequence (/*...*/) to be a comment if it occurs inside a string literal ("...") or character literal ('...').

This project is a COS217 assignment.  A complete code is a private repository and it is available upon request only for employment purpose.
