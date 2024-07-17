# URL Shortner

A simple URL shortener built with Node.js, Express, EJS, and MongoDB. This application allows users to shorten long URLs and track the number of clicks for each shortened link.


## Description
The URL Shortener project provides a straightforward way to shorten long URLs and track their usage. It uses Node.js with the Express framework for the backend, MongoDB for data storage, and EJS for server-side templating. This project demonstrates basic CRUD operations with MongoDB and includes features like URL shortening and click tracking.

## Features

- Shorten long URLs
- View a list of shortened URLs with their full versions, short links, and click counts
- Responsive design for various devices
- Basic URL validation to ensure valid URLs are shortened

## Technologies Used

- **Node.js**: JavaScript runtime for building the application
- **Express**: Web framework for Node.js
- **EJS**: Embedded JavaScript templating for rendering HTML views
- **MongoDB**: NoSQL database for storing URLs and their click data
- **Bootstrap**: Front-end framework for responsive design

## Installation Instructions

Follow these steps to get your development environment up and running:

- **Clone the Repository:**


```bash
git clone https://github.com/Slygriyrsk/url-shortener.git
cd url-shortener
```

- **Install Dependencies**

```bash
npm install express mongoose ejs nodemon
```

- **Set Up the Environment**

Make sure MongoDB is running on your local machine. If you don't have MongoDB installed then you can follow this link below:
https://www.mongodb.com/try/download/community



## Start the application

```bash
nodemon server.js
```






## Usage

To shorten a URL, enter the full URL into the input field on the main page and click the "Shorten" button. You will receive a shortened URL that redirects to the original URL. The application tracks the number of clicks on each shortened URL.

## Configuration

You can customize the shortUrl model and server.js for different settings or features. The default configuration uses ```localhost:27017/urlShortener``` for MongoDB.
You can change this in server.js:

```javascript
mongoose.connect('mongodb://localhost:27017/urlShortener', {
  useNewUrlParser: true,
  useUnifiedTopology: true
});

```


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

- Fork the repository.
- Create a new branch for your   feature or fix.
- Make your changes and commit them.
- Push your changes to your fork.
- Open a pull request.

Please adhere to this project's `code of conduct`.


## License

This project is licensed under the MIT License. See the ```LICENSE``` file for details. [MIT](https://choosealicense.com/licenses/mit/)


## Contact Me

If you have any questions or feedback, feel free to contact me:

```Email: slygrin005@gmail.com```
```GitHub: Slygriyrsk```

## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saharsh-kumar-9768a8264/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/repatriation_23?s=09)
