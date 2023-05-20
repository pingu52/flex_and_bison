calc_ast_2:	calc_ast_2.l calc_ast_2.y calc_ast_2.h
			bison -d calc_ast_2.y
			flex -o calc_ast_2.lex.c calc_ast_2.l
			gcc -o $@ calc_ast_2.tab.c calc_ast_2.lex.c calc_ast_2.c -lm

clean:
			rm calc_ast_2.lex.c calc_ast_2.tab.c calc_ast_2.tab.h calc_ast_2
