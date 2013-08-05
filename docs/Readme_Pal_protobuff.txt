protobuff:

download and install protobuff compiler from
https://code.google.com/p/protobuf/downloads/list

for mac version, download the source zip or tar file and install with following steps

$ ./configure
$ make
$ make check
$ make install

----------------------------------------------------------------------------------------------
java files creation from proto files using protoc compiler:


1. navigate to /src/main directory (/Users/palani/git/google-protobuff/src/main)

2. protoc -I=resources/proto-files --java_out=java resources/proto-files/*.proto [this assumes that protoc is in the path]

--
protoc -I=resources/proto-files --java_out=java resources/proto-files/*.proto
----------------------------------------------------------------------------------------------
protoc command format:
protoc -I=$SRC_DIR --java_out=$DST_DIR $SRC_DIR/addressbook.proto

----------------------------------------------------------------------------------------------


