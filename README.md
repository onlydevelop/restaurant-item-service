# Item Service for restaurant

This is the item service for restaurant. This gives the name and price of an item given the itemId. This gives two different price depending on that is a 'restaurant' order or a 'takeaway' order.

#### Request
```
$ curl http://localhost:10000/items/1002/type/restaurant
```

#### Response
```
{"id":1002,"name":"Chicken Chaap","price":198}
```

#### Request
```
$ curl http://localhost:10000/items/1002/type/takeaway
```

#### Response
```
{"id":1002,"name":"Chicken Chaap","price":180}
```
