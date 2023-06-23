# TeenyCompiler
Based off of [Austin Z. Henley's](https://austinhenley.com/blog.html) teeny tiny compiler




# Lessons learned

Lexers require
    peek() looks at next charector
    nextChar() to advance and get the next char
    Skip whitespaces() to skip white spaces
    skipcomments() skip comments
    getToken() drives the whole lexer, this is where the string is matched to the token, if not error is thrown
    abort() allow error to be thrown so that debugging is possible

Token
    need a list of tokens that represent each possible type (IF, INT, EQUAL)


