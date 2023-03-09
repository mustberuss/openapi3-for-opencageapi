# The OpenApi/Swagger 3 definition of the OpenCage Geocoding API

I'm not sure the OpenCage people are as excited about OpenAPI/Swagger as they should be so I created this repo and stood up the Swagger UI page for their API.  OpenCage already provides a [version 2 Swagger definition](https://opencagedata.com/api#openapi) for their API.  All I did was convert it to OpenAPI/Swagger 3 using the online converter mentioned [here](https://github.com/LucyBot-Inc/api-spec-converter).  

## Fun things to do

* Try out the [OpenCage Swagger UI page](https://mustberuss.github.io/openapi3-for-opencageapi/) - it's like Postman online, pre-loaded to work with the OpenCage Geocoding API.
  
*   Open the OpenAPI 3 swagger definition in the online editor
   1 Go to https://editor.swagger.io/
   2 File -> Import URL : https://mustberuss.github.io/openapi3-for-opencageapi/opencagedata3.yaml

    Especially fun to then generate clients via the Generate Client menu for anything not already mentioned on the [OpenCage SDK page](https://opencagedata.com/sdks)

  * Look at all the fun open source projects that take an API's Swagger 2 or OpenAPI/Swagger 3 definition as inputs to do amazing things.  See https://openapi.tools/
  * Read the [article](http://patentsview.historicip.com/swagger/articles/) I wrote about using Swagger/OpenAPI with the patentsview API (I'm a contributor to the API's R package).
  * Read about the [fun things](http://patentsview.historicip.com/feedback2.htm) I've done with the geolocation data provided in bulk by the patentview API team.  
  
Note that it's useful to have both versions around, some open source projects only work for a specific version (ex: [rapiclient](https://github.com/bergant/rapiclient/issues/17) for R reads only Swagger 2 definitions).
