title 0.5: Single page app

note over browser:
The user navigates to the page
end note

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa
server-->browser: HTTP 200

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
server-->browser: HTTP 200
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa.js
server-->browser: HTTP 200

note over browser:
The browser executes spa.js which requests data.json
end note

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json
server-->browser: HTTP 200

note over browser:
spa.js renders the received json to the DOM
end note