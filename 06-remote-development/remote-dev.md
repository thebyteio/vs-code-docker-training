# Become a Docker Power User with Microsoft Visual Studio Code

<img src="./../img/vs-code-docker-training.png" alt="VS Code and Docker training" height="350"> 

# Remote Development in Container

The Remote-Container extension allows you to connect or launch a container and connect VS Code to the container. This is different than connecting to a Container shell as you have the full development environment inside the container. Additionally, you can control quickly the mounting of files or folders from your host into the container speeding up development time.

## 1. Install Remote-Container Extension

In the lab we will launch our Python Flask demo application in Debug mode.

1. Open the VS Code Marketplace
2. Type `remote-container` in the Marketplace search
3. Click `install` on the Official Docker extension

## 2. Launch Remote-Container Development container

OK, we will launch a sample Development container to see the possibilities with the Remote-Container extension.

1. Open the Command Palette `Mac ⇧⌘P` `Windows CTRL + SHIFT + P`
2. Type `Remote-Container: Try Sample`
3. Select `Python` Sample Application
4. VS Code will refresh and you will be attached to the Python sample. Now you can run debug, everything directly inside the container.
5. Open the Command Palette `Mac ⇧⌘P` `Windows CTRL + SHIFT + P` 
6. Type `Remote-Container: Open Folder in Container`
7. You can then choose a folder to mount in the container which will again re-launch VS Code with the mounted folder.

# Continue to the next section, Course Wrapup

### Click here to continue -> [07 Course Wrapup](./../07-course-wrapup/wrapup.md)