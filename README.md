# Labs 17 401

## Image Lambda

Repo for 401 lambda assignment, code on lambda

### Author: Mike Pace

### Links and Resources

-[Repo](https://github.com/catdude2000/image-lambda)  

### Collaborators  

Sara Russert

#### Running the app

clone repo  

#### Tests

Unit Tests: npm test

#### My Journey

A description of how to use your lambda.  
When you upload images to my awslab17 bucket, the lambda kicks in and writes a record of name, type, and size to the images.json file.  

a description of any issues you encountered during deployment of this lambda.
I had issues creating the bucket, as I didn't like my first one so I emptied it and then couldn't (and still can't) delete it.  After getting the code 99% done I had trouble getting the json file to show anything besides what was already in the index file.  Turned out one of my s3's had a capital S and needed a lower case.  

a link to your images.json file.  
<https://awslab17.s3.us-east-2.amazonaws.com/images2.json>  
