# Class-08 

``` js

While Loop 

let count = 1;
while(count <= 10) {
console.log(count)
count = cound + 1
} 

For Loop 

For( let i = 1; i <= 10; i++) { 
console.log (i);

++ adds 1

— take away 1


function getDuck() {
let output = ""
 let ducks = prompt("How many ducks you going to Mint ");

 let duckMessage

if (ducks < 5){
    duckMessage = "Little Duckling"
}
else if (ducks > 10) {
    duckMessage = "Duck Whale"
}

else {
    duckMessage = "Quack Quack "
}

for ( let i = 0;i < ducks; i++) {
    output = output + "<img src='duck-01.png' alt='duck' class='duck'/>"
    console.log(i)
}

return document.write(duckMessage + output);

 }


function rating () {
let output = ""
let rating = promt ("pelase rate my questions out of 5");

for (let i = 0; i < rating; i++){
output = output + "<img src='duck-01.png' alt='duck' class='duck'/>"
console.log (i)

}

return docuemnt.write(output)


```



