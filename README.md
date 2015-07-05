tftp_implementation
===================

tftp implementation in cplusplus

To run the program
type
g++ -o common.o -c common.cpp
g++ tftpserver.cpp -o t common.o
g++ tftpclient.cpp -o r common.o

./t
./r -r test.txt -- for reading
./r -w test.txt --for writing

./t portno ---> for running on specific port
./r -r test.txt portno

Group Members:
Rishabh Bhatia (12BCE1029)
Virat Sardana (12BCE1123)
