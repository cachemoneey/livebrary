# Livebrary

### Introduction

This is a web application that allows users to track, monitor and store records of their physical and electronic books they own. Users can create, edit delete books from their records as well as read details of their favourite books.

### Demo

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
