OBJS1 = cswu/Common.o cswu/Table.o cswu/Seq.o cswu/Map.o cswu/Sam.o
Objects1: ${OBJS1}
	g++ -c -o cswu/IsInList.o cswu/IsInList.cpp
	g++ -c -o RemoveInList.o Tools/RemoveInList/RemoveInList.cpp 
	g++ -c -o RetainInList.o Tools/RetainInList/RetainInList.cpp 
	g++ -c -o SeqOut.o Tools/SeqOut/SeqOut.cpp 
	g++ -c -o 3pParser.o Tools/3pParser.cpp 
	g++ -c -o BlatCoverCut.o Tools/BlatCoverCut.cpp 
	g++ -c -o BlatFindCoLinear.o Tools/BlatFindCoLinear.cpp 
	g++ -c -o CountName.o Tools/CountName.cpp 
	g++ -c -o FastqOut.o Tools/FastqOut.cpp 
	g++ -c -o RmAmbiMapping.o Tools/RmAmbiMapping.cpp 
	g++ -c -o RmLowComplexReads.o Tools/RmLowComplexReads.cpp 
	g++ -c -o SeqRm.o Tools/SeqRm.cpp 
	g++ -c -o TSscanSamParser.CS50.o Tools/TSscanSamParser.CS50.cpp 
	g++ -c -o TSscanSamParser.NT.o Tools/TSscanSamParser.NT.cpp 
	g++ -c -fopenmp -o TSscan1of4.o TSscan1of4.cpp 
	g++ -c -o TSscan2of4.o TSscan2of4.cpp 
	g++ -c -o TSscan3of4.o TSscan3of4.cpp 
	g++ -c -o TSscan4of4.o TSscan4of4.cpp 
	g++ ${OBJS1} RemoveInList.o -o RemoveInList
	g++ ${OBJS1} RetainInList.o -o RetainInList
	g++ ${OBJS1} BlatCoverCut.o -o BlatCoverCut
	g++ ${OBJS1} BlatFindCoLinear.o -o BlatFindCoLinear
	g++ ${OBJS1} CountName.o -o CountName
	g++ ${OBJS1} RmAmbiMapping.o -o RmAmbiMapping
	g++ ${OBJS1} RmLowComplexReads.o -o RmLowComplexReads
	g++ ${OBJS1} SeqRm.o -o SeqRm
	g++ cswu/Common.o cswu/Table.o cswu/Seq.o cswu/IsInList.o cswu/Sam.o SeqOut.o -o SeqOut
	g++ cswu/Common.o cswu/Table.o cswu/Seq.o cswu/IsInList.o cswu/Sam.o FastqOut.o -o FastqOut
	g++ cswu/Common.o cswu/Table.o cswu/Seq.o cswu/IsInList.o cswu/Sam.o TSscanSamParser.CS50.o -o TSscanSamParser.CS50
	g++ cswu/Common.o cswu/Table.o cswu/Seq.o cswu/IsInList.o cswu/Sam.o TSscanSamParser.NT.o -o TSscanSamParser.NT
	g++ -fopenmp TSscan1of4.o -o TSscan1of4
	g++ TSscan2of4.o -o TSscan2of4
	g++ TSscan3of4.o -o TSscan3of4
	g++ TSscan4of4.o -o TSscan4of4

