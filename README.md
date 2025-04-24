# QueryMongoDB

{isActive: true}

{ "age": { "$gt": 26 } }

{ age: {$gt: 26, $lte: 30}}

{ "eyeColor": { "$in": ["blue", "brown"] } }

{ "eyeColor": { "$nin": ["green", "blue"] } }

Filtro { "company": "FITCORE" }, Project { "email": 1, "_id": 0 }
