# EviDiff
EviDiff: Efficient Multi-Object Composition with Evidential Supervision

The trained EviDiff models are available at https://huggingface.co/EviDiff

## 1. Additional qualitative examples
![image](https://github.com/anonymity-coder/EviDiff/blob/main/additional-results.jpg)

## 2. Hyperparameters analysis
| $\lambda_1$    | 	    OA↑	   | FID(C)↑ | FID(F)↑ | CLIP(C)↑ | FID(F)↑ |
| ---------- | --------------- | ------- | ------- |-------- | -------- |
|  5e-4      | 	    0.7109     | 20.11   | 55.26   | 0.3229  | 0.3330   |
|  5e-5      | 	    0.7116     | 20.09   | 55.12   | 0.3241  | 0.3348   |  
|  5e-6      | 	    0.7110     | 20.13   | 55.24   | 0.3237  | 0.3336   |  

| $\lambda_2$    | 	    OA↑	   | FID(C)↑ | FID(F)↑ | CLIP(C)↑ | FID(F)↑ |
| ---------- | --------------- | ------- | ------- |-------- | -------- |
|  5e-6      | 	    0.7105     | 20.17   | 55.33   | 0.3230  | 0.3328   |
|  5e-7      | 	    0.7116     | 20.09   | 55.12   | 0.3241  | 0.3348   |  
|  5e-8      | 	    0.7097     | 20.14   | 55.15   | 0.3234  | 0.3343   |  

| $\lambda_3$    | 	    OA↑	   | FID(C)↑ | FID(F)↑ | CLIP(C)↑ | FID(F)↑ |
| ---------- | --------------- | ------- | ------- |-------- | -------- |
|  5e-6      | 	    0.7114     | 20.17   | 55.33   | 0.3230  | 0.3328   |
|  5e-7      | 	    0.7116     | 20.09   | 55.12   | 0.3241  | 0.3348   |  
|  5e-8      | 	    0.7097     | 20.14   | 55.15   | 0.3234  | 0.3343   |  

| $\eta_1$    | 	    OA↑	   | FID(C)↑ | FID(F)↑ | CLIP(C)↑ | FID(F)↑ |
| ---------- | --------------- | ------- | ------- |-------- | -------- |
|  1e-3      | 	    0.7109     | 20.31   | 55.54   | 0.3226  | 0.3324   |
|  1e-4      | 	    0.7116     | 20.09   | 55.12   | 0.3241  | 0.3348   |  
|  1e-5      | 	    0.7102     | 20.28   | 55.32   | 0.3230  | 0.3315   |

| $\eta_2$    | 	    OA↑	   | FID(C)↑ | FID(F)↑ | CLIP(C)↑ | FID(F)↑ |
| ---------- | --------------- | ------- | ------- |-------- | -------- |
|  1e-3      | 	    0.7103     | 20.46   | 55.44   | 0.3213  | 0.3320   |
|  1e-4      | 	    0.7116     | 20.09   | 55.12   | 0.3241  | 0.3348   |  
|  1e-5      | 	    0.7088     | 20.38   | 55.65   | 0.3219  | 0.3314   |

## 3. Visualization of ablation study
![image](https://github.com/anonymity-coder/EviDiff/blob/main/abalation.jpg)

