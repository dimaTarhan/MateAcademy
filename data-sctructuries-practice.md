```javascript
const cats = [
  {
    'id': 1,
    'name': 'simon',
    'category': 'fast',
    'price': 100,
    'img_url': 'https://storage.googleapis.com/ck-kitty-image/0x06012c8cf97bead5deae237070f9587f8e7a266d/495636.svg',
    'available': true,
    'created_at': '2018-02-06T23:08:49.179Z',
    'updated_at': '2018-02-06T23:08:49.179Z',
  },
  {
    'id': 2,
    'name': 'felix',
    'category': 'fast',
    'price': 10000,
    'img_url': 'https://storage.googleapis.com/ck-kitty-image/0x06012c8cf97bead5deae237070f9587f8e7a266d/495625.svg',
    'available': true,
    'created_at': '2018-02-06T23:08:49.186Z',
    'updated_at': '2018-02-06T23:08:49.186Z',
  },
  {
    'id': 3,
    'name': 'luna',
    'category': 'slow',
    'price': 2000,
    'img_url': 'https://storage.googleapis.com/ck-kitty-image/0x06012c8cf97bead5deae237070f9587f8e7a266d/495622.svg',
    'available': true,
    'created_at': '2018-02-06T23:08:49.190Z',
    'updated_at': '2018-02-06T23:08:49.190Z',
  },
  {
    'id': 4,
    'name': 'oliver',
    'category': 'fast',
    'price': 9000,
    'img_url': 'https://storage.googleapis.com/ck-kitty-image/0x06012c8cf97bead5deae237070f9587f8e7a266d/495619.svg',
    'available': true,
    'created_at': '2018-02-06T23:08:49.193Z',
    'updated_at': '2018-02-06T23:08:49.193Z',
  },
  {
    'id': 5,
    'name': 'oreo',
    'category': 'middle',
    'price': 100,
    'img_url': 'https://storage.googleapis.com/ck-kitty-image/0x06012c8cf97bead5deae237070f9587f8e7a266d/495616.svg',
    'available': true,
    'created_at': '2018-02-06T23:08:49.197Z',
    'updated_at': '2018-02-06T23:08:49.197Z',
  },
  {
    'id': 6,
    'name': 'molly',
    'category': 'slow',
    'price': 3000,
    'img_url': 'https://storage.googleapis.com/ck-kitty-image/0x06012c8cf97bead5deae237070f9587f8e7a266d/495613.svg',
    'available': true,
    'created_at': '2018-02-06T23:08:49.201Z',
    'updated_at': '2018-02-06T23:08:49.201Z',
  },
  {
    'id': 7,
    'name': 'simba',
    'category': 'fast',
    'price': 11000,
    'img_url': 'https://storage.googleapis.com/ck-kitty-image/0x06012c8cf97bead5deae237070f9587f8e7a266d/495592.svg',
    'available': true,
    'created_at': '2018-02-06T23:08:49.205Z',
    'updated_at': '2018-02-06T23:08:49.205Z',
  },
  {
    'id': 8,
    'name': 'jack',
    'category': 'middle',
    'price': 5000,
    'img_url': 'https://storage.googleapis.com/ck-kitty-image/0x06012c8cf97bead5deae237070f9587f8e7a266d/495579.svg',
    'available': true,
    'created_at': '2018-02-06T23:08:49.209Z',
    'updated_at': '2018-02-06T23:08:49.209Z',
  },
  {
    'id': 10,
    'name': 'loki',
    'category': 'fast',
    'price': 20000,
    'img_url': 'https://storage.googleapis.com/ck-kitty-image/0x06012c8cf97bead5deae237070f9587f8e7a266d/336916.svg',
    'available': true,
    'created_at': '2018-02-06T23:08:49.216Z',
    'updated_at': '2018-02-06T23:08:49.216Z',
  }];
```

### Tasks:
  0. Write function `printCat` which accept cat object and show his `id` and `name` in console in any way. 
  1. Create function `printCats` which iterate over all cats and print them using `printCat` function;
  2. Create a new array with cats `name`, `id` and `category` and print these cats.
  3. Filter cats with price more than 8000 and print them 
  4. Group Cats by category (slow, middle, fast). The final result should like:

```javascript
 {
  slow: [
    {
      'id': 1,
      'name': 'simon',
      'category': 'slow',
      'price': 100,
      'img_url': 'https://storage.googleapis.com/ck-kitty-image/0x06012c8cf97bead5deae237070f9587f8e7a266d/495636.svg',
      'available': true,
      'created_at': '2018-02-06T23:08:49.179Z',
      'updated_at': '2018-02-06T23:08:49.179Z',
    }
    ...
  ],
  middle: []
  fast: []
 }
```
