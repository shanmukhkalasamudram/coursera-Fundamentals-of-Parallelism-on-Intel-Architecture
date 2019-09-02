TARGET=main.cc

default: app-icc app-gcc

app-icc : ${TARGET}
	icpc -o "$@" "$<"

app-gcc : ${TARGET}
	g++ -o "$@" "$<"

clean :
	rm app-icc app-gcc