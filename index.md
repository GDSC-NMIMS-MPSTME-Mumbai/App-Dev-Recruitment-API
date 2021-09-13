![](https://i.ibb.co/wrK2B3q/download.png)
## API Documentation

### API Endpoints

1. Data: [https://gdsc-nmims-mpstme-mumbai.github.io/App-Dev-Recruitment-API/data.json](https://gdsc-nmims-mpstme-mumbai.github.io/App-Dev-Recruitment-API/data.json)
- This endpoint returns a list of JSON Objects, each of which represent a taxi trip and contain the following fields:
  - driverId - Id of the driver
  - customerId - Id of the customer
  - PUDatetime - pickup datetime
  - DODatetime - drop off datetime
  - passengers - number of passengers
  - tripDistance - distance coverd in that trip
  - PULocationId - Id of pickup location
  - DOLocationId - Id of drop off location
  - fare - fare for the trip
  - tax - tax charged
  - tip - tip given by customer

Example Object:

![data-snippet](https://i.ibb.co/BrK07y8/data-snippet.png)

2. Locations: [https://gdsc-nmims-mpstme-mumbai.github.io/App-Dev-Recruitment-API/locations.json](https://gdsc-nmims-mpstme-mumbai.github.io/App-Dev-Recruitment-API/locations.json)
- This endpoint return a list of Json Object, which represent locations and contain the following fields:
  - locationId - Id of the location
  - town - town
  - zone - zone

Example Object:

![location_snippet](https://i.ibb.co/PZtBS6q/location-snippet.png)


**You can use the mentioned URLs to access the API. These endpoints only support GET requests.**

