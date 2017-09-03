# gSoapProject
Just for learning,no other aims at all.




1.Construct 2 FOLDERS named server and client
2.put soapcpp2.exe inside server folder,and cd /d to the server folder,then type the cmd: soapcpp2.exe add.h,then you get the above files except add.h which is added by youself.
3.Add.h with the following contents:
//gsoap ns service name: add  
//gsoap ns service namespace: http://localhost/add.wsdl  
//gsoap ns service location: http://localhost  
//gsoap ns service executable: add.cgi  
//gsoap ns service encoding: encoded  
//gsoap ns schema namespace: urn:add  
int ns__add(int num1, int num2, int* sum);
