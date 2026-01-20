# ESP32 OXIMETER

## Connections beetwen esp32 and maxim max30102
MAX30102 Vin   ->   3v3

MAX30102 GND   ->   GND

MAX30102 SDA   -> GPIO33

MAX30102 SCL   -> GPIO32


## Flashing the code
Afer connecting everything up plug you esp32 to the pc and then in the project directory terminal run these commands:

```
idf.py fullclean

idf.py flash
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
