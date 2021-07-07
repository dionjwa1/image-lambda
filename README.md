# image-lambda
We used lambda as a trigger funcition to listen on our S3 file and trigger an event to push any new images into a specificed location.
Could not create code that caught new images uploaded to the S3 and then push into the image.json file. Also had trouble keeping the syntax consistent with the index and test files. 
https://s3.console.aws.amazon.com/s3/object/dions3?region=us-west-2&prefix=image.json