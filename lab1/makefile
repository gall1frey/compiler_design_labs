a.out: y.tab.c lex.yy.c
	gcc y.tab.c lex.yy.c -ll

y.tab.c: parser.y
	yacc -d parser.y

lex.yy.c: lexer.l
	lex lexer.l
