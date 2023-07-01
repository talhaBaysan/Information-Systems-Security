server: server.c
	gcc server.c -o server -fno-stack-protector -z execstack -no-pie -m32
	sudo chown root:root server
	sudo chmod 4655 server