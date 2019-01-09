# Simplified dockerized laravel application

## How to Install

- Download and install docker in your system. [Download here](https://www.docker.com/get-started)

- Fork this project and clone in your system. Current version of laravel is 5.7.x

- Move to the root folder and run `docker-compose up -d`

- Open your browser and go to [http://localhost:81](http://localhost:81)

- Enjoy!

## FAQ

- Why port 81?
  - Sometimes you want your backend and frontend separated. You can have your frontend runs in the default `:80` and the API to be in port `:81`
  
- Can we change this port?
  - Yes. You can change the port in the webserver block of the `docker-compose.yml` file
  
- Is everything customizable?
  - Yes. You can fiddle the `docker-compose.yml` file and make your own customization. Be sure you know what you are doing.
  
  
  
# Author
[Jeff Simons Decena](https://jsdecena.me)