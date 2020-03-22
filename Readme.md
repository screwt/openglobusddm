This tool generates ddm tile files for https://www.openglobus.org/ .

To build it:

```shell
git clone https://github.com/screwt/openglobusddm.git
mkdir build
cd build
cmake ../openglobusddm
make
```

The tool arguments are self documented.


You will need data source files from:

* http://www.viewfinderpanoramas.org/Coverage%20map%20viewfinderpanoramas_org3.htm

This tool is based on this project from the openglobus team:

* https://github.com/openglobus/tools/tree/master/HeightsAdapter

