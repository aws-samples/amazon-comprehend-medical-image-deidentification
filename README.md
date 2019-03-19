## De-identify medical images with the help of Amazon Comprehend Medical and Amazon Rekognition

This repository provides Python code to use Amazon Rekognition to extract text from images and Amazon Comprehend Medical to help us to identify and detect the PHI.  After the PHI is detected it is then redacted.   All of the image files will be read from and written to a bucket in Amazon Simple Storage Service (Amazon S3), an object storage service that offers industry-leading scalability, data availability, security, and performance.

![diagram](https://github.com/aws-samples/amazon-comprehend-medical-image-deidentification/raw/master/images/deidentify-medical-1.gif)

## License

This library is licensed under the Apache 2.0 License. 
