# ecommerce-json-server

JSON Server is a simple and lightweight tool that allows you to quickly create a RESTful API with a full set of CRUD operations based on a JSON file. This user guide will walk you through the steps to use JSON Server for mocking APIs during development.

### Resources/Routes

This json-server contains following *routes* to make frontend without backend.

- [/products](https://ecommerce-json-server.onrender.com/products) - object
- [/brands](https://ecommerce-json-server.onrender.com/brands) - object
- [/categories](https://ecommerce-json-server.onrender.com/categories) - object
- `/users` - object
- `/cart` - object
- `/orders` - object

### Available HTTP Methods

You can use the following HTTP methods to access and modify resources:

- **GET**: Retrieve resource data
- **POST**: Create a new resource
- **PUT**: Update or create a resource
- **PATCH**: Partially update a resource
- **DELETE**: Delete a resource
- **OPTIONS**: Get information about the communication options for the target resource

## Product Schema Model

The product schema model defines the structure of a product in your application. Below is a detailed breakdown of the fields and their meanings:

```json
{
  "title": "Metal Ceramic Flower",
  "description": "Metal Ceramic Flower Chandelier Home Lighting American Vintage Hanging Lighting Pendant Lamp",
  "price": 35,
  "discountPercentage": 10.94,
  "rating": 4.93,
  "stock": 10,
  "brand": "Ifei Home",
  "category": "lighting",
  "thumbnail": "https://i.dummyjson.com/data/products/97/thumbnail.jpg",
  "images": [
    "https://i.dummyjson.com/data/products/97/1.jpg",
    "https://i.dummyjson.com/data/products/97/2.jpg",
    "https://i.dummyjson.com/data/products/97/3.jpg",
    "https://i.dummyjson.com/data/products/97/thumbnail.jpg"
  ],
  "deleted": false
}
```

## Brands Schema Model

The brand schema model defines the structure of a brand in your application. Below is a detailed breakdown of the fields and their meanings:

```json
{
"value": "Apple",
"label": "Apple",
"checked": false
}
```

## Categories Schema Model

The categories schema model defines the structure of a categories in your application. Below is a detailed breakdown of the fields and their meanings:

```json
{
"value": "smartphones",
"label": "smartphones",
"checked": false
}
```

## Users Schema Model

The user schema model defines the structure of a user in your application. Below is a detailed breakdown of the fields and their meanings:

```json
{
"name": "test",
"email": "test@gmail.com",
"password": "Test@123",
"addresses": [],
"role": "user",
}
```

## Conclusion

JSON Server is a powerful and easy-to-use tool for mocking APIs during development. It allows you to focus on building and testing your application without the need for a fully functional backend. Enjoy using JSON Server for a seamless development experience! 🚀
