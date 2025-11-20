# Prompt used to create the initial plan

Your task is to plan the construction of a ToDo web application with a simple yet stunning UI, that includes a login page and a main application page for managing todos (listing, creating, deleting, marking as done etc). The application should be built using Python, FastAPI and HTMX.

## Basic App Requirements
- Implement only using web standards like HTML, CSS, JS etc
- Do NOT use any JavaScript framework, JavaScript Toolchains, Node modules etc
- It's ok to use UI component libraries and animation libraries that can be served via a CDN
- Use a templating library such as jinja2 (if you find something better/more suitable, use that).
- Templates should be stored as HTML files, not in code
- Use a lightweigt UI Component library like for instance Shoelace (https://shoelace.style/), but also look at other possible options.
- Use modern Python, and uv for dependency and project management
- Make proper use of HTMX for optimal interactivity (i.e. avoiding full screen reloads etc.)
- Use Supabase for data storage and authentication
- Use appropriate client libraries for database/supabase access
- Build a domain model that ta least includes concpts like users, todos, todo-lists etc. A todo should at least have fields for title, note, completion flag, completion date etc. 
- Do not use Docker - the application should be runnable just using the command line or in an IDE
- Create a few basic tests, if and where it makes sense (and can be done without connection to database)

## Other Considerations
The main purpose of this project/application is to server as an educational lab project, for use in workshops around AI coding agents. 
Additionally, the end goal is to create ports to other languages/frameworks of this application, after completion, so keep that in mind when selecting dependencies, making architecture/design decisions etc. One potential lab excercise could actually be to create a port of this project to another language/framework using an AI codig agent.

## Inspiration
Here as some repositories that can serve as a basis/inspiration, but do not limit yourself to these:
- https://github.com/eladgunders/fastapi-todos
- https://github.com/patrickloeber/flask-todo
- https://github.com/AtticusZeller/fastapi_supabase_template

## Plan
Do extensive research on examples on how to build such an app and asking me follow-up questions when needed. Don't start implementation right away - create and store the plan first.
