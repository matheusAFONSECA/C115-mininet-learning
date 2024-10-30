# C115-mininet-learning

## Overview

This repository is dedicated to documenting the initial learning stages of Mininet for the course *Connected Devices - C115* at *Instituto Nacional de Telecomunicações* (INATEL). Here, a proposal is presented for developing and learning in Mininet.

## Index

- [Proposal](#proposal)

- [Execution Steps](#execution-steps)
    - [1. Creating topology](#1-creating-topology)
    - [2. Checking informations of topology](#2-checking-informations-of-topology)
        - [Hosts configurantions](#hosts-configurantions)
        - [Dump of topology](#dump-of-topology)
        - [Net of topology](#net-of-topology)
        - [Nodes of topology](#nodes-of-topology)
    - [3. Pings among different nodes](#3-pings-among-different-nodes)
    - [4. Specifying host 1 as server and host 2 as client](#4-specifying-host-1-as-server-and-host-2-as-client)
        - [Configuration of putty](#configuration-of-putty)
        - [Login in mininet using puTTy](#login-in-mininet-using-putty)
        - [Using Xterm to make h1 as a server and h2 as a client](#using-xterm-to-make-h1-as-a-server-and-h2-as-a-client)

- [Author](#author)

## Proposal

The proposal for this project is as follows:

```text
Consider a tree topology with depth=4 and fanout=2.
    - Using the standard Mininet command line, create the topology with standardized MAC addresses, a bandwidth (bw) of 25 Mbps, and the default Mininet controller (no need to specify);
    - Inspect interface information, MAC addresses, IP addresses, and ports using command-line inspection;
    - Run ping tests between different nodes;
    - Specify that host 1 on port 5555 will be a TCP server and host 2 will be a client, then execute iperf tests, reporting every second for a 10-second test. Conduct the tests with a bandwidth (bw) of 25 Mbps.
```

## Execution Steps

### 1. Creating topology

![Creation of topology](images/project/creating_topology.png)

---

### 2. Checking informations of topology

#### Hosts configurantions

![Configuration of H1 and H2](images/project/config/config_h1_h2.png)
![Configuration of H3 and H4](images/project/config/config_h3_h4.png)
![Configuration of H5 and H6](images/project/config/config_h5_h6.png)
![Configuration of H7 and H8](images/project/config/config_h7_h8.png)
![Configuration of H9 and H10](images/project/config/config_h9_h10.png)
![Configuration of H11 and H12](images/project/config/config_h11_h12.png)
![Configuration of H13 and H14](images/project/config/config_h13_h14.png)
![Configuration of H15 and H16](images/project/config/config_h15_h16.png)

---

#### Dump of topology

![Dump of topology](images/project/info/dump.png)

---

#### Net of topology

![Net of topology](images/project/info/net.png)

---

#### Nodes of topology

![Nodes of topology](images/project/info/nodes.png)

---

### 3. Pings among different nodes

![Ping among nodes](images/project/ping_all.png)

---

### 4. Specifying host 1 as server and host 2 as client


#### Configuration of putty

![Configuration of VM mininet](images/project/ifconfig.png)

![Defining IP of VM mininet in puTTy](images/project/putty/config1.png)

![Enabling Xming of VM mininet in puTTy](images/project/putty/config2.png)

---

#### Login in mininet using puTTy

![Login in mininet using puTTy](images/project/putty/login.png)

---

#### Using Xterm to make h1 as a server and h2 as a client

![h1 as a server and h2 as client using xterm](images/project/putty/topology_xterm.png)


## Author

### [Matheus Fonseca](https://github.com/matheusAFONSECA)

Undergraduate student in the eighth (8th) semester of Computer Engineering at the National Institute of Telecommunications (Inatel). I participated in a Scientific Initiation at the Cybersecurity and Internet of Things Laboratory (CS&ILAB), where, in the Park Here project, I developed skills in computer vision applied to parking systems, focusing on license plate recognition and vehicle identification. Additionally, I served as a teaching assistant for Physics 1, 2, and 3, helping with practical classes, report writing, and answering theoretical questions. Currently, I am an intern at the Inatel Competence Center (ICC) in the PDI SW department.