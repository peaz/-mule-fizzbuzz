#Mule FizzBuzz 

Coding FizzBuzz in Mule as a flow, becuase why not?

![flow_image](https://gitlab.com/peaz/mule-fizzbuzz/-/raw/master/src/test/resources/mule-fizzbuzz-flow.png) "The Mule FizzBuzz flow"

This implementation uses vm queues to perform the while loop to count up to the number that is passed in the uri parameter.

The flow listens on http://localhost:8081/fizzbuzz/{count}.
