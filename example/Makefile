all : echo_server echo_server_async http_server

echo_server :
	g++ -g -o echo_server echo_server.cpp -lbasemuduo -lpthread -std=c++11

echo_server_async :
	g++ -g -o echo_server_async echo_server_async.cpp -lbasemuduo -lpthread -std=c++11

http_server :
	g++ -g -o http_server http_server.cpp -lbasemuduo -lpthread -std=c++11

clean :
	rm -f echo_server echo_server_async http_server 