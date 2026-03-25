## Weather API Console App

A simple Java console application that fetches and displays real-time weather data for any city worldwide. It uses the free [Open-Meteo API](https://open-meteo.com/) for geocoding and weather forecasting.

## Features

The application prompts the user for a city name and provides the following real-time data:
* Current local time
* Air temperature (°C)
* Relative humidity (%)
* Wind speed (km/h)

## Technologies & Requirements

* **Language:** Java (JDK 8 or higher)
* **JSON Parsing:** `json-simple` library (v 1.1.1)
* **Networking:** Standard `java.net.HttpURLConnection`

## Setup and Installation (IntelliJ IDEA)

### 1. Clone the repository
Clone this project to your local machine and open the folder in IntelliJ IDEA.

### 2. Add the `json-simple` dependency (Crucial Step)
This project requires the `json-simple` library to parse API responses. 

**If you are using Maven**, add the following to your `pom.xml` under `<dependencies>`:
```xml
<dependency>
    <groupId>com.googlecode.json-simple</groupId>
    <artifactId>json-simple</artifactId>
    <version>1.1.1</version>
</dependency>
```
If you are using a standard Java project (No Maven):

Download the json-simple-1.1.1.jar file.

In IntelliJ IDEA, go to File -> Project Structure -> Modules -> Dependencies tab.

Click the + icon, select JARs or directories..., and browse to your downloaded .jar file. Click Apply and OK.

3. Run the application
Open the WeatherAPIData.java file and run the main method.

