simple_calc:	simple_calc.l simple_calc.y
				bison -d simple_calc.y
				flex -o simple_calc.c simple_calc.l
				gcc -o $@ simple_calc.tab.c simple_calc.c -ll

clean:
				rm simple_calc.c simple_calc.tab.c simple_calc.tab.h simple_calc

