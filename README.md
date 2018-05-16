# FlowManager

The FlowManager is a RYU controller application that gives the user manual control over the flow tables in an OpenFlow network. The user can create, modify, or delete flows directly from the application. The user can also monitor the OpenFlow switches and view statistics. The FlowManager is ideal for learning OpenFlow in a lab environment, or in conjunction with other applications to tweak the behaviour of network flows in a production environment. 

## Getting Started

These instructions will get you a copy of FlowManager on your local machine.

### Dependencies

FlowManager is a [RYU Controller](https://osrg.github.io/ryu/) application, so make sure that the controller is installed properly before you proceed.
Also, if you intend to use FlowManager with [Mininet](http://mininet.org/), you will need to install that too.

### Installation

Install FlowManager using the following steps:

```
$ git clone https://github.com/martimy/flowmanager
```

## Running the app

```
$ ryu-manager ~/monitor/flowmanager.py
```

## Deployment

The following is a typical deplyment scenario for FlowManager:


## Built With

* [jQuery](https://jquery.com/) - A JavaScript library for event handling, animation
* [D3.js](https://d3js.org/) - A JavaScript library for data visulization. 

## Authors

* **Maen Artimy** - [Profile](http://adhocnode.com)

## License

FlowManager is licensed under the Apache 2 License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

*
*