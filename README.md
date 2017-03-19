# PuerMockServer
mock server based on PuerMock

## install

1. clone the repository
```
git clone https://github.com/TangJiong/PuerMockServer.git
```

2. install puer globally
```
npm install puer -g
```

3. go to PuerMockServer project directory and run
```
npm install
```

4. run and start, in project directory
```
npm run start
```

## usage

1. add new mock api

just edit ```_mockserver.json```, add new api object under api property

```javascript
{
  "method /path/to/your/api": {
    "response": {
      "key1": "value",
      "key2": "@somemockvalue"
    }
  }
}
```

2. now you can access your api with ```localhost:8000/path/to/your/api``` get mock data as you defined

3. more mock value @see[Mockjs](http://mockjs.com/examples.html)

## thanks to

* [ufologist/puer-mock](https://github.com/ufologist/puer-mock)
