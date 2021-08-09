rafce will add a function component snippet

impt will add imports prop types for defining specific types of props

NPM
npx create-react-app 'My App'
npm start - starts the app
npm run build - build the website for deployment (just need to upload the build folder)
npm i -g serve - install local http server for running the build version
serve -s build -p 8000 - run the build version on port 8000
npm i json-server - installs a server that creates a fake backend for working with json
add to package.json file ("server": "json-server --watch db.json --port 5000")
npm run server - to run the json server
npm i react-router-dom - used for routing since react doesn't have it's own unlike angular


{
      "id": 1,
      "text": "Doctors Appointment",
      "day": "Feb 5th at 2:30pm",
      "reminder": true
    },
    {
      "id": 3,
      "text": "Food Shopping",
      "day": "Feb 5th at 2:30pm",
      "reminder": false
    },
    {
      "text": "Take Test",
      "day": "Friday",
      "reminder": false,
      "id": 5
    }