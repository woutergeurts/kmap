sudo apt-get install docker.io
sudo apt-get npm
npm install
npm start

Docker:
sudo docker build -t my_img .
sudo docker network create --subnet 172.20.0.0/16 --ip-range 172.20.240.0/20 wnet
sudo docker run -it --rm --name my_c my_img 
sudo docker network --ip 172.20.240.2 my_c
