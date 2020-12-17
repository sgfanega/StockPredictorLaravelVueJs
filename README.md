<p align="center">
    <a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a>
    <a href="https://vuejs.org" target="_blank"><img src="https://vuejs.org/images/logo.png" alt="Vue logo"></a>
</p>


## About Stock Predictor Laravel Vue Js Project
You can tell from the title that this project uses Laravel + Vue.js alongside with my other project, Stock Predictor.

What this project is about is an attempt to use Laravel and Vue.Js together. What I did in the project was create a controller that would run the script of my Python Stock Predictor, create a Chartjs-friendly JSON to pass it to Vue. Once there, I use Vue+Chartjs to create the line graph.

## Important Details
I used WSL2 Ubuntu to run this project, you will need to figure out how to run Laravel on your Web Server, and make sure to make Python and it's modules to have global access. You might encounter issues where the Python script might not run because it is missing modules. If you already have installed the modules required, but it still gives you the same error, it is likely that you did not install Python and the modules needed globally.
Please look at my Stock Predictor project at https://www.github.com/sgfanega/stockpredictor to figure out what modules you will need to install.

## What you need to download
Run `npm init` when you are inside the root folder of the project and it should download everything I used.
