# ChickenRun
Chicken Run API for Clac des Doigts

This API provides endpoints to create, modify, delete and make run a chicken.

The endpoints are the following :
- GET ('/chicken') -> Return return all chicken details (Name, BirthDay, Weight, Steps, isRunning)
- POST ('/chicken') -> Create a new chicken if none exists; Minimal parameters required are Name and Weight
- PUT ('/chicken') -> Create a new Chicken if none exist; else, update it
- PATCH ('/chicken') -> Update the existing chicken with the given parameters
- DELETE ('/chicken') -> Delete the existing chicken
