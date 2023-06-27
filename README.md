# Ping-Pong API 🏓

REST API for testing your frontend app without the need for developing complex APIs.

## Function

This REST API has only one endpoint with two methods.
| Endpoint | Method | Response |
| -------- | ------- | ------- |
| / | GET | "Hello World" |
| / | POST | `Contents of the request` |

It was named ping-pong because when you POST something, it returns it to you.😀🏓

## Usage

1. Clone this repo and go into its directory.
   1. `git clone github.com/omarxadel/pingpong-api`
   2. `cd pingpong-api`
2. `npm install`
3. `npm start`

and voila! You can send your requests from your frontend app to localhost:`PORT` (default PORT value = 8080)
