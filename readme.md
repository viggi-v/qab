# Steps

ssh to the new gpu instance

execute all commands in https://gist.github.com/viggi-v/627e4b3c6bf42a9b89a5770abca257be

close the connection.

scp the files in Downloads/gcloud to the gpu instance using
	scp -r Downloads/gcloud/* rajmehta2811@<IP ADDRESS>:~/qab/model_pickles/
then try ssh to the instance, and go to qab
	python train.py