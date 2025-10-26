# imperial-ml-capstone

The Black-Box Optimization (BBO) Capstone is a hands-on machine learning challenge where we try to optimize unknown functions by carefully choosing input queries — even though we don’t know how these functions work inside. All we get is the output in response to each input we submit, which makes every decision count.
The main goal is to design a smart strategy that can figure out which inputs are likely to produce the best results. This means constantly balancing between exploring new areas of the input space and refining choices around the ones that have shown promise — all with limited data and feedback.
Working on this project has been an eye-opener. It's pushed me to think critically about how to get the most insight from very limited information, which is a common real-world problem, especially when tuning models or running A/B tests. I’ve gotten the chance to use tools like Gaussian Processes and SVMs, and more importantly, to experiment with how they can work together.
Beyond just the technical work, this project has helped me practice communicating my ideas clearly. I’ve had to explain my decisions, write up my thought process, and reflect on my results — all of which are essential when working with teams or presenting projects to future collaborators or employers.

| Function     | Input Dimensionality | Output Type |
|--------------|----------------------|--------------|
| Function 1   | 2D array             | 1D array     |
| Function 2   | 2D array             | 1D array     |
| Function 3   | 3D array             | 1D array     |
| Function 4   | 4D array             | 1D array     |
| Function 5   | 4D array             | 1D array     |
| Function 6   | 5D array             | 1D array     |
| Function 7   | 6D array             | 1D array     |
| Function 8   | 8D array             | 1D array     |


What makes my strategy different is that I don’t rely on a single method. I use both Bayesian modeling and classification techniques together to improve how I choose queries. Each function is treated uniquely — I don’t assume one solution fits all. I also monitor patterns and confidence levels to reduce the risk of overfitting and wasted efforts.
To me, this project is more than an academic exercise. It mirrors real-world machine learning tasks where you’re working with limited data, noisy signals, and high uncertainty — and where success depends on smart modeling, thoughtful iteration, and clear communication.
