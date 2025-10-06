# scr4py_3tsy

## Description:
Hi guys. In this respository, I use Scrapy to crawl from www.etsy.com.
Please feel free to clone and experiment on it. 

## How - to install:
### For novices like me:
1. Clone this repository.
2. Create your working environment.
3. Inside your working environment, please create your own virtual environment because ***dependencies might messes up with your local environment***: 

`python -m venv scrapy_venv`

* in windows: 

`scrapy_venv\Scripts\activate.bat`

* in linux/unix: 

`source scrapy_venv\bin\activate`

3. Install dependencies:

`pip install -r requirements.txt`

4. Add *environtment variables*: Please explicitly include this inside your machine or the code will be broken.

* ***SCRAPY_USEREMAIL***: Your **gmail** address.
* ***SCRAPY_USERPASS***: Your app-password. You can enable the less secure app password following these steps:
    
    Go to your Google Account settings.
    Click on the Security tab.
    Scroll down to the Less secure app access section.
    Click on the Turn on access button.

* ***SCRAPY_DEFAULT_RECIPIENT***: When you do not state the specific recipient. The email result will be sent to this address.

5. For running:

`python app.py`

5. Users input: 

`Please insert `

5. Et voila

### For pros:
Welp, 
> if you know, you know