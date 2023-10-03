# super-lora
Infer multiple LoRA module with one main model

Have a single main model deployed to the GPU, and multiple LoRA modules on the other. Evoke a particular LoRA module, combine at runtime at the same GPU as the model, and send back the inference, and delete LoRA from main model GPU.

![Uploading Untitled (5).png…](Bare minimum tech architecture)
