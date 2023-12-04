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