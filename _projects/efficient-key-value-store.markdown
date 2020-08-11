---
layout: page
title: Efficient Key Value Store
description: High throughput database built entirely in C, minimizing memory and cpu time
img: /assets/img/blue-2.jpg
importance: 4
---

Project repository: <a href="https://github.com/jaidevshriram/Efficient-Key-Value-Storage-API">https://github.com/jaidevshriram/Efficient-Key-Value-Storage-API</a>

The main goal with this project was building a database system - with insert, delete, search, and update operations - for key, value pairs. The database was judged on peak memory usage and number of operations per second. Hence, we chose to build a compressed trie. The encapsulated methods and data structure have been optimized to handle millions of requests while keeping memory and CPU usage to a minimum.

The trie automatically adapts to the data inserted/deleted to/from the database. The resulting data strucutre saves a considerable amount of space while being parallelizable at the same time. Further, to save time in allocating memory, we make use of free lists to service more requests sooner.

Built in a team of four for the course 'Software Programming for Performance' at IIIT-H.