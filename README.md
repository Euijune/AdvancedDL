## Generating Image

  python eval-scripts/generate-images.py --model_name='models/compvis-VanGogh-ESDx1-UNET' --prompts_path 'data_from_ESD/0421_reproduce.csv' --save_path 'evaluation_folder' --num_samples 10


## Model Weight

  https://erasing.baulab.info/weights/esd_models/

  esd_models/art: 특정 style지우기

  esd_models/NSFW: Nudity 제거 

  fine-tuned weight를 다운받으면 models아래 하위 폴더를 만들고, 해당 폴더안에 pt파일을 저장
  
    EX) diffusers-VanGogh-ESDx1-UNET.pt파일을 다운받았다면, models/compvis-VanGogh-ESDx1-UNET 폴더를 만들고 그 안에 pt파일 위치



