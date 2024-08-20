# Backtesting - Android Cryptocurrency Trading Strategy App

## Overview

**Backtesting** is an Android application designed to provide users with comprehensive analysis and tracking of cryptocurrency trading strategies. The app allows users to visualize trading results through detailed charts and efficiently manage their favorite strategies. With features like historical trade analysis and strategy simulations, **Backtesting** enables users to forecast potential outcomes without any financial risk.

## Features

- **Home Activity**: The landing page after login, displaying the most recent trading chart (if available) or a welcome message. Users can navigate to different parts of the app or sign out from here.
  
- **Favorite Activity**: Users can view, manage, and organize their favorite trading strategies and results for quick reference.

- **History Activity**: Provides a historical overview of past trades, allowing users to analyze and track performance trends over time.

- **Test Activity**: Simulates trading strategies using historical data, enabling users to forecast potential outcomes without risking actual funds.

- **Top Activity**: Displays the top-performing strategies based on user data and shared insights from the community.

## Technical Components

- **HomePageActivity**: The central hub of the application that presents the most recent chart data or general information when no data is available. It includes navigation options to other sections of the app and a sign-out option.

- **FileHandler**: Manages file operations within the app, focusing on reading and writing data critical for trading strategies and result storage.

- **StrategyExecutor**: Executes cryptocurrency trading strategies using historical data, simulating trading environments and calculating performance metrics.

- **TradeStrategies**: Defines and manages various trading strategies. This component is essential for users who wish to test different trading approaches within the app.

## Libraries and Tools

- **Firebase**: Used for authentication, database storage, and real-time data handling.
  
- **MPAndroidChart**: A powerful library for rendering complex charts within Android applications, extensively used in the app for displaying trading analytics.

## Getting Started

To get started with **Backtesting**, clone the repository and open the project in Android Studio. Make sure to configure Firebase for authentication and database storage. Install the necessary dependencies, including **MPAndroidChart**, for chart rendering. Once set up, you'll be able to simulate trading strategies, track performance, and manage your favorite strategies.

## Contributing

Contributions to the **Backtesting** app are welcome! Feel free to fork the repository, create a new branch, and submit a pull request with your changes.

https://github.com/user-attachments/assets/615f5fe5-f879-4ec3-917e-7a255ad993c4


