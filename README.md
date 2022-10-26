# UFO Sightings

![Screen Shot 2022-10-26 at 11 18 36 AM](https://user-images.githubusercontent.com/110786136/198094405-f8919c95-2efa-4ecd-ba35-d37dd050a6e8.png)

## Overview of Project: 

Customize UFO Sightings webpage using Bootstrap, and equip UFO table with several fully functional filters that will allow users to interact with our visualizations. Analysis of UFO sightings will allow users to filter for multiple criteria at the same time. Filter searching criteria included date, city, state, country, and shape. We used data stored in a JavaScript array to built UFO table and place the table into a HTMLS file for easy viewing.


## Results: 

> ### ***1. When a user access to the UFO webpage they will be able to see the UFO's header, article and table with the date, city, state, country, and shape as a search criteria***
![Screen Shot 2022-10-26 at 11 43 42 AM](https://user-images.githubusercontent.com/110786136/198096438-13b60992-e169-4c06-88b3-cf5e85856ef1.png)

>### ***2. Users can narrow or customize table search by inputting the type of result they want in the filter search placeholders under date, city, state, country, and shape. Looking the example below we can see that user filtered the table by entering the following criteria ;***
```
- el cajon under City 
- ca under State
- us under Country 
- light under Shape

NOTE: User must press enter after typing the last search criteria
```
>***The result of this search criteria brought back two row that matched the user current search criteria***
![Screen Shot 2022-10-26 at 11 52 51 AM](https://user-images.githubusercontent.com/110786136/198096509-88d4fc66-5925-419e-9c90-9b49c238b25d.png)

## Summary: 

### Drawback

I believe we can all agree that the new webpage filter design have definitely improved the way users can search for UFO events during 2010. However , we can also clonclude that the webpage have some limitation that may need to be address in order to refine the application. 

- UFO date filters don't recognize upper cases 
- User must have to go through the table first to see what information they can use to conduct the search
- An invalid search criteria result in a empty table

### Recommendation

- Create a present drop-down lists including all filter values in place of the input fields.
- Create a default message when search criteria is not found. Example "We're sorry, Search was unable to find any result for"
