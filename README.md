# tesla-mate
Installing TeslaMate on AWS EC2 or LightSail
- Create instance and open ports *80*, *443*, *3000*, and *4000*

- Fetch and run the setup script
    - `wget https://raw.githubusercontent.com/wmaciel/tesla-mate/master/script.sh`
    - `chmod +x script.sh`
    - `./script.sh`

- Modify `.env` file if needed *(Optional)*
    - `cd tesla-mate`
    - `vim .env`

- Reboot and start docker daemon: 
    - `sudo reboot`
    - `sudo service docker start`

- Start TeslaMate: (must be on same dir as the docker-compose file)
    - `docker-compose up`
