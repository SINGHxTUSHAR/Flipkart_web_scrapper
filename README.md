# Flipkart_web_scrapper

This is a web scrapper project which will show the reviews given by the people on Flipkart for entered items. you can enter the item on the search page and will get the reviews on result page.

Link for the API : https://blue-hairdresser-qlwgf.pwskills.app:5000/

Modules that we have used in our API with Flask framework are : 

1. from flask import Flask, render_template, request,jsonify     
2. from flask_cors import CORS,cross_origin     
3. import requests      
4. from bs4 import BeautifulSoup as bs      
5. from urllib.request import urlopen as uReq      
6. import logging         
7. logging.basicConfig(filename="scrapper.log" , level=logging.INFO)    

The structure is designed by using HTML and CSS :              
1.index.html: This contains the search page              
2.result.html: This contains the final output or the information fetched from Flipkart about the entered item      
3.main.css and style.css : These files are used in designing part for the UI used in API.



We are also logging the information in our scrapper.log file, for this we have use the logging module and level is set to INFO.


Screenshots : 
![ss1](https://github.com/SINGHxTUSHAR/Flipkart_web_scrapper/assets/113624520/f34c7105-dc67-4787-bee4-6d6f03e7d13c)

![ss3](https://github.com/SINGHxTUSHAR/Flipkart_web_scrapper/assets/113624520/d77cfb43-6464-4b0f-acb5-f06b0b426f46)

![ss2](https://github.com/SINGHxTUSHAR/Flipkart_web_scrapper/assets/113624520/88eb6073-e62c-4f2c-a962-63774017f545)


we can also push the data to our database using MongoDB, the code for that is given in the app_Mongodb file.











