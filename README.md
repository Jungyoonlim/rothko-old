# rothko AI
Artificial Intelligence and Art, Man and Machine, Tragedy and Ecstasy

# What Rothko does: AI Art and Design Studio
- Project #1:  Automate UV unwrapping for 3D modeling (in interior design, games, 3d art, ar/vr, architecture, engineering, product design etc)
#### Moving Project 2 and 3 to different repos
- Project #2: Unsupervised Learning x Art. Algorithms find patterns beyond human labels -- that was not thought possible. Exploring the gaps between language. 
- Project #3 (TBD): AI x Style. What is it to create your 'style'?

## What is UV-ing?
- ML Algorithms can have an advantage by training on a wide variety of complex geometries, e.g. dealing with non-planar or concave polygons, quite common in 3D models. 

## timeline
- early Jul: Ideation, talking to designers 
- Jul 17-21: search+download data!
- Jul 22: unzip, convert, parse
- Jul 23: Try turbosquid to download only the ones with UV maps / alter the src codes for that!
- Jul 24: Trying turbosquid 
- Plans for Jul 25 - Aug 1: Data cleaning, data augmentation, data preprocessing for Project #1, Data preparation (Moma's Collection) for Project #2
- Jul 27: Need to learn more about GANs. Will document on my blog. 
- Jul 29: Trying Reinforcement Learning instead of CNNs for UV unwrapping. Thinking about sorting data into kinds of geometry. 

- [ ] RL Algorithm 
- [ ] Develop a web-based user interface or a plugin for a popular 3D modeling sw to make a way to upload their 3D models and download the generated 2D UV maps. 
- [ ] Incorporate my RL model -- embed in my application and able to accept 3D models as input and output 2D UV maps.
- [ ] Handle File I/O -- Need to be able to read in 3D model files in various formates and export 2D UV maps in a format thta users can use in their texturing workflow (.png, .jpg, etc)
- [ ] A training pipeline -- My RL model can generate UV maps after it's been trained, need to continually train my model on new data so that it can improve over time. 
- [ ] Set up a system for collecting training data, re-training your model, and deploying the new versions of my model. 
- [ ] Maps should be well laid-out for good performance and usability // follow the guidelines and rules of UV mapping
- [ ] Test and Iterate! 

An Ode to Mark Rothko