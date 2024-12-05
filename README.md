# CHAPTER_7
Flutter (Mobile app development)

ADDING ANIMATION TO AN APP

This chapter was all about making my app come to life with animations. I learned how even small, simple animations can completely change the user experience and make an app feel smoother and more interactive.

I started with the AnimatedContainer, which let me animate the width of a container. Adding a spring effect using Curves.elasticOut made the movement look so natural and satisfying. Then, I played around with the AnimatedCrossFade widget, which allowed me to create a cool transition effect between two widgets. I even animated the color to shift from amber to green while also adjusting the width and height—such a neat way to make the interface more dynamic.

Next, I explored the AnimatedOpacity widget, which is perfect for fading widgets in and out over a set period. It’s simple yet so effective for adding subtle transitions that don’t feel abrupt.

But the real magic started with the AnimationController class. It’s the foundation for creating custom animations. I learned how to work with multiple AnimationControllers at the same time, each with different durations, and paired them with the Tween class to define the start and end values of animations.


One of the coolest things I tried was animating a balloon! I controlled its movement—floating upward or downward—while also inflating and deflating it. By combining CurvedAnimation for nonlinear effects like Curves.fastOutSlowIn and Curves.elasticInOut, the results were super smooth and realistic.

Lastly, I experimented with staggered 
animations, where multiple animations are triggered sequentially using a single AnimationController. It’s such a powerful way to create polished, layered effects that add depth to the app.


This chapter really opened my eyes to how much animations can enhance an app’s overall experience. I feel more confident now about making my apps not just functional but visually engaging too.
In the next chapter, I’ll dive into navigation. I’m excited to explore how to use tools like Navigator, Hero Animation, BottomNavigationBar, TabBar, and even Drawer to guide users through my app seamlessly.
