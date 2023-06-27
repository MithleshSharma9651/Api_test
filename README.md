# Api_test
API test on Weather Map API
tests["ResponseCode"]=responseCode.code=200
tests["LondonCheck"]=responseBody.has("London")

var response=JSON.parse(responseBody)
tests["longitude"]=responseBody.lon=-0.3
tests["latititude"]=responseBody.lat=51.51

tests["id_check"]=responseBody.id=2643743
