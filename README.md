# Deep Hedging Cryptocurrency Options 
By Rachel Swallow
## About 
This project is undertaken as part of the minor dissertation component of the MSc Data Sceince in Financial Markets at UCT. The project stems from work completed by H.Buehler et al in their landmark paper "Deep Hedging". This dissertation will focus on using Deep Hedging to hedge Cryptocurrency options (namely European style call options written on Bitcoin). This project aims to be entirely reproducable, hence the use of virtual machines and docker images. 

## About Docker 

A docker image has been created so the research is entirely reproducable on any machine. A Docker container can be seen as a computer inside your computer. The  virtual computer can be sent and used so when anyone runs your code they will get exactly the same results as you did.

For this thesis I'm using docker as it allows me to wrangle dependancies (from the opperating system up to python and library versions) and it makes sure my analyses are reproducable. It also make sure this code is portable so I can run it on a more powerful machine if necessary. 

Some basic vocabulary for those that are new to docker: An image is a setup of a virtual machine, if you run this image then you have an instance of it - this is called a container. You can have multiple containers of the same image running simulataniously. 

Steps to use Docker : 
1. Download docker at https://www.docker.com/products/docker-desktop as well as Visual Studio Code. 
2. Next, we will ask Docker to run the image created for this project - it contains all the necessary packages needed for analysis.

To use docker image type the below in your VS terminal.
'docker run --rm -p 8787:8787 -e PASSWORD=12345 rswallow/thesis_image' in your VS terminal. Alternativley you can press 'run' on the appropriate image name if you have cloned this repo and built the docker file using "docker build -t thesis_image"


## Usage 


## References 
H. Buehler, L. Gonon, J. Teichmann & B. Wood (2019) Deep hedging, Quantitative Finance, 19:8, 1271-1291, DOI: 10.1080/14697688.2019.1571683