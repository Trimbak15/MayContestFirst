# MayContestFirst
The task involves fetching data from three APIs and displaying it in a table format.


I recently completed a task where I implemented a promise chain to fetch data from three APIs and display it in a suitable UI. The process was initiated by clicking a button with an onClick listener.
![Contest1](https://github.com/Trimbak15/MayContestFirst/assets/118504736/c72bfdf9-1627-4f59-bf22-76e8e4a8359e)

In the promise chain, I created three functions, namely PromiseAPI1(), PromiseAPI2(), and PromiseAPI3(), each of which returned a promise. Within each promise, I used setTimeout to simulate delays of 1000ms, 2000ms, and 3000ms, respectively. During each setTimeout, I fetched data from the corresponding API endpoint and displayed it on the screen.
![contest2pic](https://github.com/Trimbak15/MayContestFirst/assets/118504736/866443ef-51f5-4857-8683-8b7bbfc6550a)

To ensure the sequential execution of promises, I resolved each promise with resolve(true) once the data was fetched and displayed. Before returning the next promise, I implemented an if condition to check if the previous resolve was true. This ensured that the chain progressed only when the previous promise was resolved.

I implemented the promise chaining using either the ".then()" method or async/await syntax. This allowed for a streamlined and organized flow, making the code more readable and maintainable.

Overall, it was a successful implementation of promise chaining to fetch data from multiple APIs and display it dynamically in a table-like UI.


