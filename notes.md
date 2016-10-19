response.send(param) // param gets sent as http response body

response.sendFile(fileName) //file gets sent as HTTP Response bosy
// fileName is the file path as strong

response.render(fileName, dataObject)

//It will run EJS Engine with the file(fileName), you can also optionally
//send dara to the template

// and then render will response.send(resultHtmlString) to the browser/client
