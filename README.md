# Bath 2022 hackathon project
An android app created in Unity that encourages you to walk more. The more steps logged in your phone's pedometer, the more you can expand your animal's home and accumulate currency to buy items. Project completed in 10hrs.

## Inspiration
Staying active is essential to maintaining a fit and healthy lifestyle. With the increasing popularity of wearable devices like smartwatches, many people use their daily step count as a measure of how active they are. Setting a step goal to meet is a great way to stay motivated, however it can sometimes be hard to maintain that motivation. The NHS recommends that the best way to stay active is to form a habit that becomes a part of your routine. We wanted to create an app that helps its users to stay fit and healthy by helping to form these habits, providing motivation to meet step goals. Our biggest inspirations in this were apps like Forest and Sleep Town, which reward users for meeting goals and offers consequences for not meeting them. Other inspirations included apps that gamify exercise, such as Pokemon Go.

## What it does
Habitat uses the phone's step-tracking hardware to keep track of whether the user meets their step goals. It does so by allowing the user to build up an island, adding one tile per day. If the goal is met, the tile is luscious and green, however if the goal is missed the tile will be barren and dry. If goals are met for multiple days in a row, more exciting and extravagant tiles are added, motivating users to meet their goals continuously. Our aim is that this helps users to form a habit that lasts long after they stop using the app. Users can earn currency (apples) by meeting their goals, which they can use to buy cosmetic upgrades for their tiles. Most importantly, the island is inhabited by a very cute little creature. This fox (or squirrel if you purchase him) livs on the users island and loves grassy green tiles!

## How we built it
We developed this app almost entirely in the Unity game engine. We started by brainstorming ideas for how we could motivate users to meet the step goal, settling on a Nintendogs-like pet that the users hopefully become attached to. We split into two sub-teams, one of whom worked on the visual side (making the game look pretty) and the other worked on integrating the phone's hardware to get the step count. We started by making the base game - an island that builds out in a spiral, with two different tile types. Then we added extra features, such as a larger tile variety for streaks, having the pet move around the screen smoothly, a scrolling cloud background, and extra island decoration. Finally, we worked on the UI, adding the text and making the screens for the shop and the menus.

## Challenges we ran into
We really wanted to capture user step data, but we found that our choice of Unity made this very difficult. Lots of other people online seemed to have found the same issue, and we spent a long time before eventually giving up to focus on more achievable aspects of Habitat. Unity also presented issues with version control, as it stores lots of metadata in its project files that lead to annoying merge conflicts. Finally, none of us are Unity experts, so we were constantly looking things up to make them work.

## Accomplishments that we're proud of
We're very proud of the aesthetic of our game and believe it will attract a wide variety of users - from children to older adults. We're also proud of the user interface and general concept that follows the growing trend of gamifying exercise in a simple but effective and persuasive way. We all find certain activities hard and this app will provide a gentle nudge to engage in activities that are beneficial for yourself and society as a whole. 

## What we learned
This was the first phone app any of us had developed and learnt key factors that must be considered compared to other problems such as adjusting the UI for phone input. We learnt a great deal about working in a short span of time - deciding what was most vital and focusing on that. This required making tough decisions in a time crunch, but discovered that this sort of pressure can actually facilitate creativity.

## What's next for Habitat
We think our template could be extended to a wide variety of use cases where incentivising / disincentivising behaviour such as smoking, studying, and healthy eating. We could see this as the start of a wider variety of similar games under the Habitat name with the positive incentive currency being carried over between services. On a smaller scale, we'd love to add more customisation and minigames to build engagement with our app. This could be spending your AP (currency) on activities/items to further build your relationship with the animal of your choice thus giving you further motivation to achieve your goals.
