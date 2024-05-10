to build docker image:
docker build -t ace346/weather:01 .

to push to/pull from docker hub:
sudo docker push/pull ace346/weatehr:{tag}

to connect to ec2: 
ssh -i "weather-02.pem" ec2-user@ec2-54-162-57-19.compute-1.amazonaws.com

to run docker image:
docker run -p 80:80 {image}