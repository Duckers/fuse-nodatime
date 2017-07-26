
# Uno.Time based on nodaTime

This repo holds a Uno port of an older version of http://nodatime.org/

In a certain version of Fuse, the Uno.Time namespace was removed to reduce the size of the runtime. This repo provides the code as it was at that time. 

This is only recommended to use if your app had heavy dependencies on the old `Uno.Time` namespace. If a rewrite to use `Uno.DateTime` is viable for you, please do that instad.

This repo is not actively maintained.