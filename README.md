Activity 1: Simple-WebScraping
=============================

This activity consists in making a program in Python which manages to filter information on this [page](https://www.banggood.com/Flashdeals.html) through the Web Scraping technique, which consists of gathering information automatically from the Web.
In this case, we must obtain information about the products found on this website. Specifically, the information that we should obtain through this program was the name of the product, the price on offer and the original price of the product.

As for the code, several functions have been performed. The first call "download_page", which searches the web page and downloads. Another function takes the code of the page and passes into "lxml" format. As for the functions performed for do filters, we have a function called "search_prices", it serves to filter prices, the original price and the price on offer too. We have another function called "search_name_product", which finds the name of each product. The last function called "print_data" show the final result.

Something to keep in mind is that some products that haven't original price, only have a current price, therefore the original price will have "None" value.


### Author ###
* [Marc Castellnou Quibus](https://github.com/MarCastellnou)

### Links ###
* [Practice statement](https://cv.udl.cat/access/content/attachment/102023-1819/Activitats/07919b10-6280-4738-bbc2-0f19c3ce386b/enunciat.pdf)
* [Used page](https://www.banggood.com/Flashdeals.html)
