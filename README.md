# :cloud: :snowflake: weather_forecast :open_umbrella: :satellite:



The pip package provides weather forecasting information based on location or address. Using address, the weather_forecast provides location specific forecast. Currently only one function is included i.e forecast. 



### Install :computer:
```
pip install git+https://github.com/iurrrok/weather_forecast
```

### Code Usage :video_game:
```
import weather_forecast as wf
wf.forecast(place = "Bangalore" , time="23:15:00" , date="2019-09-12" , forecast)
```
or 
```
wf.forecast(place = "Bangalore")
```
Так же можно использовать русский 
```
wf.forecast(place = "Москва")
```
Либа возвращает словарик вида :
```
{'place': 'Bangalore', 'time': '10:17:36', 'date': '2021-01-23', 'day': {'temperature': 28, 'precipitate': 0, 'uv_description': 'Extreme', 'wind_speed': 11, 'humidity': 38, 'phrases': 'Sunny', 'narrative': 'Generally clear. High 28ºC. Winds E at 10 to 15 km/h.'}, 'night': {'temperature': 15, 'precipitate': 9, 'uv_description': 'Low', 'wind_speed': 10, 'humidity': 79, 'phrases': 'Clear', 'narrative': 'Generally clear. Low 15ºC. Winds ESE and variable.'}}
```


### Command Line usage :space_invader:

- Navigate to **./weather_forecast/** and then execute the below command.



```
python forecast.py -p Bangalore
```

```
python forecast.py -p Bangalore -d 2019-09-12
```
