You can retrain tensorflow object detection api model:

https://towardsdatascience.com/how-to-train-your-own-object-detector-with-tensorflows-object-detector-api-bec72ecfe1d9
https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/configuring_jobs.md



dont forget to run this command in the root directory of project:
protoc object_detection/protos/*.proto --python_out=.
this compiles all the proto files in object_detection/protos into python