# super-lora
Infer multiple LoRA module with one main model

Have a single main model deployed to the GPU, and multiple LoRA modules on the other. Evoke a particular LoRA module, combine at runtime at the same GPU as the model, and send back the inference, and delete LoRA from main model GPU.

<img width="2432" alt="Bare minimum tech architecture" src="https://github.com/aashay96/super-lora/assets/8274603/41044276-f5cf-4286-8037-b3caee2bf337">

