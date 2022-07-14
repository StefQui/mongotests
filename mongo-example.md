### Source
```
[
  {
    "id": 1,
    "name": "John",
    "designation": "customer"
  },
  {
    "id": 2,
    "name": "Alison",
    "designation": "manager"
  },
  {
    "id": 3,
    "name": "Sam",
    "designation": "customer"
  },
  {
    "id": 4,
    "name": "George",
    "designation": "salesperson"
  },
  {
    "id": 5,
    "name": "Will",
    "designation": "salesperson"
  },
  {
    "id": 6,
    "name": "Daffney",
    "designation": "customer"
  },
  {
    "id": 7,
    "name": "Julie",
    "designation": "salesperson"
  },
  {
    "id": 8,
    "name": "Elliot",
    "designation": "customer"
  },
  {
    "id": 9,
    "name": "Bruno",
    "designation": "customer"
  },
  {
    "id": 10,
    "name": "Omar",
    "designation": "customer"
  },
  {
    "id": 11,
    "name": "Sid",
    "designation": "customer"
  },
  {
    "id": 12,
    "name": "Nelson",
    "designation": "manager"
  }
]
```

## Match

```
db.collection.aggregate([
  {
    "$match": {
      name: "John"
    }
  }
])
```
### Result
```
[
  {
    "_id": ObjectId("5a934e000102030405000000"),
    "designation": "customer",
    "id": 1,
    "name": "John"
  }
]
```

## Header 2
