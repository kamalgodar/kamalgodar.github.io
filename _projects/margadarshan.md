---
title: "Margadarshan: A Smart Traffic Management System"
collection: projects
category: personal
permalink: /projects/margadarshan
excerpt: 'This project aims to manage traffic by alerting users about different unforeseen conditions such as heavy traffic, constructions, accidents and diverging them to less crowded routes to optimize their travel time.'
# date: 2019-10-01
venue: 'Journal 1'
start_date: Aug, 2019
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Not many existing systems have been effective in providing traffic data to users, although some have been implemented in countries like Germany, and the US. While Google Traffic provides some traffic data, traffic congestion problems, particularly in Nepal, remain unaddressed. Margadarshan aims to manage traffic by alerting users about different unforeseen conditions such as heavy traffic, constructions, accidents and diverging them to less crowded routes to optimize their travel time. The system also seeks to provide real-time updates on passenger density and the number of available seats inside public vehicles while also tracking their locations. Additionally, it offers users route-specific information, such as fog conditions, temperature, rainfall, dust, and pollution levels. 

Margdarshan is a web based application that collects real-time information of the traffic density through image processing and forwards it to its users. It calculates the time to reach the destination considering the traffic congestion and helps users pick the route that is optimal to reach the location. It also offers information about the temperature, humidity, and weather conditions of the user’s current location. A traffic capacity counting was implemented to count the number of vehicles in a certain region. 

<!-- <div style="display: flex; justify-content: center; padding-bottom: 20px;">
    <a href="image/margadarshan/margadarshan.png" target="_blank">
        <img src="image/margadarshan/margadarshan.png" alt="Margadarshan" width="1000" height="700">
    </a>
</div> -->

<div style="display: flex; justify-content: space-between; align-items: center; padding-top: 5px; padding-bottom: 20px;">
    <div style="flex: 1; text-align: center; margin-right: 10px;">
        <a href="image/margadarshan/margadarshan.png" target="_blank">
            <img src="image/margadarshan/margadarshan.png" alt="Image 1" width="600" style="max-width: 700px; height: auto;">
        </a>
    </div>
    <div style="flex: 1; text-align: center; margin-left: 10px;">
        <a href="image/margadarshan/traffic_capacity.png" target="_blank">
            <img src="image/margadarshan/traffic_capacity.png" alt="Image 2" width="150" style="max-width: 600px; height: 500;">
        </a>
    </div>
</div>

This system further tracks public transport using GPS and also lets the user know about the passenger count in a particular vehicle. The GPS sensor is interfaced in an 8051 microcontroller (AT89C51) to track the location of the vehicle. The data is obtained in the form of latitude and longitude and uploaded to the web and the location is shown in the map. Passenger count system is implemented by using a switch (or an IR sensor) at the entry and exit points of the public. At entry, when an incoming person presses the switch, the passenger count increases and at exit, when an outgoing person presses the exit switch, the passenger count decreases.

<div style="display: flex; justify-content: space-between; align-items: center; padding-top: 5px; padding-bottom: 20px;">
    <div style="flex: 1; text-align: center; margin-right: 10px;">
        <a href="image/margadarshan/vehicle_tracking.png" target="_blank">
            <img src="image/margadarshan/vehicle_tracking.png" alt="Image 1" width="250" style="max-width: 450px; height: auto;">
        </a>
    </div>
    <div style="flex: 1; text-align: center; margin-left: 10px;">
        <a href="image/margadarshan/passenger_counting.png" target="_blank">
            <img src="image/margadarshan/passenger_counting.png" alt="Image 2" width="500" style="max-width: 600px; height: 500;">
        </a>
    </div>
    
</div>


Furthermore, the system alerts users to potential obstructions caused by construction work, accidents, or riots, helping them avoid time delays and potential dangers. The application has the feature where people can post an update regarding the conditions of their surroundings and share the information to everyone. The validity of the post can be tested by implementing the voting and credit point system.

<div style="display: flex; justify-content: space-between; align-items: center; padding-top: 5px; padding-bottom: 20px;">
    <div style="flex: 1; text-align: center; margin-right: 10px;">
        <a href="image/margadarshan/post_update.png" target="_blank">
            <img src="image/margadarshan/post_update.png" alt="Image 1" width="350" height="300">
        </a>
    </div>
    <div style="flex: 1; text-align: center; margin-left: 10px;">
        <a href="image/margadarshan/post_on_map.png" target="_blank">
            <img src="image/margadarshan/post_on_map.png" alt="Image 2" width="300" height="300">
        </a>
    </div>
    
</div>


<!-- ![1737145063071](image/margadarshan/1737145063071.jpg "Traffic Congestion") -->

<!-- <div style="display: flex; justify-content: center;">
    <img src="image/margadarshan/traffic_jam.jpeg" alt="" width="600" height="400">
</div> -->