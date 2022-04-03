Project instructions
Create a react project



Call the following API to get all locations

API: https://dev-api.confidence.org/v2/confidence/locations


Sample Request:



header:
Username:amitphatak$r5labs.com
body: { 
  "start":0, 
  "limit":10 
} 


Sample Response:



{
   "locations":[
      {
      "locationId":"ABBB0C49",
      "locationName":"Airbnb - Mountains",
      "locationDetails":"",
      "locationType":"Airbnb",
      "numberofTasks":10,
      "numberofMyTasks":10,
      "numberofDevices":0,
      "address":{
            "addressLine1":"5600 3rd Street",
            "city":"San Francisco",
            "state":"CA",
            "zip":"94124"
      },
      "locationUserRole":"Member",
      "active":true,
      "subscriptionActive":true
      },
      {
"locationId":"GOVG57YG",
"locationName":"Govt Offices",
"locationDetails":"",
"locationType":"Government",
"numberofTasks":1,
"numberofMyTasks":1,
"numberofDevices":0,
"address":{
      "addressLine1":"425 1st Street",
      "city":"San Francisco",
      "state":"CA",
      "zip":"94105"
},
"locationUserRole":"Member",
"active":true,
"subscriptionActive":true
},
{
"locationId":"BUSBMJFT",
"locationName":"SRP Restaurant",
"locationDetails":"Restaurant 1",
"locationType":"Business",
"numberofTasks":1,
"numberofMyTasks":1,
"numberofDevices":0,
"address":{
      "addressLine1":"233 Franklin Street",
      "city":"San Francisco",
      "state":"CA",
      "zip":"94102"
},
"locationUserRole":"Manager",
"active":true,
"subscriptionActive":true
},
{
"locationId":"SCHGU4YS",
"locationName":"Graham",
"locationDetails":"Graham Middle school",
"locationType":"School",
"numberofTasks":5,
"numberofMyTasks":5,
"numberofDevices":0,
"address":{
      "addressLine1":"1175 Castro Street",
      "city":"Mountain View",
      "state":"CA",
      "zip":"94040"
},
"locationUserRole":"Member",
"active":true,
"subscriptionActive":true
},
{
"locationId":"BUSLCHXM",
"locationName":"San Mateo Business",
"locationDetails":"shailaja's Workspace",
"locationType":"Business",
"numberofTasks":0,
"numberofMyTasks":0,
"numberofDevices":0,
"address":{
      "addressLine1":"3428 16th Street",
      "city":"San Francisco",
      "state":"CA",
      "zip":"94114"
},
"locationUserRole":"Member",
"active":true,
"subscriptionActive":true
},
{
"locationId":"OFFV55VJ",
"locationName":"Health Club Title 1",
"locationDetails":"Health Club ",
"locationType":"Office",
"numberofTasks":4,
"numberofMyTasks":4,
"numberofDevices":0,
"address":{
      "addressLine1":"432 Octavia Street",
      "city":"San Francisco",
      "state":"CA",
      "zip":"94102"
},
"locationUserRole":"Member",
"active":true,
      "subscriptionActive":true
      }
], 

   "numberOfLocations":6
}


Create a simple web page that displays the list of locations. For each location display following for each location

Location Details
Address
Location Type


Display only 3 locations on each page and as the user scrolls display the next set of 3 locations



Results package to upload on GithHub repo
The page should be simple HTML

Write unit tests for the implementation 

Screenshots/Video of the locations page running on your local machine

Execute tests and take a screenshot of the test.



Please include instructions on how to run the application in your README.md



How to submit
Upload your completed project to your GitHub, and then paste a link to the repository below in the form along with any comments you have about your solution.