# Employee Handbook: #

This handbook contains a number of the company policies and procedures all in one place. By using GitHub they can be updated easily and are always the latest version. All these documents can be viewed as a website through a browser.


## Development Environment:  ##

The handbook can be run locally by: 
1. Clone the handbook repository to your machine.
2. Open PowerShell.
3. Navigate to the root directory of the handbook repository on your machine.
4. Enter the following Docker command, making sure the backticks aren't present when running:

`docker run --rm --label=jekyll --volume=" FILE PATH TO CURRENT DIRECTORY ":/srv/jekyll  -it -p 4000:4000 jekyll/jekyll jekyll serve`

5.Using a browser, enter `localhost:4000` to see the website.

