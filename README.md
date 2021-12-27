# CouchBase

curl -v http://54.198.182.212:8093/query/service \
  -u ashish:ashish \
  -d 'statement=SELECT meta().id
      FROM `travel-sample`.inventory.hotel
      WHERE meta().id LIKE $1 &args=["hotel_1002%25"]'
	  

curl -v http://54.198.182.212:8093/query/service \
  -u ashish:ashish \
  -d 'statement=SELECT *
      FROM `travel-sample`.inventory.hotel
      WHERE meta().id LIKE $1 &args=["hotel_1002%25"]'

############### 20-OCT ##################
	  
curl -v http://54.89.14.49:8093/query/service \
  -u ashish:ashish \
  -d 'statement=SELECT meta().id
      FROM `travel-sample`.inventory.hotel
      WHERE meta().id LIKE $1 &args=["hotel_1002%25"]'
	  
curl -v http://54.89.14.49:8093/query/service \
  -u ashish:ashish \
  -d 'statement=DELETE FROM `travel-sample`.inventory.hotel
      WHERE meta().id LIKE $1 &args=["hotel_1002%25"]'
	  
curl -v http://54.89.14.49:8093/query/service \
  -u ashish:ashish \
  -d 'statement=SELECT meta().id
      FROM `travel-sample`.inventory.hotel
      WHERE meta().id LIKE $1 &args=["10226"]'
	  
	  
	  
