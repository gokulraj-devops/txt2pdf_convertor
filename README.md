This is docker project. Its is used to convert the txt file to pdf file. using python.

install and following steps,

1. Clone the repo.
2. Open the ps to check below command,
3.     docker --version
4. Please check the docker version and install.
5. Use the below command to convert the config file to image 
6.     docker build -t "your iamge name:tag name"
7. Note : the clone file path please check at your end.
8.  After changed the image using below command to craete container,
9.      docker run -d --name docker -d --name Container-name -v "Source_path\SOURCE:/app/source" -v "Destinatio_path\DESTINATION:/app/destination" image-name 
10. Note : before convert the container create 2 folder for source and destination
11. txt file place the source path the pdf file converted in destination path.
12. Thanks you
