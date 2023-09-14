# SpamClassifier
Spam/Ham Classifier Api using FastApi/Docker 


## Want to use this project?

Build the images and run the containers:

```sh
$ docker build . -t fastapi-spam-classifier:latest
$ docker run --rm -it -p 8000:8000 --user=42420:42420 fastapi-spam-classifier:latest
```

Test out the following routes:

1. [http://0.0.0.0:8000/docs](http://0.0.0.0:8000/docs)
1. [http://0.0.0.0:8000/spam_detection_path](http://0.0.0.0:8000/spam_detection_path)
