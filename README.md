# E-commerce Chatbot

This **E-commerce Chatbot** is a virtual assistant built to enhance the customer experience on an e-commerce platform. It uses natural language processing (NLP) and machine learning techniques to understand customer queries, assist with product inquiries, provide order information, and facilitate a smoother shopping experience.

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Libraries Used](#libraries-used)
- [Data and Training](#data-and-training)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
- [Frontend Interface](#frontend-interface)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project

The **E-commerce Chatbot** is designed to automate customer support and guide users through product inquiries and order-related questions. By recognizing specific intents from user queries, the chatbot provides relevant responses and assists users in navigating the e-commerce platform.

## Features

- **Product Inquiry Assistance**: Helps users find products, check availability, and compare items.
- **Order Information**: Provides updates on order status, estimated delivery times, and return policies.
- **FAQ Responses**: Responds to frequently asked questions regarding the platform's policies.
- **Personalized Recommendations**: Offers product suggestions based on customer preferences.

## Libraries Used

The following libraries are used in this project:

- **sys**: System-specific parameters and functions.
- **nltk (Natural Language Toolkit)**: For tokenization, stemming, and other NLP functions.
- **numpy**: For handling numerical operations and matrix manipulations.
- **PorterStemmer**: For word stemming in NLP preprocessing.
- **punkt**: Tokenizer within nltk for breaking text into individual words.
- **torch, torch.nn**: Used to build and train the neural network model.
- **Dataset and DataLoader**: For organizing and loading data in batches.
- **flask**: To create a simple web-based frontend for the chatbot.
- **HTML and CSS**: For designing the user interface.

## Data and Training

The chatbot uses intents stored in a `intents.json` file. These intents include sample queries and corresponding categories, such as product-related questions, order tracking, and general FAQs.

The machine learning model is built using PyTorch and uses a neural network (`NeuralNet`) to classify user inputs into predefined intents. NLP techniques such as bag-of-words and stemming are applied to preprocess the text data.

## Tech Stack

- **Backend**: Python, Flask
- **Machine Learning**: PyTorch, nltk
- **Frontend**: HTML, CSS for the web interface
- **Data Storage**: JSON for intent data

## Getting Started

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/ecommerce-chatbot.git
   cd ecommerce-chatbot
   ```
