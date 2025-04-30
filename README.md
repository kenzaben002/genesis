
## Citation

If you use Genesis in your research, please consider citing:

```bibtex
@software{Genesis,
  author = {Genesis Authors},
  title = {Genesis: A Universal and Generative Physics Engine for Robotics and Beyond},
  month = {December},
  year = {2024},
  url = {https://github.com/Genesis-Embodied-AI/Genesis}
}

# genesis
Exploring and testing GENSIS IA to gain a deeper understanding of its capabilities in robotics simulation and reinforcement learning
-----
J'ai testé l'installation sur Linux et Windows.
- Linux fonctionne bien
- Windows fonctionne mais pose problème de visualisation (OpenGL), donc Linux est fortement recommandé
Pré-requis :
- Installer torch
    # Assurez-vous d'installer la version de Python et de torch adaptée à votre système
    pip install torch
- Installer Genesis
    pip install genesis-world
##Pour une meilleure compréhension, veuillez vous référer à la documentation officielle :
https://genesis-world.readthedocs.io/en/latest/user_guide

Genesis est plus efficace avec une carte GPU.
- Vérifiez vos drivers NVIDIA avec la commande :
    nvidia-smi
- Si le driver n’est pas trouvé, installez-le :
    sudo apt install nvidia-driver --version
- Verifier vos cuda version
  
Vérifiez aussi l’architecture de votre GPU :
- Elle doit avoir un Compute Capability  (C.C) supérieur ou égal à 3.7
- Certaines architectures ne sont plus supportées par PyTorch
  Exemple : la NVIDIA GeForce GTX 780 a un C.C de 3.5 et n’est donc **non compatible**

