# sagemaker_docker
Code for building and deploying Custom ML Models on Amazon Sage Maker using Docker.


Steps :- 
1. On terminal,run "docker build -t custom_tag_name ." --> To build the docker image.
2. Run "docker images" --> To check if the built image is running or not.
3. Run "docker run --rm -v $(pwd)/local_test/test_dir:/opt/ml custom_tag_name train" --> To train your model and save weights in required folder in pickle format. 
