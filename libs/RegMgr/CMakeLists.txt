cmake_minimum_required (VERSION 2.8)
project (RegMgr)
add_library (RegMgr STATIC 
	regmgr.cpp)
include_directories (../lith) 