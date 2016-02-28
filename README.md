#Colorizr Mini Gem
**Version 0.0.1**

####Function
This Gem will alter the color of strings printed in the terminal.

####How To Use It
The following methods can be called on String objects:
* red
*  green
*yello
* blue
* pink
* light_blue
* white
* light_grey
* black

######For Example
```ruby
puts "John".red
puts "Paul".green
puts "George".blue
puts "Ringo".yellow
```

The following methods can be called on the String class:
* sample_colors
* colors

```ruby
p String.colors
=> [:red, :green, :yellow, :blue, :pink, :light_blue, :white, :light_grey, :black]

String.sample_colors
=> This is red
This is green
This is yellow
This is blue
This is pink
This is light_blue
This is white
This is light_grey
This is black
```
####How to Install
```ruby
gem install colorizr-0.0.2
```



