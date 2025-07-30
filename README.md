# EviDiff
EviDiff: Efficient Multi-Object Composition with Evidential Supervision

The trained EviDiff models are available at https://huggingface.co/EviDiff

# Rebuttal
## 1. Additional qualitative examples
![image](https://github.com/anonymity-coder/EviDiff/blob/main/additional-results.png)

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


