#!/bin/sh

#perulangan
ulang='y'
while [ $ulang = 'y' ];
do
  #menu utama
  echo '1) install Red Hawk'
  echo '2) install cmbah-v2'
  echo '3) install LazyGo'
  exho '0) exit '
  #masukan atau input
  read -p 'Masukkan Pilhan anda : ' pil; 
  #kondi jika input = 1 maka akan menginstall redhawk
  if [ $pil = '1' ]
  then
      echo 'installing Red Hawk'
      cd $HOME
      apt update && apt upgrade -y
      apt intall php -y
      apt install git
      git clone https://github.com/Tuhinshubhra/RED_HAWK
      echo 'installing succes....! '
      sleep 1
  #kondisi jika input = 2 maka akan menginstall Cmbah-v2
  elif [ $pil = '2' ];
  then
      echo 'installing Cmbah v2 '
      cd $HOME
      apt update  && apt upgrade -y
      apt install python -y
      apt install git -y
      git clone https://github.com/kadal15/Cmbah-v2
      cd Cmbah-v2
      pip install -r requirements.txt
      echo 'installing succes...! '
      sleep 1
  #kondisi jika input = 3 maka akan menginstall LazyGo
  elif [ $pil = '3' ];
  then
      echo 'installing LazyGo'
      cd $HOME
      apt update && apt upgrade -y
      apt install git
      git clone https://github.com/kadal15/LazyGo.git
      cd LazyGo
      sh install.sh
      echo 'installing succes.. '
      sleep 1
  #kondisi jika input = 0 maka akan keluar dari tools
  elif [ $pil = '0' ];
  then
      echo 'bye bye.....! '
      sleep 2
      exit
  #kodisi else
  else
      echo 'ERROR : Wrong Input....! '
      sleep 1
      echo $ulang
  fi
done
       
