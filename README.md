# TuneHub Project
#### TuneHub is a comprehensive platform designed to enhance the music experience for users. It offers a variety of features including user registration, playlist creation, and song management.

## Features
- User Registration and Login
- Playlist Creation and Management
- Song Management
- Admin and Customer views
- Payment Integration with Razorpay
- Responsive UI

## Technologies Used
- Java SE 17
- Spring Boot
- Maven
- Thymeleaf
- HTML/CSS
- Razorpay

## Prerequisites
- Java Development Kit (JDK) 17 or higher
- Maven

## Installation Instructions
### Clone the repository:
`git clone  https://github.com/Theertha26/TuneHubMusic/tree/master`

## Usage
#### After running the application, you can access it in your web browser at http://localhost:8080. You will see the following pages:

- Home Page (index.html)
- Admin Home (adminHome.html)
- Customer Home (customerHome.html)
- Create Playlist (createPlaylist.html)
- Display Playlists (displayPlaylists.html)
- Display Songs (displaySongs.html)
- New Song (newSong.html)
- Login (login.html)
- Registration (registration.html)
## API Documentation
 ### Playlist Controller
- GET /createPlaylist - Show create playlist page
- GET /addPlaylist - Add a new playlist
- GET /displayPlaylists - Display all playlists
### Payment Controller
- GET /pay - Show payment page
- POST /createOrder - Create a new order
- POST /verify - Verify payment
### Nav Controller
- GET /login - Show login page
- GET /registration - Show registration page
- GET /newSong - Show new song page
- GET /index - Show home page
### Users Controller
- POST /register - Register a new user
- POST /validate - Validate user credentials
- GET /logout - Logout user
### Song Controller
- POST /addSong - Add a new song
- GET /displaySongs - Display all songs
- GET /playSongs - Play songs (premium users)
- GET /custSongsHome - Show customer songs home page
- GET /searchSongs - Search for songs
- POST /deleteSong - Delete a song

