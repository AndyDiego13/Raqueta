### Instructions to used this dfa
## Installing
1. Download  and install Racket
2. Try typing [racket] on your command line
3. To run it type inside racket [(enter! "dfa_tokens")]
## Example
The function [arithmetic-lexer] 
(arithmetic-lexer "3+5 // this is all") '(("3" int) ("+" op) ("5" int) ("// this is all" comment)) "Expression and comment")