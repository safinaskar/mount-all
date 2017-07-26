cmake_minimum_required (VERSION 3.0.2) # 3.0.2 подходит
project (mount-all LANGUAGES)
install (PROGRAMS mount-all DESTINATION sbin)
install (PROGRAMS umount-all DESTINATION bin)
