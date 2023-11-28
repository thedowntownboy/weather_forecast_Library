# weather_forecast_Library

 this Library creats object getting an api as input
    and either a city name or lat and lon coordinates.

    package use example:

    # Creats a weather object using city name.
    # Get your own Api key from https://openweathermap.org
    # And wait for a couple of hours for the key to be activated.

    >>> weather1 = Weather(apikey="Your_Key", city="Madrid")

    # using lat and lon coordinates(*please enter actual coordinates)
    >>> weather2 = Weather(api_key="Your_key", lat=41.1, lon=-4.1)

    # Get complete whether data for next 12 hours:
    >>> weather1.next_12h()

    # simplified data for next 12 hours:
    >>> weather1.next_12h_simplefied()

    # Sample url to get the sky condition icons:
    https://openweathermap.org/img/wn/10d@2x.png
