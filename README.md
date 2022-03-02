# APD Updated - March Term

We will be practicing the basics of JavaScript. Module 1 will discuss api's and github.

[:old_key: GitHub Key terms](/Github.md)
### Branches
main - module 1 information


**IEEFY - This branch contains an example of usinge the IEEFY methodology.**
```
(() => {
    //Write functions here
})()
```

**Functions - Syntax**
```
function getInfo(){
    //Make it do something
}
getInfo();
```

**Variable - Syntax**
```
const url = "https://www.blahblahbblah.com";
```

**Fetch - Syntax**
```
function getMovie(){
    fetch('http://example.com/movies.json')
        .then(response => response.json())
        .then(data => 
            console.log(data)
            displayMovie(data)
        );
        .catch(err => console.log("This is an error", err);
}
getMovie();
```

**Display API Information in the HTML**
```
function displayMovie(data){
    //Your code here
}
```

**Event Listeners**
```
HTML:
<button type="submit" id="btn" onclick="getMovie()">Click</button>
JS: 
varname.addEventListener("click", ...);
```