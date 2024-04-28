React Day 1: 20-04-2024

React:
-React is used to build the single page web application[Only one HTML file is used]
-Using DOM and VDOM manipulation.

Promise:
-Promise is used to run a Asynchronous process to synchronous process.

const P1= new Promise ((resolve,reject)=>
{
    console.log("Promise Running...");
   setTimeout(()=>
   {
       resolve("Hello");
   },10000); 
});

P1.then(res=>
{
    console.log(res)
});
