# Dell EMC VxFlex OS Helm Chart for Kubernetes

For detailed installation instructions, look in the Product guide in the csi-vxflexos repository please.

The general outline is:

    1. Satisfy the pre-requsites outlined in the Release and Product guide in the csi-vxflexos repository.

    2. Create a Kubernetes secret with the VXFlex OS credentials using the template in secret.yaml.

    3. Copy the `csi-vxflexos/values.yaml` to a file  `myvalues.yaml` in this directory and fill in various installation parameters.

    4. Invoke the `install.vxflexos` shell script which deploys the helm chart in csi-vxflexos.
    
