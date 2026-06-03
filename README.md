# Configurations FederNet 

Ce dépôt contient des fichiers de configuration se basant sur les algorithmes FedAvg et FedAsync, pour le framework FederNet.

Ce dépôt contient des configurations de références ainsi que des configurations aux paramètres adaptés suite à nos observations et données extraites des simulations de référence.

> **Attention** : Afin de pouvoir utiliser ces configurations, il est nécessaire d'installer le framework Federnet (https://github.com/antonio-boiano/FederNet)

---

## 1. Installation du framework FederNet

Les étapes suivantes résument l'installation du framework. Pour plus de détails concernant l'installation, veuillez vous référer au dépôt du framework (https://github.com/antonio-boiano/FederNet)

> [!CAUTION] Pour utiliser ce framework, il est nécessaire de l'installer sur une machine sous Ubuntu. Pour plus de précisions, voir le [dépôt du framework](https://github.com/antonio-boiano/containernet)  
> Prérequis : **Docker**, **Python 3.7+**, **ContainerNet** (pour l'installation de containernet, se référer au dépôt suivant : https://github.com/antonio-boiano/containernet)

Cloner le dépôt de FederNet :
    ```bash
    git clone https://github.com/antonio-boiano/FederNet.git
    cd FederNet
    ```

Installer les dépendances : 
     ```bash
    pip install -r requirements.txt
    ```

## 2. Télécharger les configurations

A la racine du projet, cloner ce dépôt :
    ```bash
    git clone https://github.com/Maxme-L/fl-configurations
    ```

## 3. Utilisation

Pour utiliser le framework : 
```bash
cd FederNet
python3 -m src.main --config "/path/to/configuration.yaml"
```
