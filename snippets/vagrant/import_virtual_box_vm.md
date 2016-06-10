#### Import existing virtual box machines to vagrant

- Package a `.box` file using the following command:

        vagrant package --base <vm_name> --output <output.box>

        # vm_name - Name of the existing virtual box vm
        # output.box - Output box file name


- Add newly created box file to vagrant using following command:

        vagrant box add <box_name> <output.box>

        # box_name - Name of vagrant box
        # output.box - Newly created box file
