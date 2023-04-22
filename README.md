# Commandes utiles pour Micro8ks

Mettre a jour node Microk8s <br /> 
kubectl drain $NOMDUNODE --ignore-daemonsets <br /> 
sur le node <br /> 
sudo snap refresh microk8s --channel 1.26/candidate <br /> 
Apres MAJ: <br /> 
kubectl uncordon $NOMDUNODE <br /> 


