title 0.6: New note in Single page app

note over browser:
The user adds a new note to the form input and clicks on the 'Save' button
end note

note over browser:
spa.js adds the note to the DOM and sends it to the server
end note

browser->server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa

note over server:
The server stores the new note
end note

server-->browser: HTTP 201