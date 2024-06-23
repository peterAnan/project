The dataset has been uploaded to Baidu Cloud. You can download it using this link: https://pan.baidu.com/s/1SzgliOLouJQJCDQ1oiU3Kw?pwd=8tr3, with the extraction code: 8tr3. The dataset includes a category mapping list, which can be configured by modifying the coco128.yaml file in the docer/data folder.

After installing the GPU version of PyTorch, you can start training by entering the following command in the docker folder:

bash
python train.py
You can also directly predict using the data by running:

bash
python detect.py
to make predictions on the data.
