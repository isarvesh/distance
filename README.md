# City Distance API

![City Distance API](city-distance.png)

This project implements an API endpoint that accepts a pair of city names as input and returns the travel distance (not straight-line distance) between these cities, sub-cities, or localities.

## Expected Solution

You are expected to share a hosted, working GET endpoint and an API contract for the same.

## Additional Information

- Choice of backend stack is up to you.
- Additional points for building a front-end where you can enter the city names and it shows the distance. You can choose to host it locally and expose it via ngrok for testing.
- Feel free to use any free-tier hosting. Locally hosted endpoints are okay but not desirable.
- Feel free to integrate with any third-party maps provider to fetch this information.
- You would be judged on extensibility, modularity, and code quality.
- Code with test cases is a huge plus.

## API Endpoint

The API endpoint accepts a pair of city names as input and returns the distance between them.

### API Contract

- Endpoint: `/api/distance`
- Method: `GET`
- Request Parameters:
  - `city1`: The name of the first city
  - `city2`: The name of the second city
- Response Format: JSON
- Example Response:
  ```json
  {
    "distance": "1,080.7 km"
  }
  
### Getting Started
- Installation
- Clone the repository: git clone https://github.com/isarvesh/distance.git
- Navigate to the project directory: cd distance
- Install dependencies: npm install
- Start the development server: npm run dev

### Front-end
To test the API and view the distance between cities, you can visit the hosted front-end.

Hosted Front-end: https://distance-lemon.vercel.app/

License
This project is licensed under the MIT License.
