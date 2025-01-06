# Lunar Lander with Deep Q-Learning in Pytorch

This repository displays a solution to the lunar lander problem from the gymnasium library. Solved using Deep Q-learning (DQL) in pytorch. Notes on DQL shown [here](notes.md).

### Results 
---

I stopped training when the average rewards over the latest 100 episodes reached +200, which took 1764 episodes. 

**After 100 episodes:**

<div align="center">
    <video src='./assets/lunar_lander_100.mp4' controls></video>
</div>


**After training completed:**
<div align="center">
    <video src='./assets/lunar_lander.mp4' controls></video>
</div>

---

### References

* Richard Sutton's [book](http://incompleteideas.net/book/the-book-2nd.html) 
* Andrew Ng's Reinforcement Learning [course](https://www.coursera.org/learn/unsupervised-learning-recommenders-reinforcement-learning?specialization=machine-learning-introduction) in the coursera Machine Learning specialization