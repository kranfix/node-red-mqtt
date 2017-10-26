Node-Red MQTT Nodes
===================

This repository is a copy of the default Node-Red MQTT nodes.

The intention of this repository is to be an educational example
of how to generate customizable nodes with multiple file a many
options.

# Testing Process

## Clone the repository

Via SSH:

```
git clone git@github.com:kranfix/node-red-mqtt.git
```
Via HTTPS:

```
git clone https://github.com/kranfix/node-red-mqtt.git
```

## Node-Red link

```
npm link
```

Then, go to `~/.node-red`:


```
cd ~/.node-red
```
And run:

```
npm link node-red-mqtt
```

And run a new flow in node-red:

```
node-red myflow.json
```
