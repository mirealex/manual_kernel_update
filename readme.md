1. centos.json поправил под свежую версию packer - 1.7.9
   "iso_checksum": "sha256:07b94e6b1a0b0260b94c83d6bb76b26bf7a310dc78d7a9c7432809fb9bc6194a"
2. там же увеличил время ожидания ssh до 40 минут - слабая хост-машина
   "ssh_wait_timeout": "40m"