![](https://github.com/yamitcar/stringCalculator/workflows/Ruby/badge.svg)

para ver el reporte de analisis de codigo:

https://yamitcar.github.io/stringCalculator/overview.html#


### Para el setup sin docker:

install ruby 2.6.5

Setup:
	sudo apt-get install phantomjs

on the project root:
	gem install bundler
	bundle install

to run app:
	ruby app.rb

for unit test:
	rspec

for acceptance test:
	cucumber