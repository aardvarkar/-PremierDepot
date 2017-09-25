sources = carre.cpp
headers = qcustomplot.h
objets = $(sources : .cpp=.o)

CourbeCarre : carre.o
	g++ $^ -o $@ -l QtGui -l QtCore -L /net/cremi/arohan/prograC/compilation3/TP1/qcustomplot/sharedlib/compilation/ -l qcustomplot

carre.o : carre.cpp
	g++  -c $^ -o $@ -I /usr/include/qt4/QtGui/ -I /usr/include/qt4/ -I /usr/include/qt4/QtCore/ -I /net/cremi/arohan/prograC/compilation3/TP1/qcustomplot/
