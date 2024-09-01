---
layout: posts
title:  "Street Sweeper World Projects"
date:   2024-02-13 19:36:07 +0000
categories: work
tags: AI
description: These are three projects that I completed relating to the Street Sweeper World in my AI course.
header:
  overlay_image: "/assets/images/background1.jpg"
  teaser: "/assets/images/streetsweeper.jpg"
  caption: "Photo credit: [Unsplash](https://unsplash.com)"
---
> Three bots that interact with similated street network enviromnment to clean streets.

# Project 1: Street Sweeper World
I was given a reflex agent using the OSMnx Library to retreieve real map data from OpenStreetMap that can perceive its battery life, meters cleaned, and current location, as well as any useful data about the street, such as its real-life name, length, speed limit, travel time, and cleanliness. I implemented a model-based agent that made rational decisions based on the current percepts and the state that I was keeping track of. I also described why this performed better than the reflex agent.
[Project 1 Colab Link](https://colab.research.google.com/drive/193UnFif2DSnkNG1cDOMplGJQIPzUi73_?usp=sharing)
# Project 2: Breadth-First Search with Repeated State Checking
Now, using the same environment and libraries as before, you can get information about destinations that are not in the bot’s current location, such as incoming/outgoing streets from their current location or just any specified street. I was given a bot that works with a simple search algorithm, but directed to implement A* Search. To do so, I had to decide path costs and a heuristic and a way to deal with these accordingly. I also showed that this was an improvement over my partially observable agent from Project 1.
[Project 2 Colab Link](https://colab.research.google.com/drive/1kG-JS92EBF56bIjT8toniLZuTznN3uMs?usp=sharing)
# Project 3: Iterative Improvement Avoiding Local Optima
I was given a bot that implements an iterative improvement algorithm that attempts to avoid getting stuck in local minima (a hill-climbing algorithm), and asked to improve this basic approach with a different algorithm.
[Project 3 Colab Link](https://colab.research.google.com/drive/1D0nyi_Y8P5Uzqp1GwlHLSyy4GBUltop5?usp=sharing)