Install Colima in Macos
1. brew install colima docker docker-compose.
2. Start colima, and allow it outbound internet access: $ colima start --network-address --dns 8.8.8.8 --dns 1.1.1.1
3. Rebuild your images, and start them.
4. Check your system status $ docker ps
Docker ps 
Docker build .  Or   -f “” .
Docker images ls
docker pull grafana/loki:main
docker run -d -it 9a036fb1a037 
docker exec -it b10574f871e2 sh
docker rm $(docker ps -a -f status=exited -q)
docker rmi $(docker images -a -q)

alias docker-compose='docker run --rm -v /var/run/docker.sock:/var/run/docker.sock -v "$PWD:$PWD" -w="$PWD" docker/compose:1.27.4'  // Run docker compose  in lightweigh OS(Alphine)
