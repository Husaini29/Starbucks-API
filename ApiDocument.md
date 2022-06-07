Api Link:
 http://localhost:9876/

 https://starbuck-api.herokuapp.com/

Page 1: Find a Store

Data to find a store:  
http://localhost:9876/stores/stores

https://starbuck-api.herokuapp.com/stores

Find a store w.r.t cityId (for using in map): 
http://localhost:9876/stores?city_id=4

https://starbuck-api.herokuapp.com/stores?city_id=5

Find a store w.r.t cityname (for using in search bar):
 http://localhost:9876/stores?city_name=delhi

 https://starbuck-api.herokuapp.com/stores?city_name=Delhi

Find a store w.r.t store name (for using in search bar):
 http://localhost:9876/stores?name=Punjabi%20Bagh
 
 https://starbuck-api.herokuapp.com/stores?name=Punjabi%20Bagh



Page 2: Menu (Fetches data for coffee as well as food)

Sub-category data: https://starbuck-api.herokuapp.com/category

https://starbuck-api.herokuapp.com/category?type=Drinks

https://starbuck-api.herokuapp.com/category?id=1

https://starbuck-api.herokuapp.com/category?type=Food&id=10

Menu data w.r.t category id: https://starbuck-api.herokuapp.com/item/1



Page 3: Careers

Jobs w.r.t CityId and Keyword/Profile: https://starbuck-api.herokuapp.com/jobs?city_id=2&profile=Barista

Jobs w.r.t Cityname and Keyword: https://starbuck-api.herokuapp.com/jobs?city_name=Pune&profile=Barista

Jobs w.r.t CityId: https://starbuck-api.herokuapp.com/jobs?city_id=4

Jobs w.r.t CityName: https://starbuck-api.herokuapp.com/jobs?city_name=Delhi

Jobs w.r.t Keyword/Profile: https://starbuck-api.herokuapp.com/jobs?profile=Apprentice

Api for name animation (Post Call): https://starbuck-api.herokuapp.com/name

Fetching name for animation: https://starbuck-api.herokuapp.com/fetchname/620a32d2f173b2436e1192d0



Page 4: Starbucks Delivers/Filters

For Type (veg/Non-Veg): https://starbuck-api.herokuapp.com/filter?type=Vegetarian

For Price: https://starbuck-api.herokuapp.com/filter?bprice=200&aprice=350

For Ratings:https://starbuck-api.herokuapp.com/filter?arate=4 https://starbuck-api.herokuapp.com/filter?brate=4

To place order (Post Call): https://starbuck-api.herokuapp.com/placeOrder

Menu item based on user's selection (Post Call): https://starbuck-api.herokuapp.com/menuItem

Update Order (Put Call): https://starbuck-api.herokuapp.com/updateOrder/620a171210f46a95ecc712d2?status=SUCCESS

Delete Order: https://starbuck-api.herokuapp.com/deleteOrder



Page 5: Rewards

List of gift cards: https://starbuck-api.herokuapp.com/giftcards/1

Gift card based on user's selection (Post Call): https://starbuck-api.herokuapp.com/giftcard

Placing Order for gift cards (Post Call): https://starbuck-api.herokuapp.com/giftcardOrder

Updating Order for gift cards (Put Call): https://starbuck-api.herokuapp.com/updategiftOrder/620a6fa338e79a9e1a6b0d11?status=SUCCESS

Delete Orders for gift cards: https://starbuck-api.herokuapp.com/deletegiftOrder