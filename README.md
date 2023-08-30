# OutOfStockScript

**Setup:**

The script is fairly straight forward. There are 2 requirements for the script to work properly.

1. The script scans the pages html looking for Out Of Stock schema. If this doesn't exist or isn't working then you will need to change line 18. Try and find a page element that reflects the stock status accurately

2. If a product has more than one variant, the variant will need to have a unique URL. For example in Shopify the URL will looking something like https://www.domain.com/products/product-a?variant=3328718732823

Installation: Copy the spreadsheet and populate it https://docs.google.com/spreadsheets/d/1nkujhXqb-ZQljp8khU71HBXOGDo-CFYQXbS-XTrTznk/copy 

Download the script from https://github.com/entromarketing/OutOfStockScript/blob/main/v1

Schedule the script to run daily

Column A is the product URL. Use the bestselling variant URL for a product with multiple variants. If there aren't any variants you can use the standard product URL.

Column B is for notes, I personally use it to list the size/colour that the product URL is referring to

Column C and D have to match the campaign and ad group names exactly. 

Column E has the current status of the ad group. 

Feedback or questions: https://www.linkedin.com/in/bhavesh-t/
