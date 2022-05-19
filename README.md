This is final project of Docker and kubernetes. by this project you can deploy an flask application with mysql database on your docker environment with docker-compose command. To run the application please follow below instructions.

- Install Docker desktop from below address
	https://www.docker.com/products/docker-desktop/
	you can find installation instruction from below address
	https://docs.docker.com/desktop/windows/install/
- download application and extract any places that you want (for example d:\LabafProject)
- execute powershell as Administrator or open your shell
- move to project folder (cd d:\LabafProject)
- execute below command
	docker-compose up --build -d --force-recreate
- open your browser for address 127.0.0.1:50000 and enjoy the flask application on docker
- if you want to conect mysql database, open address 127.0.0.1:30000 on the browser.


