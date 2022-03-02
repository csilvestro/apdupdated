# apdupdated - March Term

## This repo is for additional help. 

### GitHub Key terms
[GitHub Helpful Terms](/Github.md)


### IEEFY - This branch contains an example of usinge the IEEFY methodology.
(() => {
    //Write functions here
})()

### Functions - Syntax
function getInfo(){
    //Make it do something
}
getInfo();

### Variable - Syntax
const url = "https://www.blahblahbblah.com";

### Fetch - Syntax
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

### Display API Information in the HTML
function displayMovie(data){
    //Your code here
}

### Branches
01_FetchAPI
dev - my working branch