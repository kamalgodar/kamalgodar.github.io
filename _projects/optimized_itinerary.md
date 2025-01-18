---
title: "Optimized Itinerary Recommendation with AI"
collection: projects
category: personal
permalink: /projects/optimized-itinerary-recommender
excerpt: 'This project aims to recommend destinations and provide optimized itinerary connecting the best destinations based on user’s travel preferences and overall statistics of the destinations, ensuring a tailored travel experience.'
# date: 2019-10-01
venue: 'Journal 1'
start_date: Aug, 2019
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Traveling to new places is a refreshing and fulfilling experience for naturally curious individuals, especially in today's world where leisure often feels like a luxury. However, the uncertainty before embarking on a trip is common, as there are usually countless options to consider. Balancing personal preferences and constraints only adds to the challenge. The Optimized Itinerary Recommender, targeted specifically for tourists visiting new places, is designed to generate the best possible itinerary for travelers, tailored to their preferences and previous ratings. By factoring in constraints such as time, budget, and distance, the problem essentially transforms into an "orienteering problem," a variant of the well-known NP-hard Travelling Salesman Problem (TSP). It aims to plan the most efficient itineraries by linking together the best places to visit that are nearby.

<div style="display: flex; justify-content: center; padding-bottom: 20px;">
    <a href="image/optimized_itinerary/homepage.png" target="_blank">
        <img src="image/optimized_itinerary/homepage.png" alt="Image 1" width="750" style="max-width: 800px; height: auto;">
    </a>
</div>

For the optimized itinerary, Ant Colony Optimization technique is used. ACO is a probabilistic metaheuristic technique for solving difficult combinatorial optimization problems. It is an algorithm which is used to find the optimal path in a graph. It is inspired by the behavior of ants in finding paths from the colony to food. It falls under Swarm Intelligence, which is a branch inside the large domain of Artificial Intelligence (AI). In the ACO algorithm, a set of software agents called artificial ants are created and used to solve the given optimization problem. The optimization problem is transformed into the problem of finding the best path on a weighted graph.

<div style="display: flex; justify-content: center; padding-bottom: 20px;">
    <a href="image/optimized_itinerary/ACO.png" target="_blank">
        <img src="image/optimized_itinerary/ACO.png" alt="Image 1" width="750" style="max-width: 800px; height: auto;">
    </a>
</div>


Datasets were scraped from Tripadvisor using Python libraries like: beautiful soup, selenium, and requests, and users rated different destinations.

<div style="display: flex; justify-content: space-between; align-items: center; padding-top: 5px; padding-bottom: 20px;">
    <div style="flex: 1; text-align: center; margin-right: 10px;">
        <a href="image/optimized_itinerary/data3.png" target="_blank">
            <img src="image/optimized_itinerary/data3.png" alt="Image 1" width="370" style="max-width: 600px; height: auto;">
        </a>
    </div>
    <div style="flex: 1; text-align: center; margin-left: 10px;">
        <a href="image/optimized_itinerary/data1.png" target="_blank">
            <img src="image/optimized_itinerary/data1.png" alt="Image 2" width="370" style="max-width: 600px; height: 300;">
        </a>
    </div>
</div>

<div style="display: flex; justify-content: center; padding-bottom: 20px;">
    <a href="image/optimized_itinerary/data2.png" target="_blank">
        <img src="image/optimized_itinerary/data2.png" alt="Image 1" width="760" style="max-width: 800px; height: 400;">
    </a>
</div>

Content-based recommendation, collaborative filtering using KNN, and hybrid recommendation methods were implemented to provide users with personalized suggestions for similar top destinations.

<div style="display: flex; justify-content: center; padding-bottom: 20px;">
    <a href="image/optimized_itinerary/recommendation.png" target="_blank">
        <img src="image/optimized_itinerary/recommendation.png" alt="Image 1" width="750" style="max-width: 800px; height: 400;">
    </a>
</div>

<div style="display: flex; justify-content: center; padding-bottom: 20px;">
    <a href="image/optimized_itinerary/recommendation1.png" target="_blank">
        <img src="image/optimized_itinerary/recommendation1.png" alt="Image 1" width="750" style="max-width: 800px; height: 400;">
    </a>
</div>

Once a list of places similar to the searched location is generated, the Ant Colony Optimization technique is used for optimized itinerary recommendations. This method was chosen as it outperforms other route optimization algorithms, such as dynamic programming and greedy search.

<div style="display: flex; justify-content: space-between; align-items: center; padding-top: 5px; padding-bottom: 20px;">
    <div style="flex: 1; text-align: center; margin-right: 10px;">
        <a href="image/optimized_itinerary/map1.png" target="_blank">
            <img src="image/optimized_itinerary/map1.png" alt="Image 1" width="370" style="max-width: 600px; height: auto;">
        </a>
    </div>
    <div style="flex: 1; text-align: center; margin-left: 10px;">
        <a href="image/optimized_itinerary/map2.png" target="_blank">
            <img src="image/optimized_itinerary/map2.png" alt="Image 2" width="370" style="max-width: 600px; height: 300;">
        </a>
    </div>
</div>

Chatbot is also integrated in the website to assist users with simple queries related to the places they are visiting. 
<div style="display: flex; justify-content: center; padding-bottom: 20px;">
    <a href="image/optimized_itinerary/chatbot.png" target="_blank">
        <img src="image/optimized_itinerary/chatbot.png" alt="Image 1" width="500" style="max-width: 800px; height: 400;">
    </a>
</div>