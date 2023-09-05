# OutOfStockScript

**Why Use It**

https://www.linkedin.com/posts/bhavesh-t_first-post-have-felt-inspired-recently-by-activity-7102545899901390848-b_Qu


**Setup:**

The script is fairly straight forward. There are 2 requirements for the script to work properly.

1. The script scans the pages html looking for Out Of Stock schema. If this doesn't exist or isn't working then you will need to change line 18. Try and find a page element that reflects the stock status accurately

2. If a product has more than one variant, the variant will need to have a unique URL. For example in Shopify the URL will looking something like https://www.domain.com/products/product-a?variant=3328718732823

4. Grouped Product Management: Columns F and G can be used to categorize and label groups of products. For example you have a Search campaign with an ad group that targets all t-shirts. Use column A of the sheet to list product URLs of the products/variants you want to track. Use column F to label those products and use that same label for an ad group within Google Ads. Column G is will update based on whether or not the label caused the ad group to pause or enable.

5. Out of Stock Threshold Setting: This setting allows you to define a threshold level to manage the stock more efficiently. Once the stock level reaches this predefined threshold, the script will automatically pause the ad groups, preventing inefficient spending on nearly out-of-stock products.

Installation: Copy the spreadsheet and populate it https://docs.google.com/spreadsheets/d/1WGnUoDb0Uu5AcYNLSwp0Ilr6nLAkH5T07Ve9UGjchOg/copy

Download the script from https://github.com/entromarketing/OutOfStockScript/blob/main/v1

Schedule the script to run daily

Column A is the product URL. Use the bestselling variant URL for a product with multiple variants. If there aren't any variants you can use the standard product URL.

Column B is for notes, I personally use it to list the size/colour that the product URL is referring to

Column C and D have to match the campaign and ad group names exactly. 

Column E has the current status of the ad group. 

Column F: Used to label your products based on their categories or any characteristic that suits your management style. This same label needs to be used for one or more ad groups within a Google Shopping or Search campaign

Column G: This will update based on whether or not the labeled ad groups were paused or enable as a result of the threshold set in configuration

Feedback or questions: https://www.linkedin.com/in/bhavesh-t/
