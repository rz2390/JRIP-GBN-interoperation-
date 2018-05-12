four commands for running jrip function
./jrip5 -l 0.1 -p 7999 160.39.245.46:8000:2 160.39.245.46:8001:3
./jrip5 -l 0.1 -p 8000 160.39.245.46:7999:2 160.39.245.46:8001:1 160.39.245.46:8002:9
./jrip5 -l 0.1 -p 8001 160.39.245.46:7999:3 160.39.245.46:8000:1 160.39.245.46:8002:6
./jrip5 -l 0.1 -p 8002 160.39.245.46:8001:6 160.39.245.46:8000:9 35.185.116.250:8111:1 35.185.116.250:8112:2 35.185.116.250:8113:1

one command for running jtraceroute function
./jrip45 -p 4321 160.39.245.46:7999 123.1.1.2:1010

Notice: the 160.39.245.45 was my external ip obtained via gethostbyname() or by iconfig. Here if you want to run the code, please replace them with your external ip.