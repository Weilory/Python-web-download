<h1>Python School Info Web Scrapper</h1>
<hr />

![exp](https://github.com/Weilory/python-school-info-web-srapper/blob/master/docs/gif/exp.gif)

<br />
Scrape <b>Top 100 High Schools Information of New York State U.S</b>, illustrate with a properly formated Microsoft Word document (docx)
<br /><br />
<h1>Requirements</h1>
<hr />
<ol><u>Software Requirements</u>
  <li>Selenium</li>
</ol>
<ol><u>Packages Requirements</u>
  <li>selenium</li>
  <li>openpyxl</li>
  <li>scipy</li>
  <li>numpy</li>
  <li>matplotlib</li>
  <li>docx</li>
  <li>python-docx</li>
</ol>
<br /><br />
<h1>Usage</h1>
<hr />
<ol>
 <li>Create a new docx file, anywhere on your computer, double click to open it with MS Word, write some stuff, press ctrl+s, delete what you have written, press ctrl+s, close docx</li>
 <li>open `main.py`, change `chromedriver()` to your own chromedriver path</li>
 <li>in `main.py`, change path of docx to the <b>absolute path of </b> the file that you created</li>
 <li>change the range of the list between [0:99], in other words, select a range the schools you want to scrape</li>
 <li>run `main.py`, you will see chrome being controled by the software and scrape information, it may take a few seconds to get information of each school, after each school info is scraped, it is printed into the console. when reach up to the end, it may takes a bit longer. when you see `succeed`, open the docx file, all information should be there </li>
 <li>PS: the reason of first step, is that MS Word has three different format. first, when a docx file is brand new, it's in a binary format. second, when we open it and edit, a $cache.docx file will be created to secure data just in case of crash and out of battery. third, when we save it and close it, it's no longer in binary format, it will be in XML. python-docx can only edit docx file in XML format</li>
</ol>
<br /><br />
<h1>Feature</h1>
<hr />
<ol>
  <li>automatic web scraping using chrome driver</li>
  <li>Generate matplotlib graphics into the docx file by data scraped from website</li>
</ol>
<br /><br />
