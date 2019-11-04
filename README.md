# Docker
How to create AWS server

-Create account and find "EC2" 
![Annotation 2019-11-04 023327](https://user-images.githubusercontent.com/22506281/68114694-82de9a00-feab-11e9-8ac1-90268d74e282.png)


-Click "Launch Instance"
![Annotation 2019-11-04 022439](https://user-images.githubusercontent.com/22506281/68114510-0b106f80-feab-11e9-9c6e-cdd1f05051ab.png)

-Select Ubuntu
![Annotation 2019-11-04 023158](https://user-images.githubusercontent.com/22506281/68114608-4ca11a80-feab-11e9-8842-c58774b447f8.png)

-Start
![Annotation 2019-11-04 023550](https://user-images.githubusercontent.com/22506281/68114843-de108c80-feab-11e9-9bf2-ac118da98850.png)

-Create a key pair and download it to start it

-Go to property of the key, security
-Advanced -> Click "Disable Inheritance"
-Remove everything except "Administrators" and "System"

-Go to file directory where the key is on terminal
 ex) D:\>cd Docker
 
 -Click connect and copy the command "ssh -i....."
 ![Annotation 2019-11-04 024118](https://user-images.githubusercontent.com/22506281/68115166-9cccac80-feac-11e9-85fa-349d62a26365.png)

-Copy and paste it and type it on terminal to use server 
