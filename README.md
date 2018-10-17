//to retrieve attributes of a property
let car = {
name : 'VW',
model : '2017'
};

Object.defineProperty(
car, 'name', 
{value:'VW', 
writable:false}
);

console.log(Object.getOwnPropertyDescriptor(car, 'name'));
