OBJS :=  MD5.o CString.o CXKUsername.o dail.o
CC := g++   

netkepper:ooo
	$(CC) $(OBJS) -static -lws2_32 -lrasapi32 -lWininet -o dial 

ooo:
	$(CC) -c MD5.cpp 
	$(CC) -c CString.cpp
	$(CC) -c CXKUsername.cpp
	$(CC) -c dail.cpp


