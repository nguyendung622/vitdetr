# Training
- Bộ dữ liệu: PASCAL VOC 2012
- Nếu có sử dụng CUDA
    python main.py --dataset_file pascal --data_path ../dataset/pascal --output_dir output
- Nếu không sử dụng CUDA
    python main.py --dataset_file pascal --data_path ../dataset/pascal --output_dir output --device cpu