# Weather-Service-Historical-Data
1. run ServerMain -- essential for MainApp
2. run MainApp -- to start desktop application
3. run Tomcat served -- for web part of api

# DEPENDENCIES
# 1. DesktopGUI
  1. WeatherServiceITF
  
# 2. RestService
  1. WeatherApiAdapter
  2. WeatherService
  3. WeatherServiceITF

# 3. WeatherApiAdapter
  1. WeatherService
  2. WeatherServiceITF

# 4. WeatherServer
  1. WeatherService
  2. WeatherServiceITF
  3. WeatherApiAdapter

# 5. WeatherService
  1. WeatherServiceITF

# 6. WeatherServiceITF
