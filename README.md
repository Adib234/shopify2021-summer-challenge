# Usage

This is a Vue web app which has an image repository which you can hopefully search

# Things I learned

- Never built a RESTFUL API before so this is my first time, this helped me a [lot](https://levelup.gitconnected.com/how-to-build-a-restful-api-using-node-js-express-mongodb-1882a966726c)
- Since this isn't Ruby on Rails, you have to configure a lot of things like establishing the connection to MongoDB, and then setting up the middleware so that Express doesn't stop working, then setting up the model which specifies the structure of how data will be indexed, and then the controller which deals with how requests are being handled
- AWS is a pain in the butt, my advice is to just skim over anything thats recommended, and if you have found out what your are looking for then focus on that. Otherwise you are going to tire yourself out. Thank the lord for this [guide](https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/s3-example-photo-album.html)
- I just found out how to `this` in a callback. All you have to do is create a new variable for example `let self = this` and then use `self` from now on. Here's a [link](https://stackoverflow.com/questions/45743395/uncaught-in-promise-typeerror-cannot-set-property-of-undefined-with-axios) to my problem and here's an explanation of what's going [on](https://stackoverflow.com/questions/20279484/how-to-access-the-correct-this-inside-a-callback/20279485#20279485).
- For the love of god if you do any asychronous work like fetching from a resource do it don't try to wriggle out of it with synchronous code.

# To do

- ADD
  - Why cant i access my object url?
  - Figure out how to store mongodb id and amazon s3 id so retrieving the images becomes easy
  - How to add bulk images?

# Considerations

- Swagger.io
- JWT
- This [link](https://stackoverflow.com/questions/13175510/call-python-function-from-javascript-code) seems interesting if I want to create a Python image classifier and then can make an axios request to it
- [Image classifier](https://www.tensorflow.org/tutorials/images/classification)
- Bucket versioning?
