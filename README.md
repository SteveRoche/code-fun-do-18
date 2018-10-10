# Coast Prediction and Tracking

Our idea is an implementation of Deep Learning algorithms to assist in prediction of natural disasters and also will help in saving as many lives as possible. As we live in a coastal region, people drowning due to rough waters cause by tsunamis or riptides are common occurrence.  

It will predict whether it’s safe for people who are present in that region during a certain time period, using Deep Learning or alternatively can be triggered by an authority. This will send alerts around to all the other authorities and people on the beach.

If it detects that it’s not safe to swim, it will automatically count the number of people in the water and track them at that point of time using image processing techniques and deep learning algorithms, and will alert the authorities about the same. 

Our project will help in both:
- Predicting whether the water is safe to swim in 
- Alerting the authorities about the number of people who are likely in danger and will track them.

This will give the authorities a rough idea about how much they need to work towards getting people into a safe zone.

It will be implemented by cameras already present at the beach, facing the water.

In case of a false trigger by the algorithm over the safety of the water, authorities can simply tell it that its wrong by marking the water safe. The algorithm will take this into account and try to learn from it’s mistake to make it even more accurate.

**How will it count number of people and track them?**
We can use CNN’s and variants of the YOLO V2 algorithms to assist in this.

**How will we predict the safety of water and tsunami risks?**
This can be done using various methods. One would be taking into factors such as weather, season, area, news, etc. 

Apart from this pictures of the sky and ocean can also tell us a lot about it. Based on the accuracy of both methods, we will choose one (or select both).

Additional features we can ponder over and build on:
1. As we are tracking every person in the water, we can start alerting the lifeguards if someone disappears

2. We can also get the distance of the object being tracked (person). This will make life easier for lifeguards as they know exactly where the missing person disappeared. 

3. Instead of stationary cameras, Drones can help in making this even more effective, and can also provide real time physical tracking to deploy lifejackets if needed.
