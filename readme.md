Here's how to quickly run a local server to resolve the CORS issue. You can use any of these commands depending on what you have installed:

If you have Python 3:

python -m http.server 8000

Copy

Execute

If you have Python 2:

python -m SimpleHTTPServer 8000

Copy

Execute

If you have Node.js installed:

npx serve

Copy

Execute

If you have PHP:

php -S localhost:8000

Copy

Execute

Then open your browser and navigate to:

http://localhost:8000

Copy

Execute

This will serve your files properly and resolve the CORS error, allowing the ES modules to work correctly.