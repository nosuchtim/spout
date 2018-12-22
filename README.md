spout
=====

A go package for using Spout2.  Assuming that mingw-w64 has been installed, the commands below will get and build everything necessary to run the spouttest program.

```
go get github.com/leadedge/Spout2
# Ignore the message that says: can't load package: ... no Go files...
go get github.com/nosuchtim/spout
cd $(GOPATH)/src/github.com/nosuchtim/spout
makeandinstall.bat
go get github.com/nosuchtim/spouttest
cd $(GOPATH)/src/github.com/nosuchtim/spouttest
go run spouttest.go
```
After running spouttest.go, you should see a window with a spinning cube.  If you run github.com/leadedge/Spout2/DEMO/SpoutReceiver, you should see two textures named "gosquare" and "goscreen".
