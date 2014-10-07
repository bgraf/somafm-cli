somafm-cli
==========

SomaFM command line.   
Small ruby wrapper around `mpv` to play [SomaFM](http://somafm.com) radio stations.   
Saves channel list in `~/.somachans`.
Saves bash completion file in `~./somacomplete`.
`$ source ~/.somacomplete` for channel completion.

### Usage

`somafm update` update channel list.   
`somafm list` print list of channels.  
`somafm <channel>`  play channel using `mpv` player.
