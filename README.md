# TIL
Coding concepts that I learn everyday
# 08/27/20 Thursday
Today I learned how to make an environment variable in my shell configuration file
This is how you do it...

Open the shell configuration file
```
code ~/.bash_profile
```
Make an environment variable
```
export OPEN_WEATHER_API_KEY=____
```
Restart your terminal

Modify the script to use the ENV hash
```
response = HTTP.get("https://api.openweathermap.org/data/2.5/weather?q=chicago&units=imperial&APPID=#{ENV["OPEN_WEATHER_API_KEY"]}")
```

# 08/26/20 Wednesday

# 08/25/20 Tuesday

# 08/24/20 Monday
Today I learned about the the built in array object method "include?"
With this method you can search through an array for an object.
The method will return true if found and false if not.

``
array = ["one", "two", "three", "four"]
array.include?("two")

Output => true
``
