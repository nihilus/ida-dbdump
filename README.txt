ABOUT

this is a small plugin i made for IDA ( http://www.datarescue.com )

it attempts to investigate the internals of IDA.
by dumping the RootNode.
and IDCFuncs

also I figured out how the compiled script functions are encoded,
a small disassembler for idc functions is provided.
dbdump knows how to find the idc compiled code for several ida
versions, but possibly not for all.

HOW TO USE

* install
* startup ida
* type alt-2
* read the 'dump_db.log' file in the directory from where ida was started.


BUILD REQUIREMENTS

* idasdk
* msvc7
* various cygwin utils
* boost libraries


BUILD REMARKS


unzip this source archive in the directory idasdk/plugins/dbdump.

it expects the boost libraries in c:/local/boost/boost_1_35_0
( see http://www.boost.org )

compiler options are known to work with msvc7 
  - compiler version 14.00.50727.762
  - comes with visual studio.net 2005

no attempt has been made to make this very portable.

Makefile needs gnu make. ( for instance from cygwin )


INSTALLATION

* type make
* type make install


AUTHOR

Willem Hengeveld
itsme@xs4all.nl

