# SuperPetNamer
Generative AI model on suggesting 'AvengerName'(s) to animals. 

# What is it all about? 
This repository contains a simple web service that generates superhero names for animals using the OpenAI GPT-3.5 Turbo model.

## Prerequisites: 

Before you start, make sure you have the following:

- Node.js installed
- An OpenAI API key

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/animal-superhero-generator.git

2. Install dependencies:
   
   - cd animal-superhero-generator
   - npm install

3. Set up your OpenAI API key:
   - Copy the .env.example file to a new file named .env
   - cp .env.example .env
   - Open the .env file and replace my Open AI API Key with your actual one.

4. Run the application:
   - npm start
  
    The application will start on http://localhost:3000 

## How to utilize the Model: 
  - Make a POST request to http://localhost:3000 with a JSON payload containing the desired animal:
    curl -X POST -H "Content-Type: application/json" -d '{"animal": "Cat"}' http://localhost:3000

    * Replace "Cat" with the animal for which you want a superhero name.

## Configuration
  - The OpenAI GPT-3.5 Turbo model is used to generate superhero names. You can adjust the model settings and prompt generation in the code to customize the output.

## License
  - This project is licensed under the MIT License - see the LICENSE file for details.
