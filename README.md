# OpenShift-Blue-Green-Deployment
Blue-Green Deployment using OpenShift, How to use OpenShift


## OpenShift Set-up:

1. **Create RedHat OpenShift SandBox Free:**

   - Launch RedHat OpenShift SandBox:
    ![Redhat-hybrid cloud console](https://github.com/user-attachments/assets/dcd04c70-dbce-4835-a34f-2e1f8c9e82b5)

   - SandBox Interface:
    ![SandBox](https://github.com/user-attachments/assets/198bfbe5-927d-439b-b4be-c6b3a810b2bc)
 

2. **Download `oc` OpenShift Client Side Command on Local window for CLI:**

   - Click on `?` this option:
    ![OC-CLI-option](https://github.com/user-attachments/assets/c37fef0a-020e-492d-bf7e-31627e05a06c)

   - Download oc for Windows for x86_64: (This Zip file after download extract it & Add Path in 'System Environment Variable)
    ![download-oc-cmd](https://github.com/user-attachments/assets/f5db4f8b-f5b6-4cb3-8911-655ffe28320d)

   - Check `oc` client side command work:

         oc version

     ![oc-version](https://github.com/user-attachments/assets/ccfcd963-1a62-40b4-9f36-ae24ab3861aa)


3. **Login to RedHat OpenShift SandBox From Local Laptop:**

   - On OpenShift SandBox there is option inside this `?` , then option is `Copy login command`
     ![login-cmd-gui](https://github.com/user-attachments/assets/bfbb245d-421f-48f7-8add-22c6609ae4ef)

   - Then Click on `Display Token` then token occures `Log in with this token`

         oc login --token=

4. **Set project:**

   - Check Your Current Project:

         oc project

   - Switch to your project:

         oc project pratik5577-dev

   - Now try to run OpenShift commands:

         oc get pods
 
   
