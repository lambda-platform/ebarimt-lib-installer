PosAPI lib installer on Linux


git clone https://github.com/lambda-platform/ebarimt-lib-installer

bash install.sh

after install you can check your library is working

check so in ubuntu example

nm -D /home/ebarimtuser/app/libPosAPI.so | grep getInformation

nm -D /usr/lib/libPosAPI.so | grep getInformation