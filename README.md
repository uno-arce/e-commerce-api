An API that features user and product management, product information retrieval, product to cart, and cart to checkout. It has JWT authentication and encryption of sensitive user data, only users with a token can use the app. The app lets users see product details and checkout products in their cart, while users with admin role can create, update, and archive products.

## Functionalities
**Key Functionalities**
- User Authentication
- No-SQL Database Management
- Rest API
- File Upload
- Crud

## What's Inside
**Folder Structure**  
```
-- src  
├── controllers  
├── model  
├── routes  
├── uploads
```

**Dependencies**
| Package | Purpose |
| --- | --- |
| `bcryptjs` | Password hashing and security |
| `cors` | Enabling Cross-Origin Resource Sharing |
| `express` | Web application framework for Node.js |
| `jsonwebtoken` | Securely transmitting information as a JSON object |
| `mongoose` | MongoDB object modeling for Node.js |
| `fs` | File system interaction for reading/writing local files |
| `googleapis` | Integration with Google Cloud Platform services |
| `multer` | Middleware for handling file uploads |
