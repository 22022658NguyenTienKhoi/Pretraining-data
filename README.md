# Pretraining dataset
Data sources come from the following categories:  
1. Web crawler dataset:  
- Website UET (ĐH Công nghệ): tuyensinh.uet.vnu.edu.vn; new.uet.vnu.edu.vn
- Website HUS (ĐH KHTN): hus.vnu.edu.vn
- Website EUB (ĐH Kinh tế): ueb.vnu.edu.vn
- Website IS (ĐH Quốc tế): is.vnu.edu.vn
- Website Eduacation (ĐH Giáo dục): education.vnu.edu.vn
- Website NXB ĐHQG: press.vnu.edu.vn   
[List domain web crawler](https://docs.google.com/spreadsheets/d/1zbkltkSPRm6f48Lb1Jo3Njq1-LrSd8H6/edit?gid=409337688#gid=409337688)  
2. CC100:  
[link to CC100 vi](https://huggingface.co/datasets/statmt/cc100)  
3. C4_vi:  
  [link to C4_vi](https://huggingface.co/datasets/allenai/c4)
# Tokenizer  
We use tokenizer from [meta-llama/Llama-3.1-8B](https://huggingface.co/meta-llama/Llama-3.1-8B)  
# Filtering models  
[quality classification model](https://huggingface.co/zerostratos/quality_classification)  
[domain classification model](https://huggingface.co/nvidia/multilingual-domain-classifier)  
[toxic detection model](https://huggingface.co/zerostratos/lstm)  

