Random seed set to: 3386550706
Checking inputs
✅ /tmp/inputs/input.webp
====================================
Running workflow
got prompt
Executing node 22, title: Load Image, class type: LoadImage
Executing node 67, title: 🔧 Image Resize, class type: ImageResize+
Executing node 3, title: LoRA Stacker, class type: LoRA Stacker
Executing node 49, title: AIO Aux Preprocessor, class type: AIO_Preprocessor
Executing node 28, title: Control Net Stacker, class type: Control Net Stacker
Executing node 2, title: Efficient Loader, class type: Efficient Loader
Requested to load SDXLClipModel
Loading 1 new model
----------------------------------------
[36mEfficient Loader Models Cache:[0m
Ckpt:
[1] albedobaseXL_v13
Lora:
[1] base_ckpt: albedobaseXL_v13
lora(mod,clip): 3DRedmond-3DRenderStyle-3DRenderAF(1,1)
Executing node 41, title: Apply InstantID, class type: ApplyInstantID
Executing node 51, title: VAE Encode, class type: VAEEncode
Executing node 4, title: KSampler (Efficient), class type: KSampler (Efficient)
Requested to load SDXL
Requested to load ControlNet
Requested to load ControlNet
Loading 3 new models
  0%|          | 0/20 [00:00<?, ?it/s]
  5%|▌         | 1/20 [00:00<00:05,  3.34it/s]
 10%|█         | 2/20 [00:00<00:05,  3.28it/s]
 15%|█▌        | 3/20 [00:00<00:05,  3.28it/s]
 20%|██        | 4/20 [00:01<00:04,  3.28it/s]
 25%|██▌       | 5/20 [00:01<00:04,  3.29it/s]
 30%|███       | 6/20 [00:01<00:04,  3.29it/s]
 35%|███▌      | 7/20 [00:02<00:03,  3.30it/s]
 40%|████      | 8/20 [00:02<00:03,  3.30it/s]
 45%|████▌     | 9/20 [00:02<00:03,  3.30it/s]
 50%|█████     | 10/20 [00:03<00:03,  3.29it/s]
 55%|█████▌    | 11/20 [00:03<00:02,  3.30it/s]
 60%|██████    | 12/20 [00:03<00:02,  3.30it/s]
 65%|██████▌   | 13/20 [00:03<00:02,  3.30it/s]
 70%|███████   | 14/20 [00:04<00:01,  3.31it/s]
 75%|███████▌  | 15/20 [00:04<00:01,  3.30it/s]
 80%|████████  | 16/20 [00:04<00:01,  3.31it/s]
 85%|████████▌ | 17/20 [00:05<00:00,  3.31it/s]
 90%|█████████ | 18/20 [00:05<00:00,  3.32it/s]
 95%|█████████▌| 19/20 [00:05<00:00,  3.37it/s]
100%|██████████| 20/20 [00:06<00:00,  3.42it/s]
100%|██████████| 20/20 [00:06<00:00,  3.32it/s]
Executing node 5, title: Save Image, class type: SaveImage
Prompt executed in 26.70 seconds
outputs:  {'4': {'images': []}, '5': {'images': [{'filename': 'ComfyUI_00001_.png', 'subfolder': '', 'type': 'output'}]}}
====================================
Contents of /tmp/outputs:
ComfyUI_00001_.png

# -
