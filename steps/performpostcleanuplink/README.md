Removes the directory `{ksVmwareAttuneBaseDir}/build-{kickstartedNode.fqn}` and ISO file at `{ksVmwareAttuneBaseDir}/kickstart_{kickstartedNode.fqn}.iso`. 

Place `Perform Post Cleanup (Link)` after `Perform Delete ISOs on ESXi Host` so that `Perform Delete ISOs on ESXi Host` can detect dual ISO mode.