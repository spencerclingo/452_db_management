# Final Report

---

## Project Summary

My project was taking an existing 2D graph and projecting it into a 3D space onto a globe using Cesium. Then, users can move their nodes around in a geo-spacial context, allowing us to calculate a probability of connection over a WiFi network given the distance between a node and a router. Those locations are stored in a database, which is used for the calculations and for placing the nodes back on the map if the user leaves and comes back to the feature.

## Knowledge Gained

I learned a lot abuot the capabilities (and limitation) of the CesiumJS library. One such limitation is that draw order is not customizable, so billboards (images) will almost always appear above labels and polylines. There are tricks to bypass the draw order, but they are hacky and inconsistent. Another thing I learned is how much power CesiumJS gives to the developer in interacting with the map. You can keep it simple with the default actions on clicks and drags, or you can override and introduce new capabilities, including hover events, drag/drop, and pretty much anything else a user might want to do on a 3D map.

## How did I use AI?

CesiumJS is on version 1.135.0 at the moment. It has been in open source development for over 10 years. This means it has tons and tons of documentation. While the documnetation is helpful when trying to learn the capabilities and parameters specific objects have, finding new objects that match my use cases is much harder manually. AI helped a ton in learning the CesiumJS library and getting familiar enough with it where I can feel comfortable writing whatever I need to write.

## Why is this project interesting to me?

I have loved working with CesiumJS. I built a related project with CesiumJS before this one that integrated multiple systems and outsourced the we needed for that project calculations. This time, I was able to build the necessary calculations myself, on top of learning far more about Cesium and how it works with images instead of only entities. I've also been able to learn more about the error systems it has, which helps me to mitigate the issues we face.

## Key learnings

I learned how to...

1. How to create event handlers to customize how a user interacts with a map.
1. How to sort, load, zoom to, and hide hundreds of entities in Cesium at once.
1. How to better read data out of Cesium for use in calculations.
1. How to attach different entities together to appear as one singular entity.
1. How to write a MySQL flyway migration with foreign keys and how to create a domain object in Spring JPA to force a directional parent-child relationship in the database.
1. How to use the primitives API for labels, billboards, and polylines (even if we decided against it for maintainability)

---

https://teams.microsoft.com/l/message/19:ac4bc382e82e4ef6a3b61989d55cf4b8@thread.tacv2/1762201027122?tenantId=c6fc6e9b-51fb-48a8-b779-9ee564b40413&groupId=89222c8a-2991-4873-8d7d-10b1cacaebf4&parentMessageId=1762201027122&teamName=CS%20452%20001%20(Fall%202025)&channelName=Report%20-%20Project%20Pitch&createdTime=1762201027122

No, please don't share this with future classes.
