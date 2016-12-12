# social-gossip-application

Social gossip is a gossip based protocol especially designed for disseminating information in an unstructured Peer-to-Peer network. Please visit [Social Gossip](https://github.com/ishantiw/simOSN) to learn about the implementation of Social gossip. 

This repository is an example to use Social Gossip.

## Instructions to run
- create a new java application project in Eclipse or other IDE.
- right click the project and select "build path->configure build path". Add jar files jep-2.24, peersim-1.0.5 and social-gossip.jar(you can find these jars in root of this repository).
- goto "RunConfigurations" option under "Run" of Eclipse
- right click on "Java application" and click "new"
- goto "main" tab, select the project(name of this project). select `peersim.Simulator` for "Main Class" option
- goto "arguments" tab, to run a particular script add `OSNexperiments/<script-name>`. For example, `OSNexperiments/SocialGossip_WattsModel_Dynamic.txt`
- "Run" this configuration
## Results

Initially, you will be having a graph nodes and edges as below from the selected dataset.

![Initial graph](https://cloud.githubusercontent.com/assets/9600691/21100943/ea0a0ff0-c076-11e6-9e18-e4bfa9cbb053.png)

After running few cycles of Social gossip experiment you will see changes in the graph with new connections shown in green colored edges.

![final graph](https://cloud.githubusercontent.com/assets/9600691/21100818/51429152-c076-11e6-98d2-6e8341acd321.png)

