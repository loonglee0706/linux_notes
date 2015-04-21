##scp

**scp [OPTIONS] file_source file_target **

copy local to remote address

`scp local_file remote_username@remote_ip:remote_folder`

`scp local_file remote_username@remote_ip:remote_file `

`scp local_file remote_ip:remote_folder`

`scp local_file remote_ip:remote_file`

复制目录加参数 -r

`scp -r local_folder remote_username@remote_ip:remote_folder `

`scp -r local_folder remote_ip:remote_folder `

copy remote to local

`scp root@www.cumt.edu.cn:/home/root/others/music /home/space/music/1.mp3 `

`scp -r www.cumt.edu.cn:/home/root/others/ /home/space/music/`
