# img_GridPuzzle_score
### 使用边缘差异化算法，识别3x3九宫格拼图或者4x4十六宫格拼图
通过图像识别的方式，从多张乱序的拼图中找到拼图顺序正确的图片。


- img_puzzle_nums定义图片分割宫格数 [3,3] 表示 3x3九宫格; [4,4]表示4x4十六宫格
```python
img_puzzle_nums = [4,4]
```
- 识别的图片放在同级的temp文件夹目录下，correct_image为返回差异化最小图片的标题序号

- 调用方法
```python
# 指定图片文件夹路径
folder_path = './temp'
correct_image = process_images_in_folder(folder_path)
print(f"The correct image is {correct_image}")

```
- [author by lingdanqing](https://github.com/lingdanqing)
