Fission Video Demonstration:

https://github.com/KirillSpitsyn/BCDV4032LabsKirillSpitsyn/assets/72778161/4faa1d54-1431-4d55-a098-9d46f5ce88d0

To use Fission, we need Kubectl and Helm, as you can see, I make sure that Helm is installed here. Firstly, I create a new environment called nodejstest using fission, and I create fission deployment in my local cluster using node-env image. 
Pool size 3 means that 3 running pods can accept requests to your fission functions. Then, I download the code for a function that prints a “Hello World” message to the console. After that, I created a fission function using code hello.js
I downloaded 1 step above and node js environment. The function is created successfully. Then I used the fission test command to call the function, and it successfully returned a Hello World message to the console. 
