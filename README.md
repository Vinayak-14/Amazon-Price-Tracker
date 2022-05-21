# Amazon-Price-Tracker
A web-scraper built on BeautifulSoup that alerts you when the price of an amazon product falls within your budget!

# Amazon prices keep fluctuating- Let's scrape them!💲
 C3PO is a web-scraper built on BeautifulSoup that alerts you when the price of an amazon prduct falls within your budget! 
 

# Demo Video
 
https://user-images.githubusercontent.com/85126091/169645652-5ca5b6e4-58b5-43a5-859c-6e2b840618b8.mp4

 
 ## What is the use❓
 Nothing is worse than seeing the price drop of a product you just bought on Amazon drop 2 days after you bought it. Wouldn't it be amazing if a python script could just 
 ask you your budget and the product link and then notify you when the product price drops below that? This is exactly what this script does!
 
 ## How to use❓ 
 Simply copy-paste the link of the product and your budget- that's it! The scraper will do the rest for you and notify you when the price is in your budget.
 However, it is to be kept in mind that the sender email ID and password has been stored in os variables in the script. Therefore, wherever you see the imports of 
 'DEVELOPER_EMAIL' and 'DEVELOPER_PASS', be sure to replace them with the email ID you wish to recieve the notification from.
 ### Side Note📝
 Do remember to install the dependencies in the requirements.txt file!
 
 ## Modules used (available in requirements.txt)🧩
 * requests
 * requests_html
 * BeautifulSoup
 
 ## Development Status✈ 
 This scrapper is complete. A future version may have emails sent via a server.
