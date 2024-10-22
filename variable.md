
# Variable Guide
## Time
| Variable  | Result | Description |
| ------- |:------:| ----------- |
| {HR_24} | 09 | Hours (24-hour time system) |
| {MN_24} | 41 | Minutes (24-hour time system) |
| {HR_12} | 9 | Hours (12-hour time system) |
| {MN_24} | 41 AM | Minutes (12-hour clock) |

## Date ( TH )
| Variable  | Result | Description |
| ------- |:------:| ----------- |
| {TH_DT_N} | 17 | Date (2 digits) |
| {TH_DT_S} | Thurs. | Name of the day (abbreviated) |
| {TH_DT_L} | Thursday | Name of day (full) |
| {TH_MTH_N} | 10 | Month (2 digits) |
| {TH_MTH_S} | Oct. | Month name (abbreviated) |
| {TH_MTH_L} | October | Month name (full form) |
| {TH_YR_S} | 67 | Year (abbreviated) |
| {TH_YR_L} | 2567 | Year (full) |

## Date ( EN )
| Variable  | Result | Description |
| ------- |:------:| ----------- |
| {EN_DT_N} | 17th | Date (1-2 digits followed by a sequence symbol) |
| {EN_DT_S} | Thu | Name of the day (abbreviated) |
| {EN_DT_L} | Thursday | Name of day (full) |
| {EN_MTH_N} | 10 | Month (1-2 digits) |
| {EN_MTH_S} | Otc | Month name (abbreviated) |
| {EN_MTH_L} | October | Month name (full form) |
| {EN_YR_S} | 24 | Year (abbreviated) |
| {EN_YR_L} | 2024 | Year (full) |

# Weather
> **Reference information : [weatherapi](https://www.weatherapi.com/)**

| Variable  | Result | Description |
| ------- |:------:| ----------- |
| {CTY} | Bangkok | city |
| {REG} | Krung Thep | province |
| {CNT} | Thailand | country |
| {TMP_C} | 27.4 | Temperature (degrees Celsius) |
| {TMP_F} | 81.3 | Temperature (degrees Fahrenheit) |
| {WND_KPH} | 6.5 | Wind speed (kph) |
| {WND_MPH} | 4 | Wind speed (mph) |
| {WND_D} | 67 | Wind direction (degrees) |
| {WND_DIR} | ENE | Wind direction (16-point compass) |
| {PRES_MB} | 1011 | Air pressure (millibar) |
| {PRES_IN} | 29.8 | Air pressure (inches of mercury) |
| {PRCP_MM} | 0 | Rainfall (mm) |
| {PRCP_IN} | 0 | Rainfall (inches) |
| {GST_KPH} | 8.6 | Gust winds (kph) |
| {GST_MPH} | 5.3 | Gust winds (mph) |
| {FEL_C} | 35.4 | Feeling temperature (degrees Celsius) |
| {FEL_F} | 95.6 | Feeling temperature (degrees Fahrenheit) |
| {WCH_C} | 27.4 | Wind chill temperature (degrees Celsius) |
| {WCH_F} | 81.2 | Wind chill temperature (degrees Fahrenheit) |
| {HIDX_C} | 31.3 | Heat index (degrees Celsius) |
| {HIDX_F} | 88.3 | Heat Index (Fahrenheit) |
| {DPT_C} | 24.1 | Dew point (degrees Celsius) |
| {DPT_F} | 75.3 | Dew point (degrees Fahrenheit) |
| {VIS_KM} | 10 | Visibility (kilometers) |
| {VIS_MI} | 6 | Visibility (miles) |
| {HUMT} | 75 | Humidity (percent) |
| {CLD} | 25 | Cloud cover (percent) |
| {UV} | 3 | UV Index |
| {CO} | 1365.3 | Carbon monoxide (micrograms/cubic meter) |
| {NO2} | 36.8 | Nitrogen dioxide (micrograms/cubic meter) |
| {O3} | 78 | Ozone (micrograms/cubic meter) |
| {SO2} | 42.5 | Sulphur dioxide (micrograms/cubic meter) |
| {PM2_5} | 134.9 | PM2.5 (micrograms/cubic meter) |
| {PM10} | 193 | PM10 (micrograms/cubic meter) |

# System
| Variable  | Result | Description |
| ------- |:------:| ----------- |
| {PING} | 336 | Ping of Client |
| {PATCH} | 1.0.0 | Patch of Code |
| {CPU_NANE} | Intel(R)... | Name of CPU |
| {CPU_CORES} | 4 | Cores of CPU |
| {CPU_SPEED} | 2.0 | speed CPU (GHz) |
| {CPU_USAGE} | 40 | CPU usage (percent) |
| {RAM_USAGE} | 69 | RAM usage (percent) |
| {UPT_DAY} | 2 | Show work (days) |
| {UPT_HOUR} | 15 | Show work (hours) |
| {UPT_MIN} | 10 | Show work (minutes) |
| {UPT_SEC} | 50 | Show work (seconds) |
| {COUNT} | 140 | Number of page flips |

# User
| Variable  | Result | Description |
| ------- |:------:| ----------- |
| {USER_NAME} | in love w/ you | Name of Client |
| {USER_ICON} | URL | Picture of Client (customstatus not working) |
| {USER_BANNER} | URL | Banner of Client (customstatus not working) |
| {GUILD_MEMBER(GUILD_ID)} | 500 | Number of members on the server |
| {GUILD_NANE(GUILD_ID)} | 𝐏𝐒𝐐𝐃 𝐒𝐄𝐑𝐕𝐄𝐑 | Server name |
| {GUILD_ICON(GUILD_ID)} | URL | Server image (customstatus not working) |

# Emoji
| Variable  | Result | Description |
| ------- |:------:| ----------- |
| {EMOJI_RANDOM} | 🪐 | Random Emoji |
| {EMOJI_TIME} | 🌙 | Early morning emoji by time |
| {EMOJI_CLOCK} | 🕗 | Clock Emoji by Time |

# Function
| Variable  | Result | Description |
| ------- |:------:| ----------- |
| {RANDOM(TEXT)} | TEXT | Random text as specified. Example {RANDOM(1,2,3,4,5,)} Random number from 1-5 |
| {UPPERCASE(text)} | TEXT | Convert text to uppercase |
| {LOWERCASE(TEXT)} | text | Convert text to lowercase |
| {F1(TEXT)} | > | ๐-๙ ( Number only ) |
| {F2(TEXT)} | > | 𝕒-𝕫 𝔸-ℤ 𝟘-𝟡 |
| {F3(TEXT)} | > | 𝗮-𝘇 𝗔-𝗭 𝟬-𝟵 |
| {F4(TEXT)} | > | 𝐚-𝐳 𝐀-𝐙 𝟎-𝟗 |
| {F5(TEXT)} | > | 𝟶-𝟿 ( Number only ) |
| {F6(TEXT)} | > | 𝟢-𝟫 ( Number only ) |
