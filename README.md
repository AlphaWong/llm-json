# Objective
Standard of llm public api

# JSON schema version
Draft v4

# How it works
Go to http://www.jsonschemavalidator.net/

# Left panel
Copy & paste a.json

# Right panel
```json
{
  "scheduleAt": "2017-09-25T07:01:42.534Z",
  "serviceType": "MOTORCYCLE",
  "specialRequests": [
    "SAMPLE_A",
    "SAMPLE_B"
  ],
  "requesterContact": {
    "name": "Peter Pan",
    "phone": "+661252523435"
  },
  "stops": [
    {
      "location": {
        "lat": "13.7237389",
        "lng": "100.5272805"
      },
      "placeId": "",
      "addresses": {
        "th_TH": {
          "displayString": "Chong Nonsi Silom, Bangkok",
          "country": "TH"
        }
      }
    },
    {
      "location": {
        "lat": "13.740167",
        "lng": "100.535237"
      },
      "placeId": "",
      "addresses": {
        "th_TH": {
          "displayString": "Siam Pathum Wan, Bangkok",
          "country": "TH"
        }
      }
    }
  ],
  "deliveries": [
    {
      "toStop": 1,
      "toContact": {
        "name": "Peter Wong",
        "phone": "+66823445552"
      },
      "remarks": "XXXXX"
    }
  ],
  "paymentMethod": "CASH",
  "fleetPriority": "NONE"
}
```
