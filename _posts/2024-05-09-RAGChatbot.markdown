---
layout: posts
title:  "Retrieval Augmented Generation Chatbot"
date:   2024-05-09 19:36:07 +0000
categories: work
tags: AI Python
description: A project where I improved a chatbot using RAG and semantic search.
header:
  overlay_image: "/assets/images/background4.jpg"
  teaser: "/assets/images/chatbot.jpg"
  caption: "Photo credit: [Unsplash](https://unsplash.com)"
---
> Improvement and customization of RAG/Semantic Search Chatbot

# RAG Chatbot
In my Artificial Intelligence programming course, we worked through creating a chatbot using RAG and semantic search. This chatbot has an input limit of 128, which was not effective. My assignment was to implement a different model, specifically the [Google Flan-t5-base](https://huggingface.co/google/flan-t5-base), that allows for larger input but is still small enough to run on Colab. 

I also built the chatbot into a loop so that it will continually answer follow-up questions asked by the user and experimented with the temperature (how random the output is) to determine the value that I thought was most effective. An example use case that we implemented was scraping the Drake University Computer Science Course Descriptions site to be able to chat with the LLM about which classes would include specific topics.

[RAG Chatbot Colab Link](https://colab.research.google.com/drive/1y2a4Qds1UT-_AYskejOdsUg2u9vdJw4s?usp=sharing)

### Additional work: