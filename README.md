# 🎬 MovieStream - Full Stack Movie Streaming Platform

A modern and feature-rich movie streaming platform built with Spring Boot, MongoDB, and ReactJS. This application allows users to browse, stream, and manage their favorite movies with a responsive interface and secure backend.

## 🚀 Features

- 📺 Movie streaming with high-quality video playback
- 🔍 Advanced search and filtering capabilities
- 👤 User authentication and authorization 
- 📱 Responsive design for all devices  
- ⭐ User ratings and reviews     
- 📋 Watchlist management
- 🎯 Personalized recommendations  
   
## 🛠️ Tech Stack  
 
### Frontend
- ReactJS
- Material-UI
- Redux for state management
- Axios for API calls
- React Router for navigation

### Backend
- Spring Boot
- MongoDB
- Spring Security
- JWT Authentication
- Maven

## 📁 Project Structure

```
Directory structure:
└── hariharans24-moviestream-react-springboot/
    ├── README.md
    ├── LICENSE
    ├── movies-streaming-backend/
    │   ├── HELP.md
    │   ├── mvnw
    │   ├── mvnw.cmd
    │   ├── pom.xml
    │   ├── src/
    │   │   ├── main/
    │   │   │   ├── java/
    │   │   │   │   └── com/
    │   │   │   │       └── example/
    │   │   │   │           ├── MoviesApplication.java
    │   │   │   │           └── movies/
    │   │   │   │               ├── Movie.java
    │   │   │   │               ├── MovieController.java
    │   │   │   │               ├── MovieRepository.java
    │   │   │   │               ├── MovieService.java
    │   │   │   │               ├── Review.java
    │   │   │   │               ├── ReviewController.java
    │   │   │   │               ├── ReviewRepository.java
    │   │   │   │               └── ReviewService.java
    │   │   │   └── resources/
    │   │   │       └── application.properties
    │   │   └── test/
    │   │       └── java/
    │   │           └── com/
    │   │               └── example/
    │   │                   └── movies/
    │   │                       └── MoviesApplicationTests.java
    │   └── target/
    │       └── classes/
    │           ├── application.properties
    │           └── com/
    │               └── example/
    │                   └── movies/
    └── movies-streaming-frontend/
        ├── README.md
        ├── package-lock.json
        ├── package.json
        ├── public/
        │   ├── index.html
        │   ├── manifest.json
        │   └── robots.txt
        └── src/
            ├── App.css
            ├── App.js
            ├── index.css
            ├── index.js
            ├── api/
            │   └── axiosConfig.js
            └── components/
                ├── Layout.js
                ├── header/
                │   └── Header.js
                ├── hero/
                │   ├── Hero.css
                │   └── Hero.js
                ├── home/
                │   └── Home.js
                ├── log/
                │   ├── Login.js
                │   └── Register.js
                ├── notFound/
                │   └── NotFound.js
                ├── reviewForm/
                │   └── ReviewForm.js
                ├── reviews/
                │   └── Review.js
                └── trailer/
                    ├── Trailer.css
                    └── Trailer.js
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- Java JDK 11 or higher
- MongoDB
- Maven

### Frontend Setup
```bash
cd movies-streaming-frontend
npm install
npm start
```

### Backend Setup
```bash
cd movies-streaming-backend
mvn clean install
mvn spring-boot:run
```

## 🤝 Contributing

We welcome contributions to MovieStream! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **Hariharan S** - *Initial work* - [HARIHARANS24](https://github.com/HARIHARANS24)

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the open-source community for their amazing tools and libraries 
