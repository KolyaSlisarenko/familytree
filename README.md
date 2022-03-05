# Structure

```javascript
  {
    "id": <number>,
    "name": <string>,
    "surname": <string>,
    "date_of_birth": <string>,
    "date_of_death":  <string>,
    "pids": [<number>],
    "mid": <number>,
    "fid": <number>,
    "photos": [<string>]
  },
```

### id: the unique identifier of the person
### pids: are the partner ids, represents the connection between two partners (wife and husband).
### mid: mother id.
### fid: father id.
### photos: array of photos for the gallery. the first photo is used for three!