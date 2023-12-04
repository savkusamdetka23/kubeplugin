#Plugin installation
## Create plugin script
You can use "kubeplugin.sh" file from the scripts folder in current repository.
    # Check kist of available kubectl plugins
    kubectl plugin list

    # Copy your plugin script to the folder with kubectl plugins 
    sudo chmod +x ./kubeplugin.sh
    sudo cp kubeplugin.sh /usr/local/bin/kubectl-kubeplugin
    sudo chmod +x usr/local/bin/kubectl-kubeplugin

    # Check kist of available kubectl plugins
    kubectl plugin list

    # Use plugin
    kubectl kubeplugin

## Examples of using script locally
    bash kubeplugin.sh kube-system node
    bash kubeplugin.sh kube-system pod
    bash kubeplugin.sh demo node
    bash kubeplugin.sh demo pod
    bash kubeplugin.sh argocd node
    bash kubeplugin.sh argocd pod


## Examples of using as kubectl plugin
    kubectl kubeplugin kube-system node
    kubectl kubeplugin kube-system pod
    kubectl kubeplugin demo node
    kubectl kubeplugin demo pod
    kubectl kubeplugin argocd node
    kubectl kubeplugin argocd pod