# Weather App

This is a simple ASP.NET Core web application that provides current weather information and a 5-day weather forecast using the OpenWeatherMap API.

## Features

- Get current weather by location name
- Get current weather by latitude and longitude
- Get 5-day weather forecast by location name
- Get 5-day weather forecast by latitude and longitude

## Prerequisites

- .NET Core SDK
- Visual Studio or Visual Studio Code
- Git

## Setup

1. Clone the repository:

    ```bash
   git clone https://github.com/abbas518/Abbas_WeatherApp.git

    ```

2. Navigate to the project directory:

    ```bash
    cd REPOSITORY_NAME
    ```

3. Open the project in Visual Studio.

4. Restore the NuGet packages:

    ```bash
    dotnet restore
    ```

5. Add your OpenWeatherMap API key to the `HomeController.cs` file:

    ```csharp
    public string apiKey = "YOUR_API_KEY";
    ```

6. Run the project:

    ```bash
    dotnet run
    ```

## Usage

- Navigate to the homepage to enter a location and get the current weather and forecast.
- If geolocation is enabled in your browser, the app will fetch the weather for your current location.

## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
