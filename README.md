# Makefile

## Rule
target: prerequisites<br>
	recipe

## Patterns
all: library.cpp main.cpp

$@ es el <b>target</b>, en este caso <b>all</b>.<br>
$< es el <b>primer prerequisito</b>, en este caso <b>library.cpp</b>.<br>
$^ son los <b>prerequisitos</b>, en este caso <b>library.cpp main.cpp</b>.

## Oficial Documentation 
https://www.gnu.org/software/make/manual/make.html