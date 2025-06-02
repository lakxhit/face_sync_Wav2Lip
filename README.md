 Wav2Lip HQ local installation, fully running on Torch to ONNX converted models for:
- face-detection
- face-recognition
- face-alignment
- face-parsing
- face-enhancement
- wav2lip inference.



Can be run on CPU or Nvidia GPU

Model download - https://drive.google.com/drive/folders/1BGl9bmMtlGEMx_wwKufJrZChFyqjnlsQ?usp=sharing  

Original wav2lip - https://github.com/Rudrabha/Wav2Lip

Face enhancers taken from -  https://github.com/harisreedhar/Face-Upscalers-ONNX

Face detection taken from - https://github.com/neuralchen/SimSwap

Face occluder taken from - https://github.com/facefusion/facefusion-assets/releases

Blendmasker extracted from - https://github.com/mapooon/BlendFace during onnx conversion

Face recognition for specifc face taken from - https://github.com/jahongir7174/FaceID


How to run this project:-
This can be done in cmd
Download the zip file,extract it 
Make 2 folders:-1.Example-containing audio(.wav) of a language and video_(.mp4) which you want to sync 2.Result:- Folder where result will be store after running
This project uses cuda so make sure you have downloaded it
Download the requirement.txt from the folder
Download models from the above link (Model download),and place them in blendmasker folder ,enhancers and face_occluder
Run python file inference_onnxModel_V2 in cmd where your folder is present 
Copy the code from the Code file in git and paste it 
After running select or crop region to sync with audio
The synchronized video is then saved in result folder


