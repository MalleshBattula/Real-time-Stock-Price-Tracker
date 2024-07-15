# Real-Time Stock Price Tracker

This project is a mini-website that collects and displays real-time price data for stocks or cryptocurrencies. It consists of a backend server built with Express.js and a frontend client using Next.js, designed to fetch and display data from external APIs and MongoDB.

## Features

- **Backend:**
  - Polls real-time data every few seconds for 5 stocks or cryptocurrencies from a selected API (e.g., CoinGecko).
  - Stores fetched data in a MongoDB database.

- **Frontend:**
  - Fetches the most recent 20 entries of real-time data from MongoDB for a particular stock or crypto.
  - Displays the data dynamically in a table that updates in real-time.
  - Includes a modal/popup allowing users to change the selected stock or crypto symbol.

## Technologies Used

- **Backend:**
  - Express.js
  - TypeScript
  - MongoDB

- **Frontend:**
  - Next.js
  - React.js
  - TypeScript
  - Redux

## Prerequisites

Before running this project locally, ensure you have the following installed:

- Node.js (v12.x or higher)
- npm or yarn
- MongoDB (running locally or accessible via URI)

## Getting Started

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd Real-time Stock-Price-Tracker
"# Real-time-Stock-Price-Tracker" 
