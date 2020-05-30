# AAA
This project is using POSTMAN to test against Dummy Rest API
The project itself uses newman to serve as a CLI for POSTMAN

Please go to https://www.npmjs.com/package/newman to install newman

Use the newman command and use endpoint.json as the dataprovider on the endpoint.
To run:
<code>newman run AAA.postman_collection.json -r cli,json -d endpoint.json</code>