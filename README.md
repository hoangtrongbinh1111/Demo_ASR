# Demo_ASR
 #download model and add to /static/resources
https://drive.google.com/file/d/1qk7ilImQcEKLSR5ny-3YkiKdz9RoerqB/view?usp=sharing
# download resources and add to /static/Asset_Record/
https://drive.google.com/file/d/1sQKvz1JigX0b8Hx4Af8Cpk2DS5bz0_LY/view?usp=sharing
# pnk_speech_command_recognition
Vietnamese speech command recognition

## Setup web demo with docker
```
git clone http://gitlab.phenikaa.local.com/hieuhv/asr
cd asr
sudo docker run -it --net host --name asr_demo -v <path_to_save_data_collection>:/home/asr/files hieuhv94/asr:v1.0
```
Go to ASR web demo at https://0.0.0.0:5000/