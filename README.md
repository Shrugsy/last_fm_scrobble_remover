# last_fm_scrobble_remover
selenium_IDE tool to batch delete scrobbles on last.fm

requires selenium IDE (firefox extension):
https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/
and flow control extension for selenium found here: 
https://github.com/73rhodes/sideflow/blob/master/sideflow.js

currently brute force loops 6 times and does not handle large numbers that will not load on a single page
(simple workaround is multiple runs of the loop)
likely not to work if there are less tracks then 6 during the run
script can be split (after 'storeTable' sections to work around this and just store the maximum available
apologies for the messy work, not familiar with selenium

