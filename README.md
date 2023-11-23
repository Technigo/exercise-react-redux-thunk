# Coin Fetcher App

## Overview

This is a simple web application that fetches data about cryptocurrencies from the [CoinGecko API](https://www.coingecko.com/en/api) and displays it on the UI. The app is built using JavaScript and utilizes the Fetch API to make requests to the CoinGecko endpoint.

## Features

- **Coin Data Display**: The app fetches data about cryptocurrencies from the CoinGecko API and displays it on the UI.

- **Loading State**: A loading state is implemented to indicate that the app is fetching data. This helps improve user experience by providing feedback during the data retrieval process.

- **Animation for Loading State**: To enhance the loading state, the app incorporates animation to make the waiting period more visually appealing for users.

## Getting Started

1. Fork and clone the repository to your local machine:

    ```bash
    git clone https://github.com/Technigo/exercise-react-redux-thunk.git
    ```

2. Open the project folder:

    ```bash
    cd exercise-react-redux-thunk
    ```

3. Run the app:

    ```bash
    npm run dev
    ```

## Instructions

Build an app that fetches some coins from the end-point provided and saves the data in the global state

Create a store, reducers, dispatch actions and select data from the state to render in your components.

Add a loading state until the fetching request is fultilled.

What about using some animation for the loading state?

Fetch data from this end-point:

 
    const url = "https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd";


