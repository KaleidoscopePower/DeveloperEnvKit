```bash
  595  tail -f /var/log/jenkins/jenkins.log
  596  tail -f /var/log/jenkins/jenkins.log
  597  ls
  598  sudo su jenkins 
  599  wget https://storage.googleapis.com/golang/go1.7.3.linux-amd64.tar.gz
  600  ls
  601  rm -rf go1.7.3.linux-amd64.tar.gz 
  602  sudo su jenkins 
  603  sudo vim /etc/hosts
  604  ls
  605  wget https://storage.googleapis.com/golang/go1.7.3.linux-amd64.tar.gz
  606  sudo vim /etc/hosts
  607  sudo service networking restart 
  608  tail -f /var/log/jenkins/jenkins.log
  609  ls
  610  rm -rf go1.7.3.linux-amd64.tar.gz 
  611  ls
  612  cat xinzhili-shared.pem 
  613  ls
  614  sudo service jenkins restart 
  615  ls -la
  616  ls
  617  sudo su jenkins 
  618  ls
  619  ping 10.0.1.38
  620  ls
  621  ls -la
  622  ;s
  623  ls -la
  624  ls
  625  apt show go
  626  apt show golang
  627  sudo vim /etc/hosts
  628  sudo service networking restart 
  629  df -h
  630  ls
  631  sudo su jenkins 
  632  ls
  633  sudo su jenkins 
  634  sudo vim /etc/profile.d/android.sh
  635  ls
  636  source /etc/profile
  637  android --help
  638  sudo chmod -R 755 /var/lib/jenkins/android/android-sdk-linux
  639  android --help
  640  sudo apt-get install ia32-libs
  641  sudo apt install ia32-libs
  642  ls -la
  643  ls
  644  pwd
  645  ls
  646  ls -la
  647  ls
  648  df -h
  649  ls -la
  650  ls
  651  ls -la
  652  ls
  653  ls -la
  654  ls
  655  ls -la
  656  sudo su jenkins 
  657  ls
  658  ls -la
  659  ls
  660  ls -la
  661  ls
  662  sudo su jenkins 
  663  ls
  664  echo  $ANDROID_HOME 
  665  sudo su jenkins 
  666  sudo service jenkins restart 
  667  sudo su jenkins 
  668  echo  $ANDROID_HOME 
  669  ls -la
  670  ls
  671  sudo su jenkins 
  672  df -h
  673  ls -la
  674  sudo service jenkins restart 
  675  sudo su jenkins 
  676  ls
  677  sudo chown -R jenkins Xinzhili.jks 
  678  sudo mv Xinzhili.jks /var/lib/jenkins/android/
  679  free -h
  680  sudo mv Xinzhili.jks /var/lib/jenkins/android/
  681  ls
  682  rm -rf xinzhili-shared.pem 
  683  ls
  684  free -h
  685  ls
  686  sudo su jenkins 
  687  free -h
  688  ps aux | grep java
  689  ls
  690  ps aux | grep java
  691  ls -la
  692  ls
  693  sudo su jenkins 
  694  ls -la
  695  ls
  696  sudo su jenkins 
  697  df -h
  698  ls -la
  699  ls
  700  ls -la
  701  ls
  702  sudo apt upgrade 
  703  sudo service jenkins restart 
  704  systemctl status jenkins.service
  705  df -h
  706  ls
  707  df -h
  708  sudo su jenkins 
  709  ls -la
  710  ls
  711  df -h
  712  ls
  713  sudo service jenkins status 
  714  ls
  715  ls -la
  716  ls
  717  ls -la
  718  ls
  719  tail -f /var/log/jenkins/jenkins.log
  720  ls
  721  free -h
  722  df -h
  723  docker ps
  724  sudo su jenkins 
  725  sudo service jenkins restart 
  726  tail -f /var/log/jenkins/jenkins.log
  727  sudo service jenkins restart 
  728  tail -f /var/log/jenkins/jenkins.log
  729  sudo su jenkins 
  730  tail -f /var/log/jenkins/jenkins.log
  731  tail -1000f /var/log/jenkins/jenkins.log
  732  docker login registry.xzlcorp.com
  733  ls
  734  sudo apt update 
  735  sudo apt upgrade 
  736  wget https://mirrors.tuna.tsinghua.edu.cn/jenkins/debian-stable/jenkins_2.19.3_all.deb
  737  sudo dpkg -i jenkins_2.19.3_all.deb 
  738  sudo service jenkins restart 
  739  tail -1000f /var/log/jenkins/jenkins.log
  740  ls -la
  741  ls
  742  curl
  743  curl registry.xzlcorp.com
  744  curl https://registry.xzlcorp.com
  745  curl https://git.xzlcorp.com
  746  docker ps
  747  docker help login
  748  docker help
  749  docker pull
  750  docker pull registry.xzlcorp.com/corp/mas-service
  751  docker pull https://registry.xzlcorp.com/corp/mas-service
  752  docker build -t registry.xzlcorp.com/corp/mas-service:master --pull=true /var/lib/jenkins/workspace/mas-service-build
  753  sudo su jenkins 
  754  sudo gpasswd -a jenkins docker
  755  sudo service docker restart
  756  sudo su jenkins 
  757  sudo pip install awscli
  758  easy_install
  759  sudo apt install python-setuptools
  760  sudo apt install python3-setuptools
  761  sudo easy_install3 awscli
  762  aws
  763  aws rds help
  764  aws rds download-db-log-file-portion --db-instance-identifier prod-0     --log-file-name 'error/postgresql.log.2016-11-18-06' --starting-token 0 --output text --debug
  765  vim .aws/credentials
  766  mkdir .aws
  767  ls
  768  vim .aws/credentials
  769  vim .aws/config
  770  aws rds download-db-log-file-portion --db-instance-identifier prod-0     --log-file-name 'error/postgresql.log.2016-11-18-06' --starting-token 0 --output text --debug
  771  aws rds download-db-log-file-portion --db-instance-identifier prod-0     --log-file-name 'error/postgresql.log.2016-11-18-06' --starting-token 0 --output text --debug > full.txt
  772  aws --output text rds describe-db-log-files --db-instance-identifier prod-0
  773  aws rds download-db-log-file-portion --db-instance-identifier prod-0 --log-file-name error/error/postgresql.log.2016-11-18-07 --starting-token 0 --output text > full.txt
  774  aws rds download-db-log-file-portion --db-instance-identifier prod-0 --log-file-name error/postgresql.log.2016-11-18-07 --starting-token 0 --output text > full.txt
  775  ;s
  776  ls
  777  cat full.txt 
  778  aws rds download-db-log-file-portion --db-instance-identifier prod-0 --log-file-name error/postgresql.log.2016-11-18-01 --starting-token 0 --output text > full.txt
  779  cat full.txt 
  780  ls
  781  ls -la
  782  ls
  783  sudo apt upgrade 
  784  sudo su jenkins 
  785  tail -1000f /var/log/jenkins/jenkins.log
  786  sudo su jenkins 
  787  tail -1000f /var/log/jenkins/jenkins.log
  788  sudo su jenkins 
  789  sudo service jenkins restart 
  790  tail -1000f /var/log/jenkins/jenkins.log
  791  sudo service jenkins restart 
  792  tail -1000f /var/log/jenkins/jenkins.log
  793  sudo su jenkins 
  794  git status 
  795  sudo su jenkins 
  796  sudo apt upgrade 
  797  sudo su jenkins 
  798  ls -ls
  799  sudo su jenkins 
  800  ls
  801  sudo su jenkins 
  802  ls
  803  ls -la
  804  sudo apt upgrade 
  805  sudo su jenkins 
  806  sudo service jenkins restart 
  807  tail -1000f /var/log/jenkins/jenkins.log
  808  wget https://mirrors.tuna.tsinghua.edu.cn/jenkins/debian-stable/jenkins_2.19.4_all.deb
  809  tail -1000f /var/log/jenkins/jenkins.log
  810  java
  811  java -version
  812  sudo add-apt-repository ppa:webupd8team/java
  813  sudo apt update 
  814  sudo apt install oracle-java8-installer
  815  java -version
  816  sudo service jenkins restart 
  817  tail -1000f /var/log/jenkins/jenkins.log
  818  ls -la
  819  ls
  820  sudo dpkg -i jenkins_2.19.
  821  sudo dpkg -i jenkins_2.19.4_all.deb 
  822  sudo service jenkins restart 
  823  tail -1000f /var/log/jenkins/jenkins.log
  824  sudo vim /etc/default/jenkins 
  825  sudo service jenkins restart 
  826  tail -1000f /var/log/jenkins/jenkins.log
  827  ls
  828  tail -1000f /var/log/jenkins/jenkins.log
  829  ls -la
  830  ls
  831  curl https://git.xzlcorp.com
  832  nslookup git.xzlcorp.om
  833  nslookup git.xzlcorp.com
  834  ls -la
  835  tail -1000f /var/log/jenkins/jenkins.log
  836  sudo vim /etc/default/jenkins 
  837  sudo service jenkins restart 
  838  tail -1000f /var/log/jenkins/jenkins.log
  839  sudo apt upgrade 
  840  tail -1000f /var/log/jenkins/jenkins.log
  841  sudo su jenkins 
  842  sudo service jenkins restart 
  843  tail -1000f /var/log/jenkins/jenkins.log
  844  ping github.com
  845  ssh je
  846  sudo su jenkins 
  847  ssh dev@172.16.10.12
  848  sudo su jenkins 
  849  sudo apt update 
  850  sudo apt upgrade 
  851  sudo apt update 
  852  sudo apt upgrade 
  853  sudo apt autoremove
  854  docker ps
  855  sudo service jenkins restart
  856  ps -ef | grep jenkins
  857  sudo su jenkins 
  858  sudo service jenkins restart 
  859  sudo su jenkins 
  860  sudo service jenkins restart 
  861  sudo su jenkins 
  862  sudo service jenkins restart 
  863  tail -1000f /var/log/jenkins/jenkins.log
  864  sudo service jenkins restart 
  865  tail -1000f /var/log/jenkins/jenkins.log
  866  sudo su jenkins 
  867  tail -1000f /var/log/jenkins/jenkins.log
  868  sudo su jenkins 
  869  sudo service jenkins restart 
  870  tail -1000f /var/log/jenkins/jenkins.log
  871  sudo su
  872  sudo su jenkins 
  873  sudo vim /etc/apt/sources.list
  874  sudo vim /etc/apt/sources.list.d/jenkins.list
  875  ls
  876  sudo vim /etc/apt/sources.list.d/docker.list
  877  sudo apt-key adv --keyserver hkp://p80.pool.sks-keyservers.net:80 --recv-keys 58118E89F3A912897C070ADBF76221572C52609D
  878  echo "deb https://mirrors.tuna.tsinghua.edu.cn/docker/apt/repo ubuntu-xenial main" | sudo tee /etc/apt/sources.list.d/docker.list
  879  sudo apt update 
  880  sudo apt upgrade 
  881  sudo apt autoremove 
  882  ls
  883  rm -rf jenkins_2.19.*
  884  wget https://mirrors.tuna.tsinghua.edu.cn/jenkins/debian-stable/jenkins_2.32.1_all.deb
  885  sudo dpkg -i jenkins_2.32.1_all.deb 
  886  sudo service jenkins restart 
  887  tail -1000f /var/log/jenkins/jenkins.log
  888  sudo apt install build-essential libssl-dev libffi-dev python-dev
  889  sudo apt update 
  890  sudo apt upgrade 
  891  sudo apt update 
  892  sudo apt upgrade 
  893  wget http://get.jenv.mvnsearch.org/download/gradle/gradle-3.2.1.zip
  894  ls
  895  rm -rf gradle-3.2.1.zip 
  896  ls
  897  rm -rf jenkins_2.32.1_all.deb 
  898  cat full.txt 
  899  rm -rf full.txt 
  900  ls
  901  sudo su jenkins 
  902  tail -1000f /var/log/jenkins/jenkins.log
  903  sudo service jenkins restart 
  904  ping 172.31.2.237
  905  hostname -i
  906  sudo apt update 
  907  sudo apt upgrade 
  908  python
  909  python3
  910  ls -la
  911  ls
  912  sudo su jenkins 
  913  sudo service jenkins restart 
  914  docker ps
  915  ps -ef | grep java
  916  df -h
  917  top
  918  ssh 172.31.2.214
  919  sudo apt update 
  920  sudo apt upgrade 
  921  sudo apt autoremove 
  922  sudo su jenkins 
  923  sudo service jenkins stop
  924  sudo apt upgrade 
  925  java -version
  926  jvisualvm --version
  927  ps aux | grep jvisualvm
  928  ps aux | grep java
  929  ls -la
  930  ls
  931  ls -la
  932  ls
  933  sudo apt update 
  934  sudo apt upgrade 
  935  sudo su jenkins 
  936  tail -1000f /var/log/jenkins/jenkins.log
  937  sudo service jenkins restart 
  938  tail -1000f /var/log/jenkins/jenkins.log
  939  ls
  940  sudo service jenkins restart 
  941  ls
  942  tail -1000f /var/log/jenkins/jenkins.log
  943  ls
  944  sudo su jenkins 
  945  sudo service jenkins restart 
  946  tail -1000f /var/log/jenkins/jenkins.log
  947  ls
  948  sudo su jenkins 
  949  sudo service jenkins restart 
  950  tail -1000f /var/log/jenkins/jenkins.log
  951  sudo service jenkins restart 
  952  wget https://nodejs.org/dist/v7.5.0/node-v7.5.0-linux-x64.tar.gz
  953  ls -la
  954  rm -rf node-v7.5.0-linux-x64.tar.gz 
  955  ls -la
  956  sudo su jenkins 
  957  sudo service jenkins restart 
  958  tail -1000f /var/log/jenkins/jenkins.log
  959  sudo su jenkins 
  960  sudo apt install npm
  961  apt search node
  962  apt search nodejs
  963  apt info nodejs
  964  apt search nodejs
  965  apt search npm
  966  sudo apt install npm
  967  sudo apt install nodejs
  968  nodejs 
  969  ls =-la
  970  npm
  971  sudo apt install npm
  972  sudo apt install cnpm
  973  npm install cnpm
  974  npm
  975  which np,
  976  which npm
  977  ls -=la
  978  ls -la
  979  ls
  980  sudo npm install -g gulp --registry=https://registry.npm.taobao.org
  981  glup
  982  ls -la
  983  /usr/local/lib/node_modules/gulp/bin/gulp.js 
  984  node /usr/local/lib/node_modules/gulp/bin/gulp.js 
  985  ls /usr/local/lib
  986  sudo apt install glup
  987  sudo apt install node-glup
  988  apt search glup
  989  npm list -g
  990  node '
  991  node
  992  sudo apt install nodejs-legacy
  993  node /usr/local/lib/node_modules/gulp/bin/gulp.js
  994  node
  995  node --help
  996  npm install --global gulp-cli
  997  sudo npm install --global gulp-cli --registry=https://registry.npm.taobao.org
  998  ls -la
  999  mkdir temp
 1000  cd temp/
 1001  ls
 1002  npm install --save-dev gulp
 1003  npm install --save-dev gulp --registry=https://registry.npm.taobao.org
 1004  glup
 1005  gulp 
 1006  ls -la
 1007  ls
 1008  ls -la
 1009  ls
 1010  sudo su jenkins 
 1011  ls -la
 1012  rm -rf temp
 1013  ls -la
 1014  wget https://github.com/sass/node-sass/releases/download/v3.13.1/linux-x64-46_binding.node
 1015  sudo vim /etc/hosts
 1016  wget https://github.com/sass/node-sass/releases/download/v3.13.1/linux-x64-46_binding.node
 1017  ls
 1018  rm -rf linux-x64-46_binding.node*
 1019  ls -la
 1020  sudo su jenkins 
 1021  ls -la
 1022  git status 
 1023  ls -la
 1024  sudo su jenkins 
 1025  sudo service jenkins stop
 1026  ls -la
 1027  sudo su jenkins 
 1028  sudo service jenkins start 
 1029  ls -la
 1030  ls
 1031  sudo su jenkins 
 1032  sudo vim /etc/hosts
 1033  sudo service networking restart 
 1034  ls -la
 1035  sudo su jenkins 
 1036  docker ps
 1037  npm
 1038  ls
 1039  ps -ef | grep jenkins
 1040  cd /var/lib/jenkins/
 1041  ls
 1042  cd tools/
 1043  ls
 1044  cd jenkins.plugins.nodejs.tools.NodeJSInstallation/
 1045  ls
 1046  cd NodeJS7.x/
 1047  ls
 1048  cd bin/
 1049  ls
 1050  ls -la
 1051  ls
 1052  sudo su jenkins 
 1053  ls
 1054  sudo chown -R jenkins linux-x64-51_binding.node 
 1055  sudo su jenkins 
 1056  sudo mv linux-x64-51_binding.node /var/lib/jenkins/
 1057  sudo su jenkins 
 1058  ls -la
 1059  ls
 1060  cat .sudo_as_admin_successful 
 1061  ls
 1062  rm -rf a.txt 
 1063  ls -la
 1064  ls -la
 1065  touch a.txt
 1066  ls
 1067  vim a.txt 
 1068  sudo su jenkins 
 1069  sudo service jenkins restart 
 1070  ls -la
 1071  tail -1000f /var/log/jenkins/jenkins.log
 1072  sudo su jenkins 
 1073  sudo apt install png-dev
 1074  sudo apt install libpng
 1075  apt search libpng
 1076  sudo apt install libpng16-16
 1077  sudo su jenkins 
 1078  sudo apt update 
 1079  java
 1080  sudo apt upgrade 
 1081  sudo apt autoremove 
 1082  cat /etc/issue
 1083  sudo apt upgrade 
 1084  wget services.gradle.org/distributions/gradle-3.4.1-all.zip
 1085  rm -rf gradle-3.4.1-all.zip 
 1086  sudo service jenkins restart 
 1087  sudo apt upgrade 
 1088  ja
 1089  java -version
 1090  sudo su jenkins 
 1091  tail -1000f /var/log/jenkins/jenkins.log
 1092  which cnpm
 1093  which npm
 1094  npm --version
 1095  npm install cnpm -g --registry=https://registry.npm.taobao.org
 1096  sudo npm install cnpm -g --registry=https://registry.npm.taobao.org
 1097  which cnpm
 1098  cnpm -version
 1099  sudo cnpm install webpack -g
 1100  node -version
 1101  node --version
 1102  npm install -g n
 1103  sudo npm install -g n
 1104  n
 1105  n 7.x
 1106  sudo n 7
 1107  n
 1108  node --version
 1109  n
 1110  which node
 1111  node --version
 1112  which node
 1113  ls
 1114  n latest
 1115  n stable
 1116  sudo n stable
 1117  n
 1118  n -v
 1119  node -v
 1120  which -a node
 1121  node -v
 1122  sudo apt upgrade 
 1123  sudo apt autoremove 
 1124  sudo su jenkins 
 1125  ls
 1126  sudo apt update 
 1127  sudo apt upgrade 
 1128  ls
 1129  ls -la
 1130  ls
 1131  du -h /var/lib/jenkins
 1132  df -h
 1133  ls
 1134  df -h
 1135  ls
 1136  ls -la
 1137  sudo su jenkins 
 1138  docker images
 1139  docker images -q
 1140  docker images -q | docker rmi -f
 1141  docker images -q | docker rmi 
 1142  docker images -q | xargs docker rmi 
 1143  docker image
 1144  docker images 
 1145  df -h
 1146  sudo service jenkins restart 
 1147  tail -1000f /var/log/jenkins/jenkins.log
 1148  sudo su jenkins 
 1149  ls
 1150  sudo su jenkins 
 1151  ls
 1152  sudo su jenkins 
 1153  sudo su
 1154  sudo su jenkins 
 1155  ls
 1156  sudo su jenkins 
 1157  ls
 1158  sudo su jenkins 
 1159  sudo service jenkins stop
 1160  sudo su jenkins 
 1161  sudo service jenkins restart 
 1162  tail -1000f /var/log/jenkins/jenkins.log
 1163  ls
 1164  ls -la
 1165  sudo su jenkins 
 1166  sudo apt upgrade 
 1167  docker
 1168  docker ps
 1169  sudo apt autoremove 
 1170  sudo service jenkins restart 
 1171  sudo apt update 
 1172  sudo apt upgrade jenkins
 1173  sudo apt install jenkins
 1174  tail -1000f /var/log/jenkins/jenkins.log
 1175  sudo service jenkins restart 
 1176  sudo apt upgrade 
 1177  bg
 1178  fg
 1179  sudo apt upgrade 
 1180  git clone git@github.com:douglarek/fish.git
 1181  git clone https://github.com/douglarek/fish.git
 1182  cd fish/
 1183  git log
 1184  git show
 1185  ls
 1186  git show
 1187  ls
 1188  git shjow
 1189  git show
 1190  ls
 1191  cd ..
 1192  ls
 1193  rm -rf fish
 1194  ps aux | grep a[t
 1195  ps aux | grep apt
 1196  sudo apt upgrade 
 1197  sudo apt autoremove 
 1198  curl https://lingchao.xin
 1199  curl -i https://douglarek.github.io
 1200  sudo apt update 
 1201  sudo apt upgrade 
 1202  sudo apt autoremove 
 1203  sudo su jenkins 
 1204  sudo apt autoremove 
 1205  df -h
 1206  ls -la
 1207  sudo service jenkins stop
 1208  sudo service jenkins start
 1209  df -h
 1210  tail -1000f /var/log/jenkins/jenkins.log
 1211  ls -la
 1212  sudo su jenkins 
 1213  ls -la
 1214  ls
 1215  sudo su jenkins 
 1216  ls -ls
 1217  sudo su jenkins 
 1218  sudo service jenkins restart 
 1219  sudo apt update 
 1220  sudo apt upgrade 
 1221  sudo apt autoremove 
 1222  ls -la
 1223  ls
 1224  sudo su jenkins 
 1225  tar
 1226  sudo su jenkins 
 1227  free -h
 1228  sudo su jenkins 
 1229  free -h
 1230  sudo apt update 
 1231  sudo apt upgrade 
 1232  sudo apt update 
 1233  sudo apt upgrade 
 1234  sudo apt autoremove 
 1235  ls
 1236  aws
 1237  pip install --upgrade --user awscli
 1238  sudo apt install python-pip
 1239  sudo su jenkins 
 1240  sudo apt update 
 1241  sudo apt upgrade 
 1242  sudo service jenkins restart 
 1243  sudo apt upgrade 
 1244  sudo service jenkins restart 
 1245  sudo apt autoremove 
 1246  sudo service jenkins restart 
 1247  sudo atp upd
 1248  sudo atp update
 1249  sudo apt update 
 1250  sudo apt upgrade 
 1251  sudo apt update 
 1252  sudo apt upgrade 
 1253  sudo apt autoremove 
 1254  sudo service jenkins restart 
 1255  cd
 1256  sudo apt update 
 1257  sudo apt upgrade 
 1258  sudo service jenkins restart 
 1259  tail -1000f /var/log/jenkins/jenkins.log
 1260  sudo apt update 
 1261  sudo apt upgrade 
 1262  sudo service jenkins restart 
 1263  sudo apt update 
 1264  sudo apt upgrade 
 1265  sudo apt update 
 1266  sudo apt upgrade 
 1267  sudo apt autoremove 
 1268  sudo service jenkins restart 
 1269  tail -1000f /var/log/jenkins/jenkins.log
 1270  sudo service jenkins restart 
 1271  df -h
 1272  cat .docker/config.json 
 1273  sudo service jenkins restart 
 1274  sudo su jenkins 
 1275  ls -la
 1276  df -h
 1277  sudo su jenkins 
 1278  sudo vim /etc/hosts
 1279  ls
 1280  sudo vim /etc/hosts
 1281  sudo service networking restart 
 1282  sudo apt update 
 1283  ls -la
 1284  git diff
 1285  ls -la
 1286  sudo service jenkins restart 
 1287  tail -1000f /var/log/jenkins/jenkins.log
 1288  ls -la
 1289  sudo su jenkins 
 1290  ks 0ka
 1291  ls -la
 1292  sudo su jenkins 
 1293  pwd
 1294  ls /opt/
 1295  sudo su jenkins 
 1296  sudo mv /var/lib/jenkins/java9/jdk-9 /opt/
 1297  cp -a /var/lib/jenkins/java9/java.tar.gz .
 1298  ls
 1299  which java
 1300  java -version
 1301  curl -s "https://get.sdkman.io" | bash
 1302  sudo apt install zip
 1303  curl -s "https://get.sdkman.io" | bash
 1304  sdk 
 1305  sdk install jenv
 1306  sdk list
 1307  curl -L -s get.jenv.io | bash
 1308  jenv
 1309  jenv list java
 1310  jenv selfupdate 
 1311  jenv list java
 1312  jenv install java 9
 1313  java
 1314  java -versi0on
 1315  java -version
 1316  sudo service jenkins restart 
 1317  tail -1000f /var/log/jenkins/jenkins.log
 1318  sudo su jenkins 
 1319  sudo apt update 
 1320  sudo apt upgrade 
 1321  tail -1000f /var/log/jenkins/jenkins.log
 1322  sudo su
 1323  ls -la
 1324  sudo su
 1325  sudo vim /etc/hosts
 1326  sudo service networking restart 
 1327  ls
 1328  java -version
 1329  history
 1330  ls
 1331  history >cmd
 1332  ls
 1333  mv cmd jekins_cmd
 1334  ls
 1335  rm jekins_cmd 
 1336  ls
 1337  docker login registry.xzlcorp.com
 1338  ls
 1339  ps -ef | grep jenkins
 1340  java -v
 1341  java -version
 1342  docker ps
 1343  jenv versions
 1344  jenv --help
 1345  jenv versions
 1346  jenv all
 1347  jenv --help
 1348  man jenv
 1349  jenv -help
 1350  ls
 1351  java -version
 1352  ps -ef | grep jenkins
 1353  cd /usr/share/
 1354  ls
 1355  sudo su 
 1356  ls
 1357  history >> SHARED-JENKINS-daqiang-his.txt
 1358  cat SHARED-JENKINS-daqiang-his.txt 
 1359  exit
 1360  docker ps
 1361  docker images
 1362  docker logs
 1363  su jenkins
 1364  su ff
 1365  su jen
 1366  su jenkins
 1367  finger
 1368  cat /etc/passwd
 1369  passwd jenkins jenkins
 1370  cat /etc/group
 1371  su docker
 1372  su root
 1373  w
 1374  cut -d : -f 1 /etc/passwd
 1375  cat /etc/pa
 1376  cat /etc/passwd
 1377  su jenkins
 1378  su ls
 1379  sudo ls
 1380  passwd jenkins jenkins123
 1381  passwd jenkins
 1382  su root
 1383  eixt
 1384  exit
 1385  su root
 1386  sudo passwd root
 1387  su root
 1388  su jenkins
 1389  docker ps
 1390  ls
 1391  ps -e | grep nginx
 1392  ps -ef
 1393  exit
 1394  ls
 1395  cd /etc/
 1396  ls
 1397  whereis jenkins
 1398  cd /usr/share/jenkins/
 1399  ls
 1400  jps
 1401  ps -ef | grep jenkins
 1402  cd /var/lib/
 1403  ls
 1404  cd jenkins/
 1405  ls
 1406  whereis matrix
 1407  matrix.py
 1408  whereis matrix.py
 1409  find matrix.py
 1410  locate
 1411  locate matrix.py
 1412  cd work
 1413  cd workspace/
 1414  ls
 1415  cd fab@2/
 1416  ls
 1417  cat matrix.py 
 1418  cd ..
 1419  ls
 1420  ls *fab*
 1421  cd prod-fab
 1422  cat matrix.py 
 1423  exit
 1424  history | grep jenk
 1425  ps -aux | grep jenk
 1426  history | grep user
 1427  history | grep usr
 1428  history | grep jenkins
 1429  history | grep add
 1430  cut -d : -f 1 /etc/passw
 1431  su root
 1432  exit
 1433  ps -ef
 1434  systemd --version 
 1435  ps -ef | grep systemc
 1436  ps -ef | grep system
 1437  exit
 1438  root
 1439  su root
 1440  su jenkins 
 1441  history | grep jenkins
 1442  type jenkins
 1443  whereis jenkins
 1444  ps -ef | grep je
 1445  exit
 1446  su root
 1447  history | grep jenki
 1448  sudo service jenkins restart
 1449  ps -ef | grep jen
 1450  su root
 1451  history | tail
 1452  sudo service jenkins restart
 1453  su root
 1454  sudo service jenkins restart
 1455  su root
 1456  sudo service jenkins restart
 1457  su root
 1458  sudo service jenkins restart
 1459  su root
 1460  sudo service jenkins restart
 1461  su root
 1462  exit
 1463  ls
 1464  sudo mv config.xml /var/lib/jenkins/users/daqiang/
 1465  history | grep restart
 1466  sudo service jenkins restart
 1467  exit
 1468  locate jenkins
 1469  ps -ef | grep jenkins
 1470  cd /var/lib/jenkins/
 1471  ls
 1472  cd jobs/
 1473  ls
 1474  cd fab/
 1475  ls
 1476  cd ..
 1477  ls
 1478  whereis matrix.py
 1479  locate matrix.py
 1480  cd ..
 1481  cd workspace/
 1482  cd fab@2/
 1483  cat matrix.py 
 1484  ls
 1485  cd ..
 1486  ls
 1487  cd prod-fab
 1488  ls
 1489  cat matrix.py 
 1490  ls
 1491  cat config.py 
 1492  sudo vim  matrix.py 
 1493  locate matrix.py
 1494  docker ps
 1495  ps -ef | grep jenkins
 1496  sudo vim  matrix.py 
 1497  cd ..
 1498  ls
 1499  cd logs/
 1500  ls
 1501  cd tasks/
 1502  ls
 1503  ll
 1504  cd ..
 1505  ls
 1506  cd slaves/
 1507  ;s
 1508  ls
 1509  cd local/
 1510  ls
 1511  cat slave.log 
 1512  ls
 1513  cd ..
 1514  ls
 1515  cd tasks/
 1516  ls
 1517  ll
 1518  cat Connection\ Activity\ monitoring\ to\ agents.log
 1519  cat Download\ metadata.log
 1520  cat Fingerprint\ cleanup.log
 1521  ls
 1522  ll
 1523  cat Workspace\ clean-up.log
 1524  cd ..
 1525  ls
 1526  cd /var/log/jenkins/
 1527  ls
 1528  cat jenkins.log
 1529  cd /var/lib/jenkins/
 1530  ls
 1531  cd workspace/
 1532  ls
 1533  cd prod-fab
 1534  ls
 1535  cat matrix.py 
 1536  cd ..
 1537  ls
 1538  cd fab@2/
 1539  ls
 1540  cat matrix.py 
 1541  cat /etc/hosts
 1542  cat /etc/hosts | grep 172
 1543  ls
 1544  cat fabfile.py 
 1545  cd ..
 1546  cd prod-fab
 1547  ls
 1548  cat matrix.py 
 1549  cp matrix.py ./matrix2.py 
 1550  sudo cp matrix.py ./matrix2.py 
 1551  ls
 1552  vim matrix2.py 
 1553  sudo vim matrix2.py 
 1554  cd /home/ubuntu
 1555  ls
 1556  cd /var/lib/jenkins/workspace/prod-fab
 1557  ls
 1558  rm matrix2.py 
 1559  sudo rm matrix2.py 
 1560  cat matrix.py 
 1561  vim matrix.py 
 1562  cat matrix.py 
 1563  sudo find / -name "jenkins" 2>> /dev/null 
 1564  history | jenkins
 1565  history | grep jenkins
 1566  sudo su jenkins
 1567  docker ps
 1568  docker images
 1569  sudo find / -name "*c3c763d20150*" 2>> /dev/null 
 1570  cd /var/lib/docker/image/devicemapper/imagedb/content/sha256
 1571  sudo cd /var/lib/docker/image/devicemapper/imagedb/content/sha256
 1572  exit
 1573  history
 1574  pwd
 1575  sudo su jenkins
 1576  sudo su root
 1577  cd /home/ubuntu/
 1578  ls
 1579  exit
 1580  ps -ef | grep jenkins
 1581  history | grep jenkins
 1582  sudo service jenkins restart
 1583  history | grep jen
 1584  sudo service jenkins restart
 1585  ps -e | grep jenkins
 1586  ps -e
 1587  ps -aux
 1588  ps -aux | grep jenkins
 1589  sudo kill -9 16775
 1590  ps -aux | grep jenkins
 1591  node -v
 1592  history | grep zlib
 1593  history | grep libpng
 1594  history >> log.txt

```

