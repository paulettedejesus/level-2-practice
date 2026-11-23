# Week 5 Day 2 — Three requests, side by side

Fill this in from Postman or Bruno. **Never paste your API key in this file.**
This repo is public: anyone on the internet can read it.
Write `{{gemini_key}}` (the variable's name) instead.

| | Weather request | AI request | Add a dish |
| --- | --- | --- | --- |
| Method (GET / POST) | GET | POST | |
| Endpoint (the address, filled in for you) | `https://api.open-meteo.com/v1/forecast` | `https://generativelanguage.googleapis.com/v1beta/models/gemini-3.8-flash:generateContent` | `https://dummyjson.com/recipes/add` |
| Where the details go (query params or body?) |QUERY |BODY (JSON) | |
| Headers I needed |NONE | (x-goog-api-key)KEY AND ({{gemini_key}})VALUE| |
| Does it need a key? |No |Yes | |
| Status I got |200 OK | 200 OK| |
| The part of the response I care about (the path, like `current.temperature_2m`) | "https://api.open-meteo.com/v1/forecast?latitude=35.22709&longitude=-80.84313&hourly=temperature_2m,wind_speed_10m&current=temperature_2m" |  "content": "parts":"text": "The Wandering walnut", | |

## What was different?

Write 2–3 sentences in your own words.
The AI request and Add a dish are both POST. What job does each one do?
THE POST FOR AI REQUEST ASKS GEMINI TO GIVE AN ANSWER



## Did my dish really save?

What status did `Get my dish` give you? What does that tell you? 


## Extra (if you finish early)

- Send the same prompt twice. Is the answer the same? Why might that be?
- Try a different model name in the address. What changed in the response?
