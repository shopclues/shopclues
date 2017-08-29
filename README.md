# Shopclues Products API

Shopclues is one of the leading e-commerce portals in India. It sells millions of products daily and has a huge inventory of items across different categories like electronics, mobiles & tables, fashion and heavy equipments. Some of you might be interested in doing some analysis on the list of products. In such cases you can use this API to get the items list.

**Features of the API**

The shopclues product API is developed by the [eshopclues](http://eshopclues.in) coupons online portal. To use this API, you have to register with shopclues and get the access token. After that, this access token has to be used in your code. The features of this API are listed below:

With this API you can retrieve the list of all categories.
In each category, we can get the number of items and the details of the products.
The product specifications can be retrieved by using the SKU of the item.

**Shopclues API Guide**

Here is a sample PHP code which you can use to get the products. 
```php
<?php
include "shopclues-api.php";
$token = 'ACCESS_TOKEN';
$categories = getCategoryList($token);
$product_list = getProductList($category);
$product_details = getProductDetails($SKU);
?>
```
For more information about the API, read the notes. This is a pretty straightforward code and you can integrate in your web and mobile applications. The functions return the data in JSON Format. 

**Terms and Conditions**

This is an open source API and any one is free to use. The only condition is you have to register with shopclues and get the access token. You can even use this API for commercial purpose.
