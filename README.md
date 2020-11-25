# GeometricBrownianMotionSimulations
The use of Geometric Brownian Motion in modeling stock movements (stochastic methods).

## A bit of background:

Brownian motion describes the random motion of particles. This motion is named after the botanist Robert Brown, who first described the phenomenon in 1827, while looking through a microscope at pollen of the plant in water.

In mathematical finance, Brownian motion is described by the Wiener process, a continuous-time stochastic process. The Wiener process can be constructed as the scaling limit of a random walk. In mathematics, a random walk is an object, known as a stochastic or random process, that describes a path that consists of a succession of random steps on some mathematical space such as the integers. A random variable that can jump up or down every second is an example of a random walk. If you plot it on the graph and them decrease the time interval ie it will jump every millisecond, you will approxiate a Brownian motion in continuous time.

Like the random walk, the Wiener process is recurrent in one or two dimensions (meaning that it returns almost surely to any fixed neighborhood infinitely often). Unlike the random walk, it is scale invariant which means that if you scale a Wiener Process it remains a Wiener Process.

## Applications in Finance:

If there is a “secret formula” in the Monte Carlo simulation technique, it is the development of simulated stock prices. How is it done? The “Monte Carlo” aspect of this overall process simply refers to what is, in essence, “rolling of the dice” thousands of times. Monte Carlo techniques can be applied to myriad scenarios involving forecasting or predictive modeling. For awards with market conditions, simulated future stock prices are defined using a specific formula, described below, with one of the inputs varying based on each “roll of the dice,” i.e., the Monte Carlo simulation technique.

The formula used to estimate future stock prices was developed based on an observed process called Brownian Motion. This process is named after Robert Brown, a 19th century botanist who observed the seemingly random movements of pollen particles in a fluid under a microscope. Over the following decades and into the 20th century, mathematicians and scientists developed ways of formulaically describing random movements of particles, atoms, and eventually in financial theory to describe the movements of stock prices. Today, the generally accepted method for simulating stock price paths is using a formula often referred to as Geometric Brownian Motion with a Drift. The “Geometric Brownian Motion” portion of this formula refers to the random movements of the observed stock prices (pollen particles). The “drift” refers to constant forward motion, i.e., the passage of time. It can be thought of as a “breeze,” as though pollen particles are moving through the air over time assuming a constant wind speed. In other words, there are random movements mixing with a constant force. Some particles fly high into the sky (e.g., high TSR), some fall to the ground (e.g., low TSR), and some end up somewhere in between. We will refer to Geometric Brownian Motion with a Drift as GBM going forward.

## Can be applied as a "Framework" in a Monte Carlo simulation for stocks: https://www.investopedia.com/articles/07/montecarlo.asp
