Removes the directory `{automationWorkerWindowsBaseDirectory}/build-{newOsNode.fqn}` and ISO file at `{automationWorkerWindowsBaseDirectory}/kickstart_{newOsNode.fqn}.iso`. 

Place `Perform Post Cleanup (Link)` after `Perform Delete ISOs on ESXi Host` so that `Perform Delete ISOs on ESXi Host` can detect dual ISO mode.