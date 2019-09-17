# lambda-functions

- A user should be able to upload an image at any size, and have both the original size and a thumbnail size associated with the task in question.
  When an image is uploaded to your S3 bucket, it should trigger a Lambda function. (That Lambda function may be written in any language.)

- That function should create a 50x50 pixel thumbnail version of that image, and save it to another S3 bucket. It should do so with a predictable naming convention, so that your server and/or frontend know where that thumbnail image will be.

## Collaborators:

- Jane Hur
- Nhu Trinh
- Bombibear
- Jack Kinne
- Matt Stuhring
- Padma Ganapathi

- special guest star: Melfi Perez
