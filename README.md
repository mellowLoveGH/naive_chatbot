# naive_chatbot
use python to access location by geopy, weather by pyowm, and chatbot by api.wit.ai

access weather, temperature and nearby attractions data by latitude and longitude, or by a name (city name) 
python
用python访问天气，温度和附近的经典的代码

you should run this code after applying 2 keys
在运行此代码之前你需要申请两个调用API的key
https://home.openweathermap.org/api_keys
&
https://developer.here.com

Do not forget to install realtive packages
不要忘记安装相关的库函数

!pip install pyowm 


files:

geoinfo.py, using GOOGLE geo package to obtain the geographical information such as weather, temperature and so on.

test_report.py & unit_test.py, using unit test to do unit testing.

translate_01.ipynb, using Bing / google translate api to do online translation, & wikipedia api to do online definition search.

POS_tagging_NER_sentiment_analysis.ipynb, using the Standford package & NLTK to do POS-tagging (part of speech), name entity recognition & sentiment analysis.

posTag_spellCheck.py, it is the python code from 'POS_tagging_NER_sentiment_analysis.ipynb', with spelling checking functions.
