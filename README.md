# Live Server for JavaScript

## A simple script to make life easier for JavaScript developers

It automatically reloads your projects in the browser whenever you change a file.

Works on every Linux shell out there (it's POSIX).

Runs in the background so it doesn't get in your way.

### Pre-requisites

- A browser;

- Node.js;

- Live-server from NPM package manager.

  ``npm i live-server``
  
### How to use

0. Clone the repository:

``git clone https://github.com/oguilhermefigueiredo/liveserver-javascript.git``

1. Move the **live** script for one of the directories listed at
``echo $PATH``, like:

 ``sudo mv live /usr/local/bin``

2. Go to a folder where your project is stored.

3. Type ``live`` and watch the magic happen.

4. Type ``live stop`` and watch the magic disappear.

