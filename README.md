# CST8915 Lab 2: Algonquin Pet Store Four Factors

**Student Name**: Eric Tieu
**Student ID**: 041273376
**Course**: CST8915 Full-stack Cloud-native Development
**Semester**: Fall 2026

---

## Demo Video

🎥 [Watch Demo Video](https://www.youtube.com/watch?v=3-h5xMdKDA4)

---

## Technical Explanations

### Order Service [Link](https://github.com/tieu0014/order-service)
What changes did you make to the order-service to comply with the Configurations and Backing Services factors of the 12-Factor App methodology?
<br>
The first change was to move the service to a single code base, by moving each service to their own GitHub repo. The second factor was declaring and isolating dependencies, this was already done in the updated lab. The third change was to store the configuration in the environment, files with hard coded configurations were updated with files from the lab 2 repo. A '.env' file was created to store environment variables that the updated files could use.

### Product Service [Link](https://github.com/tieu0014/product-service)
What changes did you make to the product-service to comply with the Configurations and Backing Services factors of the 12-Factor App methodology?
<br>
(Same as Order Service)The first change was to move the service to a single code base, by moving each service to their own GitHub repo. The second factor was declaring and isolating dependencies, this was already done in the updated lab. The third change was to store the configuration in the environment, files with hard coded configurations were updated with files from the lab 2 repo. A '.env' file was created to store environment variables that the updated files could use.

### Store Front [Link](https://github.com/tieu0014/store-front)

### Environment Variables
Why is it important to use environment variables instead of hard-coding configurations in your application?
<br>
"It ensures separation between the code and the configuration for better portability and security"

### Separate Repositories
Why is it important to have separate repositories for each microservice? How does this help maintain independence and scalability of each service?
<br>
"Each service can be deployed separately without having to deploy the entire system", "changes in one service will have minimal or no impact on other services". Possibly multiple instances of of the microservice can be deployed at a time, allowing it to scale with the number of instances.
