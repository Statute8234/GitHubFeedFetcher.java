# GitHubFeedFetcher
The GitHubFeedFetcher is a Java program that requests data from the GitHub API using a URL and access token, using HttpURLConnection and Base64 authentication.


[![Static Badge](https://img.shields.io/badge/java.io.BufferedReader-red)](https://mvnrepository.com/artifact/java.io.BufferedReader)
[![Static Badge](https://img.shields.io/badge/java.io.InputStreamReader-pink)](https://mvnrepository.com/artifact/java.io.InputStreamReader)
[![Static Badge](https://img.shields.io/badge/java.net.HttpURLConnection-gray)](https://mvnrepository.com/artifact/java.net.HttpURLConnection)
[![Static Badge](https://img.shields.io/badge/java.net.URL-gray)](https://mvnrepository.com/artifact/java.net.URL)
[![Static Badge](https://img.shields.io/badge/java.util.Base64-green)](https://mvnrepository.com/artifact/java.util.Base64)

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Rating: 7/10](#Rating)

# About

The GitHubFeedFetcher is a Java program that performs an HTTP GET request to the GitHub API using a specified URL and access token, retrieves data from the specified endpoint, and prints the response to the console using HttpURLConnection and Base64-encoded personal access token.

# Features

The GitHubFeedFetcher Java program is a tool that initiates an HTTP GET request to the GitHub API using a specified URL. It requires an access token to authenticate with the API, ensuring the user has the necessary permissions to retrieve data. The program retrieves data from the specified endpoint, including information about repositories, commits, issues, and pull requests. After successfully retrieving the data, the program prints the response to the console, allowing the user to view it directly in their terminal or command prompt. The program also handles connection handling using `HttpURLConnection`, handling potential errors and network-related issues. It may use Base64-encoded personal access tokens for authentication, representing binary data as ASCII text in HTTP request headers. The implementation details may vary depending on the specific code.

# Installation
1) HTTPS - https://github.com/[User]/GitHubFeedFetcher.java.git
2) CLONE - git@github.com:[User]/GitHubFeedFetcher.java.git
   
# Usage

The program demonstrates the basics of making an authenticated HTTP request to an API using Java, handling HTTP connection, authentication, and response reading. However, improvements include more robust error handling, code security, modularity, and using environment variables or configuration files for sensitive data like URLs and tokens. The code could also be refactored into methods for better readability and reusability.

# Rating

The project showcases the use of Java Swing in building a GUI application, including essential features for data management and persistence. The layout and organization of components are logical and user-friendly, and file I/O for data persistence is well-implemented. However, areas for improvement include modularizing the code for better readability and maintainability, enhancing error handling to handle specific exceptions, improving the user experience through better color schemes and fonts, and expanding the functionality with features like searching, sorting, and filtering list items. Testing through unit tests for data management functions and UI testing is also recommended. Overall, the project provides a solid foundation for building dynamic GUI applications with essential functionalities and good practices in data management and persistence.
