# Livebrary

### Introduction

This is a web application that allows users to track, monitor and store records of their physical and electronic books they own. Users can create, edit delete books from their records as well as read details of their favourite books.

### Demo




<img width="1470" alt="Screenshot 2024-08-09 at 16 43 34" src="https://github.com/user-attachments/assets/7d6d1eb6-8fd1-45b0-8313-13a659013e78">
<img width="1470" alt="Screenshot 2024-08-09 at 16 43 41" src="https://github.com/user-attachments/assets/723d9453-609b-4471-b328-9afc0d0c2737">
<img width="1470" alt="Screenshot 2024-08-09 at 16 44 06" src="https://github.com/user-attachments/assets/eb4886d9-1c2d-4a50-aa20-4fd8f8b1bbf1">
<img width="1470" alt="Screenshot 2024-08-09 at 16 44 27" src="https://github.com/user-attachments/assets/d3cdfe4d-824d-4b85-9b30-b812102aca23">
<img width="1470" alt="Screenshot 2024-08-09 at 16 44 42" src="https://github.com/user-attachments/assets/444a9408-5521-4d2d-9569-28011ee2f2e6">
<img width="1470" alt="Screenshot 2024-08-09 at 16 44 57" src="https://github.com/user-attachments/assets/8fdee683-247a-4a67-b1d2-305f2ec5f7b9">
Screenshot 2024-08-09 at 16.45.24
<img width="1470" alt="Screenshot 2024-08-09 at 16 45 36" src="https://github.com/user-attachments/assets/d8fb90f2-9a18-4f6c-8124-c622a47c6307">
<img width="1470" alt="Screenshot 2024-08-09 at 16 42 14" src="https://github.com/user-attachments/assets/a66f2e02-5467-40ff-800a-ff644ca50a8d">
<img width="1470" alt="Screenshot 2024-08-09 at 16 42 27" src="https://github.com/user-attachments/assets/ff07f08f-0d74-4cb8-992e-0c94e2fface4">
<img width="1470" alt="Screenshot 2024-08-09 at 16 42 30" src="https://github.com/user-attachments/assets/5a843b76-4005-4e41-b1b9-1fbb534f655f">



### Technology choices - Frontend
- React.js
- HTML
- Tailwind.css
- Javascript

### Technology choices - Backend
- MongoDB Atlas
- Node.js
- Express.js

### Obstacles and Solutions
- when i click on info icon i cannot see details solution was to double check the route as the console showed No routes matched location "/books/details/66b4fafa6839cfd80af24c83" solution typo "updateAt" to "updatedAt" and ad id to Route path of "/books/details/:id"
- solution was to correct "BrowseRouter" to "BrowserRouter"
- could not add books to MongoDB database as console showed empty Object { count: 0, data: [] } solution 'book' model definition was incorrect and amended to export const Book = mongoose.model('Book', bookSchema);

### Future feature releases
- Book recommendatoins based on current books in library
- Social media integration to share which books users own, have read and are reading
- Section to wishlist books that want to be added
