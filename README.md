# gcp_oci_vm_start
AHI 504 — Cloud Foundations for Health Informatics - Assignment 1

# GCP
1. Go to console.google.com
2. Click on Create new VM
3. Create instance
4. Give this machine a name - remember to not have any white spaces. Only use hyphens and underscore. No special characters
5. For Region, click drop down and choose location that is closest to you (these locations represent data centers that Google owns) - lecture timestamp 1950
6. Select a compute - depends on what you're trying to accomplish for your task. For this example, it will be E2
7. Then, scroll down to Machine type, and for preset, open the dropdown menu and select GCP: e2-micro. This is the smallest machine option
8. On left side, click OS and storage -> click change and change to Ubuntu version (this is the most common linux environment and has a lot of preinstalled software embedded in it) 
    - operating system -> ubuntu
    - everything else the same = leave as default
9. On left panel, click on data protection
    - prof left as it is to keep it cheap
10. On left panel, click on networking
    - prof left as it is to keep it cheap
11. At the bottom, click create. After it is created, click on the VM
12. scroll through the details of VM that you created
13. Back at top, create SSH dropdown and open in browser window. Then allow. Will show linux terminal environment
14. in terminal, type this command:
    sudo apt-get update

   sudo means running command with admin privileges. apt-get means software manager. update means updating all software that comes with this operating machine

15. Back on main screen "VM Instances" click on the three dots on far right side of your new VM
16. Click Delete