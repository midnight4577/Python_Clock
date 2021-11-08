# A basic python clock
A clock coded in python based around pygame

Features:
Weather
Time
Date

**Libraries required:**

Pygame:
```console
$ python3 -m pip install -U pygame --user
```

time:
Should already be installed with python

requests:
```console
$ python -m pip install requests
```

json:
```console
$ python -m pip install json
```

io:
Should already be installed with python

If these don't work check out: https://www.raspberrypi.org/documentation/linux/software/python.md

In the python file you need to change lines 21, 27 to include your city and a open weather map API key (https://openweathermap.org/). If you are using open weather map with anything else make sure that you are able to call for info once per minute as that is the rate at which the weather data is updated.**

Also about half the code is from stack overflow and other some other opensource sources so thank you to all the people who made their code available to public domain.
