somafm-cli
==========

SomaFM command line.   
Small ruby wrapper around some command line music player to play [SomaFM](http://somafm.com) radio stations.   

Saves channel list in `~/.somachans`.   
Saves bash completion file in `~./somacomplete`.   
Use `$ source ~/.somacomplete` for channel completion.   
Saves configuration in `~/.somaconf` using `mpv` as default player.   

### Usage

`somafm update` update channel list.   
`somafm list` print list of channels.  
`somafm <channel>`  play channel.
