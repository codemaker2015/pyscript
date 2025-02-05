# PyScript Demonstrator

A simple webapp to demonstrate the capabilities of PyScript.

## Getting started

1. If you don't already have Node.js, install it. The official installer for the
   LTS version of Node is available from [nodejs.org](https://nodejs.org/).

2. If you don't already have Rollup, install it. Rollup can be installed as a
   global resource using:

       $ npm install --global rollup

3. Install the demo apps requirements:

       $ npm install

4. Start the server:

       $ npm run dev

   This will compile the resources for the app, and start the development server.

5. When the compilation completes, it will display something like:

         Your application is ready~! 🚀

         - Local:      http://localhost:8080
         - Network:    Add `--host` to expose

       ────────────────── LOGS ──────────────────

   Once this is visible, open a browser at
   [http://localhost:8080](http://localhost:8080). This will provide a list of
   demos that you can run.


   You can take the examples folder and change the `pyscript.js` and `pyscript.css` local reference to the CDN one that mentioned above to run the examples indivitually on the browser.

   **For example:**

   In the hello_world.html file,

   Change the following lines

   ```
   <link rel="stylesheet" href="build/pyscript.js" />
   <script defer src="build/pyscript.js"></script>
   ```

   with remote cdn links.

   ```
   <link rel="stylesheet" href="https://pyscript.net/alpha/pyscript.css" />
   <script defer src="https://pyscript.net/alpha/pyscript.js"></script>
   ```


## More information

There is a forum PyScript where you can discuss the project or ask questions at [https://community.anaconda.cloud/c/pyscript](https://community.anaconda.cloud/c/pyscript)
