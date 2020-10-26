## Self Hosted Analytic Tool `Ackee`
Self-hosted, Node.js based analytics tool
[Ackee](https://github.com/electerious/Ackee)

![Ackee](/img/ackee.png)

### Step 1: `docker-compose up`


### Step 2: Import domains data
Import `domains.json` into db

```json
{
  "_id": {
    "$oid": "5f95b750dbce3b003e36028b"
  },
  "title": "reactapp",
  "id": "ea2518be-c4da-404f-af2e-4fcec83e01cf",
  "created": {
    "$date": {
      "$numberLong": "1603647312348"
    }
  },
  "updated": {
    "$date": {
      "$numberLong": "1603647312348"
    }
  },
  "__v": {
    "$numberInt": "0"
  }
}
```

### Step 3: Access reactjs app
`http://localhost:3000/` 

![Ackee](/img/reactapp.png)

### Step 4: Access ackee app
`http://localhost:5000/` 

use admin:admin for signin

 - Install CORS plugin into browser to enable cross origin request on localhost [CORS Plugin](https://chrome.google.com/webstore/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf?hl=en)
 - For more domains goto settings and add a new domain and keep domain id i.e. 
  `ea2518be-c4da-404f-af2e-4fcec83e01cf`
