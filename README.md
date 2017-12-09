# jdscraper.py
## A simple Python(3.5.2) script to extract data from the website justdial.com

### It's against justdial's "terms of use" to scrape data from their website. This script is to be strictly used for educational purposes.
<br />

## Libraries used:
- [bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [requests](http://docs.python-requests.org/en/master/)
- [sys](https://docs.python.org/2/library/sys.html)
- [pyperclip](https://media.readthedocs.org/pdf/pyperclip/latest/pyperclip.pdf)
- [csv](https://docs.python.org/3.5/library/csv.html)

### All the above libraries are required to run the script.
#### All the libraries comes pre-installed with Python 3, except for ```bs4``` and ```pyperclip```

<br/>

## Usage Illustration 
- Download the script
- Run the script from the command line with the appropriate url as an argument
```
python jdscraper.py https://www.justdial.com/Kolkata/Event-Organisers/nct-10194150
```
The "appropriate url" is url of a web page of the following form:

![alt text](img/1.png "'appropriate url' webpage screenshot")

- Relax and wait for the script to complete the extraction.

## Distinguished Features
- Scrapes 'Name', 'Address', 'Contact' and 'Rating' of the various organisations.
- Saves the extracted data in a csv file.
