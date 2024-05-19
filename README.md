# timer_module
timer module for website

This module is intended to implement a timer on a website page. The module is implemented in a native JavaScript, using the ES6 standard.

Usage:

1. Set up your HTML markup:
```
   <div class="your class timer">
      <div>
          <span class="your class days">00</span>
      </div>
      <div>
          <span class="your class hours">00</span>
      </div>
      <div>
          <span class="your class minutes">00</span>
      </div>
      <div>
          <span class="your class seconds">00</span>
      </div>
  </div>
```

2. Сopy the code from the timer.js file to your separate timer file

3. Import using command 'import timer from ...' in your main file 'main.js'

4. In the main file call the function timer({}) inside which, as a parameter, pass an object with the following properties:
```
	timer({
		timer: 'your selector timer',
		time: 'your timer end date', (for example: '2024-05-20')
		days: 'your selector days',
		hours: 'your selector hours',
		minutes: 'your selector minutes',
		seconds: 'your selector seconds'
	});
```
