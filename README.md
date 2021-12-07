# UFO's
## Overview of Project
This project was developed to showcase the functionality of website creation while using JavaScript to enhance features. The background is centered around assisting a data journalist to build a website. Using UFO data as the data journalists hometown of McMinnville Oregon is famous for an annual UFO centered event. The data set data.js in the static folder was provided. 
## Resources
To build this project the following resources were used:
VS Code version 1.62.3, Notepadd ++, v8.1.9, HTML, Chrome Browser verision 96.0.4664.45, JavaScript ES9, D3, and Bootstrap.
## Results
The UFO Sightings web page was created in HTML (index.html) The overall page was using a dark background and a NASA image in the jumbotron. See the example below. 
![image](https://user-images.githubusercontent.com/90878901/144958751-929fcc8c-0d5c-42c0-997b-afc2c0d5af1e.png)

Script provided by the data journalist is used in the paragraphs. Filters were then added to filter through the data and change the table to the sorts that are populated. D3 was used to listen for events to change the table to the populated fields. A search can be performed by following the examples in the filter table. The examples ain the white boxes can be typed over as shown below. 

Here is an example of using the date filter for Jan 13, 2010: 
![image](https://user-images.githubusercontent.com/90878901/144958996-19aff83e-04bf-4057-92ee-ad5fd31dfe1b.png)

There can be muliple filters applied for instance here is a date and city filter applied. The city requested is White Oak and the date is 1/13/2010:
![image](https://user-images.githubusercontent.com/90878901/144959294-aa268c67-1689-468c-a6c7-646bcd6dbcb7.png)

Here is an image with the state selected as Colorado. 
![image](https://user-images.githubusercontent.com/90878901/144959367-233241d3-e81a-40e1-bb8a-7b3ca674e53b.png)

The data has a country selection as well. Here Canada is selected. 
![image](https://user-images.githubusercontent.com/90878901/144959678-442da9f3-f23c-4542-8798-d6ff7a544ae5.png)

The shape filter can be changed. In this example the shape is triangle. 
![image](https://user-images.githubusercontent.com/90878901/144959513-8ae867ee-3791-409a-ab00-5f67d7e39805.png)

Finally here is a sample with all 5 filters used. This is an event in Buffalo, NY US on 1/9/2010 that had lights.
![image](https://user-images.githubusercontent.com/90878901/144960736-905a5fb7-e6f1-4e89-a85f-c44a34f85359.png)

The coding involved the use of forEach code and D3 to make the functionality work like the examples show. 

## Summary
The coding was able to be executed to the requirements of the challenge. Additional improvements could be made. Suggestions that I would include is a reset button to clear the page going to the orginal table rather than clearing out the filters. Making the filters easier to use to allow for different case. Expansion of the data set would be benificial. 
