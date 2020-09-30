# Become a Docker Power User with Microsoft Visual Studio Code

<img src="./../img/vs-code-docker-training.png" alt="VS Code and Docker training" height="350"> 

Welcome to [theByte](https://www.thebyte.io) training platform. This repo contains all the labs and material for the **Become a Docker Power User with Microsoft Visual Studio Code Training** course. This repo contains [Visual Studio Code](https://code.visualstudio.com) and [VS Code Docker extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) course resources for the [Become a Docker Power User with Microsoft Visual Studio Code Course](https://www.thebyte.io/become-a-docker-power-user-with-microsoft-visual-studio-code). The goal of the course is to demonstrate new workflows, tips, tricks, and improve your Docker workflow.

The course is authored both by the respective companies or organizations, and by members of the community. We welcome contributions and want to grow the repo.

The course will refer to Microsoft Visual Studio Code as VS Code.

# Docker & VS Code Power User Mode

## 1. Bootstrap a New Project

First, we will boostrap our Python Flask project.

1. Checkout this repo locally where you have VS Code installed `git clone https://github.com/thebyteio/vs-code-docker-training.git`
2. Open VS Code
3. Open a New Terminal by going to VS Code Menu `Terminal -> New Terminal` 
4. Navigate to the `04-power-user` folder `cd 04-power-user`
5. Open the Command Palette `Mac ⇧⌘P` `Windows CTRL + SHIFT + P`
6. Type in the Command Palette `Docker Add Docker files to workspace`
   <img src="./../img/04-add-docker-files-to-work-space.png" alt="Add Docker files to workspace" height="350"> 
7. Choose **`Python Flask`** as application type
8. Application entrypoint is **`04-power-user/app.py`**
9. Port **`5000`**
10. Include optional Docker Compose files? **`YES`**

## 2. Start the new Bootsrapped Python Application
Next, we will start our newly created Docker bootstrapped application.

1. Right Click on `docker-compose.yml` and select `compose up`
2. Next, click the Docker Extension icon (The Docker whale in the right toolbar)
3. You should now see our vscode demo application as a running container
4. Right click the `vscodedockertraining` and select `Open in a Browser`
5. Test the different options available with the container
6.  Right click the `vscodedockertraining` and select `View Logs`
7.  Right click the `vscodedockertraining` and select `Inspect`
8.  Try the rest Stop, Start, Restart, attach to the shell

## 3. Build Docker Image

Now, head back to File explorer which is the file icon in the top left

1. Right click on the `Dockerfile`and select `Build Image`
2. Choose the name of the image and tag

## 4. Shutdown our Application

We finished working with our Cat GIF application so now it is time to cleanup.

1. Right click on `docker-compose.yml` and select `Compose Down`


# Continue to the next section, Debug Docker with VS Code

### Click here to continue -> [05 Debug Docker with VS Code](./../05-debug-docker/debug-docker-vscode.md)