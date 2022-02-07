# API test tips
## Postman usage
     - Param is different with Body
     - If meet the situation that first need to do something in another site and then do in the test site, we can use the Pre-request Script. like some applications need login first, so we can put the login part(or get the token) in the Pre-request part
     - If meet the error code 422, not only check the key/values, but also the cookies. we can compare with the Fiddler package result
     - raw format have text/Json/xml/JS...