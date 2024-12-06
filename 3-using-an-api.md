Using an API: Example with OpenWeatherMap

## Step 1: Sign Up for an API Key
1. Go to [OpenWeatherMap](https://openweathermap.org/).
2. Create an account and get your API key.

## Step 2: Send a Request
Use a tool like Postman or a browser to request weather data:
- **Request URL:**
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY
## Step 3: Parse the Response
You will receive a JSON response:
```json
{
"weather": [{
   "description": "clear sky"
}],
"main": {
   "temp": 280.32
}
}
