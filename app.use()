# Node JS routing issue

## app.use()

Date: March 13

### Description

Deployed a node app to glowhost, link:

http://judao.hans.systems/COMP4537/personal_project/

There is a routing problem that blocks the visit of the application.

### Error Display:

Cannot GET /

### Related Code:

```js
app.get(current_dir +'/', (req, res) => {
    res.sendFile(__dirname + '/public/index.html')
    console.log(connection)
})
```

## Steps to Solve

### Step 1

Prepended path to the APIs 

```js
const current_dir = '/COMP4537/personal_project/'
```

```js
app.get(current_dir +'/', (req, res) => {
    res.sendFile(__dirname + '/public/index.html')
    console.log(connection)
})
```

