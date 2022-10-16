opying Comp's answer here for better visibility:

1) Connect to the VPN

2) Run pace-jupyter-notebook -q coc-ice-gpu -l nodes=1:ppn=12:gpus=1 --anaconda=anaconda3/2020.11 --conda-env=ece6254

This fixes the port forwarding issue for most people (including me)