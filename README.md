Clone your Save Jeopardy Data as a JSON File project to your local machine, if it isn't already there.
Install Express.js (npm install express).

require Express in your index.js or app.js file.
Use the JSON middleware: app.use(express.json()). (1 point)

Use Express' app.get('/api/category/:id', callback) method to listen for an HTTP request. (4 points)

In your callback function for that method, find a category in your JSON file by its ID (req.params.id). Then send back an HTTP response containing that category (res.send(category)). (4 points)

Use app.listen() to keep your server running in the background on a port. (1 point)

Submit your repos individually.

By the end of this activity, you should be able to use this endpoint instead of jservice.io/api/category?id=.
