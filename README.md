<p align="center">
  <a href="https://www.netlolo.com">
      <img src="https://app.netlolo.com/images/logo_vertical.png" alt="Netlolo"/>
  </a>
</p>

## Challenge for Backend Developer

A customer needs to search in our orderbook (available in this <a href="https://github.com/NetloloIncubadora/challenge/blob/master/orderbook.json">JSON</a>) and he wants to buy offers below some price also sell offer offer to recieve some money.
Based on this you will need to develop:

- a simple API to search offers in the .json available;
- it should be possible to search for offer by their amount (one or more);
- it must be possible to order the result by price (asc and desc);

The test should be done in Node(ECMAScript6). We expect at the end of the test, outside the API running, the following items:

- an explanation of what is needed to make your project work;
- an explanation of how to perform the tests;

Remember that at the time of the evaluation we will look at:

- Code organization;
- Object-Oriented Principles;
- Maintenance;

To send us your code, you must:

Make a fork of this repository, and send us a pull-request.


## Running the enviroment

To install and test the app please follow theses rules.

- Run "npm install"
- Run "npm test"

If you want to use the endpoint on the browser or some app like 'postman' 

- Run npm start

And access the following endpoints through GET: 
- /ask
- /bids

You can also send some query string parameters like:

- sort
- amount 

Server will be running at port 3000
Please make sure that these port is available or change it by changing the file config/app.js


Thanks for the opportunity.

 

Regards,

Arthur Moro.
