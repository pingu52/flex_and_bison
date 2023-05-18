calc_ast:	calc_ast.l calc_ast.y calc_ast.h
			bison -d calc_ast.y
			flex -o calc_ast.lex.c calc_ast.l
			gcc -o $@ calc_ast.tab.c calc_ast.lex.c calc_ast.c

clean:
			rm calc_ast.lex.c calc_ast.tab.c calc_ast.tab.h calc_ast
