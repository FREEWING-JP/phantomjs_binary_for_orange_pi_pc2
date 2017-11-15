# PhantomJS 2.1.1 binary for Orange Pi PC2

★ Orange Pi PC 2を買ってみた、Allwinner H5 Cortex-A53 4core ARM64  
http://www.neko.ne.jp/~freewing/raspberry_pi/orange_pi_pc2/  

## phantomjs_2.1.1_orangepi_pc2_aarch64_ubuntu_xenial.tar.gz

PhantomJS 2.1.1 binary for Orange Pi PC 2 with Ubuntu 16.04 Xenial 2017-11  

Orange Piの活用方法 Ubuntu 16.04 Xenialで PhantomJS 2.1.1をビルドする方法  
http://www.neko.ne.jp/~freewing/raspberry_pi/orange_pi_pc2_phantomjs_211_xenial/  

## bash script direct execute

```
mkdir ~/phantomjs_tmp
cd ~/phantomjs_tmp

BASE_URL=https://github.com/FREEWING-JP/phantomjs_binary_for_orange_pi_pc2/raw/master/

TAR_FILE=phantomjs_2.1.1_orangepi_pc2_aarch64_ubuntu_xenial.tar.gz
echo ${TAR_FILE}
wget ${BASE_URL}${TAR_FILE}
tar xvf ${TAR_FILE}

ls -l phantomjs
./phantomjs -v
```

