Objective:
Create a todos app
It can add and delete

Parent Component
Class App with State ->

Child Components
App pass state -> Todos
Todos pass props -> TodoItem

TodoItem
Renders the display of the todos list
Has a unique ID that from props, then we bind the ID to a method on the parent app.
TodoItem method(bind, id) -> Todos -> App

App now has the method of the ID from TodoItem by (bind, id) to setState
IF id === id, then toggle completed to the opposite.