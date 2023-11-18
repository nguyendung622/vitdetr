# Training
## Bộ dữ liệu: PASCAL VOC 2012
- Nếu có sử dụng CUDA:
```python
    python main.py --dataset_file pascal --data_path ../dataset/pascal --output_dir output
```
- Nếu không sử dụng CUDA:
```python  
    python main.py --dataset_file pascal --data_path ../dataset/pascal --output_dir output --device cpu
```
## Bộ dữ liệu COCO 2017
- Nếu có sử dụng CUDA:
```python
    python main.py --dataset_file coco --data_path ../dataset/coco --output_dir output
```
- Nếu không sử dụng CUDA:
```python  
    python main.py --dataset_file coco --data_path ../dataset/coco --output_dir output --device cpu
```