# bootdisk by Matmoul
Simple command to boot device with QEMU/KVM

## Usage :</br>
`bootdisk [options] device|file`</br>
 
 Device | File :</br>
 `/dev/sda, /dev/sdb`</br>
 `file.iso`</br>
 
 Options :</br>
  `--help`</br>
  `-wd : Work Dir (default in tmp random folder, mktemp)`</br>
  `-wdp : Work Dir Persistent`</br>
  `-boot : Boot mode [bios|efi|tpm|secure] (default : efi)`</br>
  `-cores : CPU cores`</br>
  `-mem : Memory in Mb`</br>
  `-dd : additional device`</br>
  `-cdr : Force boot dev as cd-rom (not needed for iso file)`</br>
  `-overlay : Add overlay on boot device`</br>
