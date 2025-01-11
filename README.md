# Lunar Lander with Deep Q-Learning in Pytorch

This repository displays a solution to the lunar lander problem from the gymnasium library. Solved using Deep Q-learning (DQL) in pytorch. Notes on DQL shown [here](notes.md).

### Results 
---

Training was stopped when the average rewards over the latest 100 episodes reached +200, which took 1764 episodes. 

**After 100 episodes:**

<div align="center">
    <video src='https://github.com/user-attachments/assets/9d145591-24a9-4a5a-9903-4472dfd4132b' width="600" controls></video>
</div>


**After training completed:**
<div align="center">
    <video src='https://github.com/user-attachments/assets/61fb8fae-1a10-4667-a786-59ac1ab1f505' width="600" controls></video>
</div>

---

### Resources

* Richard Sutton's [book](http://incompleteideas.net/book/the-book-2nd.html) 
* Andrew Ng's Reinforcement Learning [course](https://www.coursera.org/learn/unsupervised-learning-recommenders-reinforcement-learning?specialization=machine-learning-introduction) in the coursera Machine Learning specialization
