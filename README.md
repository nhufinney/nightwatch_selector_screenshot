# Nightwatch

UI automated testing framework powered by [Node.js](http://nodejs.org/). It uses the [Selenium WebDriver API](https://code.google.com/p/selenium/wiki/JsonWireProtocol).

[![Build Status](https://travis-ci.org/nightwatchjs/nightwatch.svg?branch=master)](https://travis-ci.org/nightwatchjs/nightwatch) [![NPM version](https://badge.fury.io/js/nightwatch.png)](http://badge.fury.io/js/nightwatch) [![Coverage Status](https://coveralls.io/repos/nightwatchjs/nightwatch/badge.svg?branch=master&service=github)](https://coveralls.io/github/nightwatchjs/nightwatch?branch=master)

***

Run the test:

(Make sure Java and Node.js are latest versions; web browsers such as Chrome and Firefox are alreay installed.)

(Create framework testing similar to "nightwatch.json" and test script similar to "example_test.js")

(In this repo, nightwatch automatically controls selenium so do not need to start selenium manually).

In terminal:
	
	$ cd nightwatch/bin
	
	$ npm install
		
Run test command:

	$ bin/nightwatch -t examples/tests/google.js
	
After run the test command, see result in directory: ./test/screenshots/
