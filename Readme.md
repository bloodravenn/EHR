#EHR

sudo apt update
sudo apt install docker.io
sudo systemctl enable docker
sudo systemctl start docker

git clone https://github.com/ozone-his/ozone-docker
cd ozone-docker
./start-demo.sh
