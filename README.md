<b><font size = 3>Project: C-UFPL (Compiler for UFPL)</font></b>
</br></br><b><font size = 2>Author: Axel Rom Ignacio BSCS-3</font></b>
</br><b><font size = 2>Lexical analyzer and Syntax analyzer for UCLM's First Programming Language</font></b>

</br>The tokenizer package includes the following:

- <b>structure.py</b> - contains the grammar constants (e.g. token types, keywords, and etc.)<br/>
- <b>tokenizer.py</b> - tokenizes the input and returns the tokens

The syntax_analyzer package includes the following:

- <b>grammar.txt</b> - contains the language grammar
- <b>nodes.py</b> - contains the nodes used in parsing (unused)
- <b>parser</b> - takes in the tokens generated by the tokenizer and returns an error if there is one.