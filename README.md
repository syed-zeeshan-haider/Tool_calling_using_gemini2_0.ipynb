# Tool Calling with Gemini 2.0

This project demonstrates a tool-calling application developed using Gemini 2.0. The application has a frontend and a Python backend and leverages LangChain Generative AI (GenAI) for tool execution. Below is a detailed overview of the application and its features.

# Features 🚀

This application integrates various tools that perform different tasks:

🔍 google_search_tool: Searches Google for a query and retrieves results.

☁️ get_weather: Provides the current weather for a specified location.

✖️ multiply: Multiplies two numbers and returns the result.

📰 get_latest_news: Fetches the latest news headlines.

🎥 get_movie_details: Retrieves details about a specific movie.

🍲 get_recipe: Provides recipes based on the input ingredients or dish name.

📍 get_distance: Calculates the distance between two locations.

📈 get_stock_price: Fetches the current stock price for a specified company.

🌐 get_ip_address: Retrieves the public IP address of the client.

🖼️ search_image: Performs an image search based on a query.

📤 upload_image: Allows users to upload an image.

📝 describe_image: Generates a description for the uploaded image.

🎨 generate_image: Creates an AI-generated image based on a description.

🔊 text_to_voice: Converts text input into spoken audio output.

# Prerequisites ✅

Python 3.8 or higher

Node.js for frontend (if applicable)

LangChain Generative AI setup

Required libraries mentioned in requirements.txt

# Usage 💡

Access the application in your browser at http://localhost:3000.

Use the interface to interact with the tools.

The backend will handle the tool calling and processing.

Tools Details 🛠️

🔍 google_search_tool

Performs Google searches based on user queries. Requires an API key for Google Custom Search.

☁️ get_weather

Fetches weather data from APIs like OpenWeatherMap. Requires an API key.

✖️ multiply

Performs basic multiplication of two numeric inputs.

📰 get_latest_news

Fetches news headlines from APIs like NewsAPI. Requires an API key.

🎥 get_movie_details

Retrieves movie details such as cast, release date, and synopsis using APIs like OMDB.

🍲 get_recipe

Provides recipes based on ingredients or dish names using APIs like Spoonacular.

📍 get_distance

Calculates the distance between two locations using mapping APIs like Google Maps.

📈 get_stock_price

Fetches real-time stock prices using APIs like Alpha Vantage.

🌐 get_ip_address

Retrieves the client’s public IP address.

🖼️ search_image

Performs image searches using services like Bing Image Search or Google Custom Search.

📤 upload_image

Allows users to upload images for processing.

📝 describe_image

Generates descriptions for uploaded images using AI models like CLIP or similar.

🎨 generate_image

Creates AI-generated images using models like DALL-E or Stable Diffusion.

🔊 text_to_voice

Converts text to speech using libraries like gTTS or Amazon Polly.

# Contributing 🤝

Fork the repository.

Create a new branch for your feature or bugfix.

Commit your changes and push to the branch.

Create a pull request.

# License 📜

This project is licensed under the MIT License. See the LICENSE file for more details.
