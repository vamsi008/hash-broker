# hash-broker
hashmap broker

To create the service-broker i am using

cf create-service-broker haash-broker admin admin https://haash-broker.local.pcfdev.io


where i have changes the credentials to username::admin
                                        password:admin
                                        
But I am gettign an exception while binding the service to the client. The exception is ::

Error: Server error, status code: 502, error code: 10001, message: The service broker rejected the request to https://haash-broker.local.pcfdev.io/v2/service_instances/3c26545a-3fa2-424c-8c91-135414417820/service_bindings/734e9787-fe35-45cc-a530-38d65c0d4fec. Status Code: 400 Bad Request, Body: {"timestamp":1482698202368,"error":"Bad Request","status":400,"message":""}

                                     
