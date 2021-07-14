# Authentication App



# Quick Start  🚀

### Add a config.env file in config folder with the following

```bash
{
  PORT=5000

  MONGO_URI=<your_mongoDB_Atlas_uri_with_credentials>

  JWT_SECRET=<secret>

  JWT_EXPIRE=10min

  EMAIL_SERVICE=SendGrid

  EMAIL_USERNAME=apikey

  EMAIL_PASSWORD=<your_api_key>

  EMAIL_FROM=<sender_email>

}
```

### Install server dependencies


 npm install 
[bcryptjs](https://www.npmjs.com/package/bcryptjs)
[express](https://www.npmjs.com/package/express)
[dotenv](https://www.npmjs.com/package/dotenv)
[jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
[mongoose](https://www.npmjs.com/package/mongoose)
[nodemailer](https://www.npmjs.com/package/nodemailer)



### Install client dependencies

```bash
cd client
```

```bash
npm install axios react react-dom react-router-dom react-scripts
```

npm install  [axios](https://www.npmjs.com/package/axios)
[react](https://www.npmjs.com/package/react)
[react-dom](https://www.npmjs.com/package/react-dom)
[react-router-dom](https://www.npmjs.com/package/react-router-dom)
[react-scripts](https://www.npmjs.com/package/react-scripts)

### Install dev dependencies

```bash
npm install -D concurrently nodemon
```

npm install -D [concurrently](https://www.npmjs.com/package/concurrently)
   [nodemon](https://www.npmjs.com/package/nodemon)
   
### Run both Express & React from root

```bash
npm run dev
```

### Build for production

```bash
cd client
npm run build
```





Check in browser on [http://localhost:5000/](http://localhost:5000/)


---

## App Info

### Author

[Amit kumar](http://www.amitkumar.tech)

### Version

1.0.0

