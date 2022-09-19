dojo-frontend-template
=================================

**Installation and Startup**

1. Clone repo:

  ``git clone git@github.com:reustleco/dojo-frontend-template.git``

2. Use node v12.x.

   The micro-frontend build scripts support node 12.  Using other major versions of node *may* work, but is unsupported.  For convenience, this repository includes an .nvmrc file to help in setting the correct node version via `nvm <https://github.com/nvm-sh/nvm>`_.

3. Install npm dependencies:

  ``cd dojo-admin-dashboard && npm install``

4. Update the application port to use for local development:

   Default port is 9090. If this does not work for you, update the line `PORT=9090` to your port in all .env.* files

5. Start the dev server:

  ``npm start``

The dev server is running at `http://localhost:9090 <http://localhost:9090>`_ or whatever port you setup.
