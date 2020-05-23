# Install all node modules mentioned in package.json

    - npm install

# Help on running commands

    - node app.js --help
    - node app.js  add --help
    - node app.js  remove --help
    - node app.js  list --help

# Add  A Note

    - node app.js add --title="name" --body="Ram Adam Singh"

# Remove A Note

    - node app.js remove --title="name"

# List All Notes

    - node app.js list

# Node debug tools
    - 1. console.log
    - 2. node inspect + chrome V8 (Debug point)
        - e.g: node inspect app.js add --title="name" --body="Ram Adam Singh"
        - chrome://inspect
        - Click on inspect
        - Set the debug point and proceed debugging