# Promt_ImageGenerat
Stable diffusion model to generat the images artificialy by using promt

Download weights and tokenizer files:

1.Download vocab.json and merges.txt from https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main/tokenizer and save them in the data folder
2.Download v1-5-pruned-emaonly.ckpt from https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main and save it in the data folder

Tested fine-tuned models:
Just download the ckpt file from any fine-tuned SD (V1.5).

1.InkPunk Diffusion: https://huggingface.co/Envvi/Inkpunk-Diffusion/tree/main
2.Illustration Diffusion (Hollie Mengert): https://huggingface.co/Envvi/Inkpunk-Diffusion/tree/main

![image](https://github.com/adityakuche/Promt_ImageGenerat/assets/48022963/966fc705-438b-46e4-adb5-aa328ab01873)

providing promt in  demo.ipynb
prompt = "A cat stretching on the floor, highly detailed, ultra sharp, cinematic, 100mm lens, 8k resolution."
Result:
![image](https://github.com/adityakuche/Promt_ImageGenerat/assets/48022963/9f9d8930-ec90-477d-8e91-fb7389d5e6e6)

prompt = "A dog on the floor, highly detailed, ultra sharp, cinematic, 100mm lens, 8k resolution."
Result:
![image](https://github.com/adityakuche/Promt_ImageGenerat/assets/48022963/2a07249b-de46-43f4-bd33-8e2a97123570)

Referance:
1.https://github.com/CompVis/stable-diffusion/
2.https://github.com/divamgupta/stable-diffusion-tensorflow
3.https://github.com/kjsman/stable-diffusion-pytorch
4.https://github.com/huggingface/diffusers/
