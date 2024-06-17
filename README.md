# User Registration and Fetch API

## Requirements

- Java 11
- Maven

## How to Run

1. Clone the repository.
2. Navigate to the project directory.
3. Run `mvn spring-boot:run`.

## Endpoints

### Register User

- **URL**: `/api/user/register`
- **Method**: `POST`
- **Content-Type**: `application/json`
- **Body**:
  ```json
  {
      "username": "john",
      "email": "john@example.com",
      "password": "password"
  }

 ### Fetch User
- **URL**: `/api/user/fetch`
- **Method**: `GET`
- **Query Parameter**: `username`
  http://localhost:8080/api/user/fetch?username=john

