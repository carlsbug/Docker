1. sudo apt-get update  
2. python3 (to check if you have it)
3. sudo apt-get install python3-pip
4. sudo pip3 install notebook (it's jupyter)
5. python3
6. >>> from notebook.auth import passwd (library)
7. >>> passwd() (to set passwd and get the hash value)
8. copy the hash value and type exit()
9. jupyter notebook --generate-config (create preference file and you will get the dir)
10.sudo vi /home/ubuntu/.jupyter/jupyter_notebook_config.py
11.scroll down to go to bottom(shift + down arrow)
12.click 'a' to --INSERT--
13. put hash value that you copied after u'sha1:
![Annotation 2019-11-04 030106](https://user-images.githubusercontent.com/22506281/68116325-617fad00-feaf-11e9-843d-7ec813fb30f6.png)
14.click ESC and type :wq! to save it
15.sudo jupyter-notebook --allow-root (run it)
16.Go to the AWS site and click this
![Annotation 2019-11-04 030354](https://user-images.githubusercontent.com/22506281/68116459-bfac9000-feaf-11e9-9a72-11102b159ad6.png)
17.Click Inbound and edit
![Annotation 2019-11-04 030446](https://user-images.githubusercontent.com/22506281/68116516-e1a61280-feaf-11e9-90a1-d281a136bb50.png)
18.Click Add rule and put 8888(open to public) and 0.0.0.0/0
![Annotation 2019-11-04 030800](https://user-images.githubusercontent.com/22506281/68116696-52e5c580-feb0-11e9-8e46-66c8fb95d4ad.png)
19.Go to EC2 Dashboard and click Running instance and find IPv4 Public IP
20.Type that IP and add :8888
 

