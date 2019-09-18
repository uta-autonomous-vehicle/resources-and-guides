# resources-and-guides
initial dump of everything relevant


Host:
- [Guide](http://www.bojankomazec.com/2017/11/how-to-install-jetpack-31-on-nvidia.html)
- [JetPack 3.1 installer .deb](https://mega.nz/#!GgpRwaRL!nsC9KS_tyBezuZik92lE2RRH00tDk3Xq2duCn1DhVcI)




**Notes:**
- Components:
	- https://www.robotshop.com/en/hokuyo-ust-10lx-scanning-laser-rangefinder.html

- Getting the motor to work
	- info on the setup from jetson hacks:  [follow here](https://www.jetsonhacks.com/2017/06/01/get-your-motor-running-vesc-jetson-racecar-build/)
	- [video on trial](https://www.youtube.com/watch?v=sjRsfWtWwf8)

- LIDAR
	- ROS support:
		- http://wiki.ros.org/rviz/DisplayTypes/LaserScan
	- config:
		- https://www.robotshop.com/en/hokuyo-ust-10lx-scanning-laser-rangefinder.html
		- what we have: https://www.hokuyo-aut.jp/search/single.php?serial=167
		- what we might want: https://www.hokuyo-aut.jp/search/single.php?serial=224
	- examples:
		- https://augustt198.github.io/bwsi-report/
	- Limitations:
		- only finds range
		- does not detect and draw objects
