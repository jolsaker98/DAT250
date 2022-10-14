# Report expass6

In particular, you should write about:

- technical problems that you encountered during the completion of the tutorial

- a link to your code for experiments 1-3 above

- any pending issues with this assignment which you did not manage to solve

Used bootstrap to easily style the form, table, and others

## Links to experiments

[Experiment 1](https://github.com/jolsaker98/Dat250-expass6-experiment1)

[Experiment 2](https://github.com/jolsaker98/angularSPA)

<img width="1440" alt="Screen Shot 2022-10-14 at 5 07 04 PM" src="https://user-images.githubusercontent.com/111968598/195882642-6329a5b1-9724-4ca8-905f-abafea106943.png">

<img width="1440" alt="Screen Shot 2022-10-14 at 5 07 16 PM" src="https://user-images.githubusercontent.com/111968598/195882669-bf684b5b-0e51-4fb9-b42a-c90ca0d19d98.png">

<img width="1440" alt="Screen Shot 2022-10-14 at 5 10 21 PM" src="https://user-images.githubusercontent.com/111968598/195882688-2375796d-666d-4de6-b45a-93122d8310d3.png">


## Issues with the assignment

Like most people with this assignment I encountered the CORS error. I used a long time on this and still have one pending issue with the assignment. I followed the CORS article that was published by the teacher. This fixed the get request so that I could get the information from the api to the spa. You can then press the refresh button and then get the result from postman or the api into the table. The problem was that the post request did not get fixed by any of the fixes. I tried a lot of different solutions, even adding "before((req, res) -> res.header("Access-Control-Allow-Origin", "*"));" to the todo api to help, but this only works for the get request. So the post request or the add button is not working properly. 
