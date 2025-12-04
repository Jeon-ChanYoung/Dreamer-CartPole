# Dreamer-CartPole  

This project involved receiving the CartPole-v1 environment as an image and implementing Dreamer components minimally to conduct reinforcement learning.  


# Requirements  
pip install -r requirements.txt  
 - gymnasium[classic-control]==1.2.2  
 - opencv-python-headless==4.12.0.88  
 - numpy==2.0.2  
 - torch==2.4.1+cu121  

# How to Run  
Simply run it from dreamer_cartpole.ipynb. If you have a trained model, please adjust the file path accordingly.  

# Simulation  
This is the result of running simulations based on the trained model. It includes the latent rollout simulation process in addition to interactions with the actual environment.  

<img src="gif/simulation.gif" width="400" alt="Simulation GIF"/>
<img src="gif/latent_simulation.gif" width="400" alt="Latent Simulation GIF"/>
