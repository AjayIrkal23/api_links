
<!-- Quick Search -->
<!-- List of all Brand Products  -->
http://localhost:9870/allproducts
<!-- Quick Search -->



<!-- List of all Brands  -->
http://localhost:9870/allbrands



<!-- list of brand 1 -->
http://localhost:9870/brandcollusion



<!-- list of brand 2 -->
http://localhost:9870/brandMonki



<!-- list of brand 3 -->
http://localhost:9870/brandNFD



<!-- list of brand 4 -->
http://localhost:9870/brandRV



<!-- list of brand 5 -->
http://localhost:9870/Topshop



<!-- list of all brands products on color -->
http://localhost:7800/allproducts?color=black
http://localhost:7800/allproducts?color=white



<!-- list of items on their brand id  -->
(post) localhost:7800/orderitem
{"id":[1,3]}


<!-- placing order api  -->
(post)localhost:7800/orders
{
            "Name": "denim crop top in white",
            "url": "//images.asos-media.com/products/waven-one-shoulder-tie-detail-denim-crop-top-in-white/201642754-1-opticalwhite?$n_480w$&wid=476&fit=constrain",
            "id ": 10,
            "color": "white",
            "Price": "19$"
}



<!-- list of orders available  -->
http://localhost:7800/ordersavailable


<!-- list of orders updated  -->
http://localhost:7800/orderupdate/1




