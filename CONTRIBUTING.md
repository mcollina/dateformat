# Contributing to dateformat

Thanks for taking the time to contribute to dateformat!!!
Feel free to raise a PR or Issue for any suggested improvements to the package.

## Running dateformat

To run dateformat, first clone the repository to your local machine.  
Then run `npm i` to install all the required dependencies.  
Then you can import dateformat from the `lib` directory and call it as needed.

## Benchmarking

If you want to try and improve the performance of dateformat, you can use the benchmarking script.  
To use the script:

- Copy the contents of the `lib/dateformat.js` file into the `benchmark/previousDateFormat.js` file.
- Make your code changes to `lib/dateformat.js` as you normaly would
- run `npm run benchmark` in root directory to see the comparison of performance before and after your change

A positive number for improvement indicates that your changes have improved the speed of dateformat.  
Any different between -5% and 5% can be disregarded as minor variance.  
It is recommended that you run this benchmark after any changes to the business logic of dateformat.  
This is to ensure that there is no detrimental impact on performance from your change.  
A screenshot it the PR would be much appreciated also.

## Running Tests

To test dateformat, just run `npm run test` and see the results.
