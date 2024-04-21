






![3](https://github.com/RitikDiyundi/Library-Fullstack/assets/154815699/9d2cbd3b-a229-43ce-ab8b-320b1e3dd3c1)

![image](https://github.com/RitikDiyundi/Library-Fullstack/assets/154815699/ff5ffc3e-44cd-4c5e-8c40-4adb9d974613)

![image](https://github.com/RitikDiyundi/Library-Fullstack/assets/154815699/31d2ebbd-4a29-48a8-84fb-0342adef00f8)



![image](https://github.com/RitikDiyundi/Library-Fullstack/assets/154815699/f2fbf8f7-60d7-48f0-a47f-10729cfde327)

![image](https://github.com/RitikDiyundi/Library-Fullstack/assets/154815699/5bc18516-dfc9-4f5a-a741-1a8b16822193)

![image](https://github.com/RitikDiyundi/Library-Fullstack/assets/154815699/31c38ef2-92ec-4469-ae0c-811958594199)

![image](https://github.com/RitikDiyundi/Library-Fullstack/assets/154815699/29187c36-1212-45cf-a877-90aa8cfb9d10)



# MS Windows - Install Development Tools

In this guide, we will install the following development tools

* Visual Studio Code
* node
* npm
* tsc

## Versions

This course has been tested with the following software versions:

* npm 8.15
* node 16.17.0
* tsc 4.7.4
* React 18.2.0
* Spring Boot 2.7.3 

It is **highly recommended** that you use the versions listed above to make sure you do not encounter any issues with the course. If you choose to use other versions then the code may not work as expected.

## Install Visual Studio Code
Visual Studio Code is a general purpose IDE that support many programming languages. Visual Studio Code has built-in support for TypeScript.

1. In a web browser, visit https://code.visualstudio.com/
2. Follow the link to download Visual Studio Code for MS Windows

3. Run the Installer

4. Follow the steps in the Installer


## Install Node
Node is the the runtime environment for executing JavaScript code from the command-line. By using Node, you can create any type of application using JavaScript including server-side / backend applications.

1. In your web browser, visit https://nodejs.org/download/release/v16.17.0/

2. Select the **Windows Installer (.msi)** for your system (32-bit or 64-bit)

3. Run the Installer

4. Follow the steps in the Installer

5. Open a **Command Prompt** window to verify the node installation

6. In the **Command Prompt** window, type the following command: 

    ```bash
    node --version
    ```

   If the installation is successful, you will see the version number

   > Note: The Node installation also includes npm (Node Package Manager).

3. Verify npm is installed

    ```bash
    npm --version
    ```

   If the installation is successful, you will see the version number. 

   > Note: node will have a different number than npm. This is similar to a different Java JDK version number compared to Maven version number.
   >
   > In this example, node is similar to the Java JDK.  And npm is similar to Maven.

## Install tsc
tsc is the TypeScript compiler. We use tsc to compile TypeScript code into JavaScript code. We can install the TypeScript compile using the Node Package Manager (npm)

> Note: This course has been tested with TypeScript 4.7. We will install this version.

1. In your **Command Prompt** window, enter the following command

    ```
    npm install --location=global typescript@4.7.4
    ```

   The "--location=global" installs this as a global package. The TypeScript compiler will be available to all directories for this user.

2. You can verify the installation

    ```bash
    tsc --version
    ```

   If the installation is successful, you will see the version number.

That's it! You have successfully installed the development tools: Visual Studio Code, node, npm and tsc.

