### Forum Api using Go,Gin and Gorm 
* Copy .env.example file as .env ```cp .env.example .env``` 
* Run specific test ```go test -v --run TestDeletePost``` 
* Run all test ```go test -v``` 
* Run all test recursively ```go test -v ./...``` 

* Run application ```docker-compose up``` 
* Run application as daemon ```docker-compose up -d``` 
* Run all test at docker ```docker-compose -f docker-compose.test.yml up --build --abort-on-container-exit``` 
* Stop docker container ```docker-compose down``` 
* Remove docker container and volumes  ```docker-compose down --remove-orphans --volumes``` 
* Remove unused images  ```docker system prune -a``` 