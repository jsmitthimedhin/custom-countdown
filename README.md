# custom-countdown
This Custom Countdown allows users to input an event name and a date to count down to from today's date. 

I used the getTime() function to retrieve the input date's standard milisecond(s). I then converted it to variables of seconds, minutes, hours, days using the documentation and allowed it to populate the UI. Since the return data is static, I created function that would allow me to re-run the function every second to allow the UI to look like it's "counting down." 

I then created a "completion" element which shows after the countdown runs out, and after that, a "reset" button which takes the user back to the original input data page. Finally, I used local storage to store the user's input date so they can return to the web page and see the countdown progressing. Of course, this could be overrun by pressing the reset button, which brings the user back to the original page.

The video background is taken from Pixabay's "Mikkehouse." The tutorial of the project was done by Jacinto Wong.
