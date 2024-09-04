
# IITG Connect

A brief description of what this project does and who it's for


## Demo

- [demoLink](https://www.loom.com/share/3c07238208764a6cafe9208a76b53af3?sid=8d29f8af-d216-4da6-9ddc-9bf605d5d09b)



## Features

- displays the shortest distance between source and destination.
- displays shortest path one must take to reach destintion with minimum distance

## API Reference

#### Get shortest distance between node A and node B 

```http
  GET /shortd/<int:A>/<int:B>
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `source` | `integer` | **Required**|
| `destination` | `integer` |     **Required**      |




## Tech Stack

**Client:** React

**Server:** Flask, Python


## Used By

This project is used by the following:

- Students of IIT Guwahati


## FAQ

#### How will obtain my shortest path from source to destination?

Every possible source and destination is mapped with a number ranging from (1 to 64). Path in the application will display the nodes in order to reach the destination. 
