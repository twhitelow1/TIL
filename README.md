# TIL
Coding concepts that I learn everyday
# 08/30/20 Sunday
I think I solved a lot of my social icon issues from now on. There is this awesome CDN called fontawesome and they have text based icons that can be easily placed with an italics html tag!

```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
```

Then you can call the <github> icon here
```html
<i class="fab fa-github"></i>
```

# 08/27/20 Thursday
Today I learned how to make an environment variable in my shell configuration file
This is how you do it...

Open the shell configuration file
```bash
code ~/.bash_profile
```
Make an environment variable
```bash
export API_KEY = insert_api_key
```
Restart your terminal

Modify the script to use the ENV hash
```bash
puts ENV["API_KEY"]
>> insert_api_key
```

# 08/24/20 Monday
Today I learned about the the built in array object method "include?"
With this method you can search through an array for an object.
The method will return true if found and false if not.

```ruby
array = ["one", "two", "three", "four"]
array.include?("two")

Output => true
```
