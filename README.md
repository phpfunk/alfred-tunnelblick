# Tunnelblick for Alfred
An Alfred Workflow so you can control Tunnelblick from [Alfred App](http://alfredapp.com/). You will need Alfred and the [Powerpack](http://www.alfredapp.com/powerpack/) to use this.

## Installation
To install the Tunnelblick Workflow in Alfred double click on `Tunnelblick.alfredworkflow`.

## How to use
Once installed with Alfred you can run the following command `vpn`. Once you type `vpn` all your tunnelblick configs will appear in the dropdown list in Alfred. Simply click one or press Enter to toggle the connection for that VPN. For added speed, narrow down the list with query: `vpn <name>`

<img src="http://cl.ly/image/010j0P2f382n/tunnelblick-alfred.png" title="Tunnelblick in Alfred" />

## Examples
To list all VPN configurations:

```
vpn
```

To limit to those containing word *office*:

```
vpn office
```

## Download
[Tunnelblick](https://github.com/phpfunk/alfred-tunnelblick/archive/master.zip)

## Version History

### 2.0.1 - January 21, 2013
* Update bundle ID

### 2.0.0 - January 14, 2013

* Updated for Alfred version 2
* Simplified, more unified workings

### 1.0.0 - December 22, 2011

* Initial release
* Ability to toggle connections
* Growl notifications
* Support for invalid configs
