# Nvidia AI Specialist Certification

# **Ov**erview of the Project

- **Backgrounds of project**
- **General description of the current project**
- **Proposed idea for enhancements to the project**
- **Value and significance of this project**
- **Current limitations**
- **Results**

# **🏋️‍♂️  Project** Title **🏋️‍♂️**

# **Fitness Equipment Identification by Using YoloV5**

---

## **Background information**

---

<aside>
**This project aims to build a system that uses a YOLOv5-based object recognition model to identify fitness accessories in real-time and provide their names, helping customers quickly recognize the correct names and purposes of these items. When customers present various accessories in front of the camera, the system recognizes them and immediately provides the name and purpose of each tool. Through this, customers can learn more about exercise equipment, increase their workout efficiency, and learn the correct ways to use the tools.**

</aside>

# **General description of the current project**

---

<aside>
**Various accessories are used during exercise, but many customers often fail to accurately recognize the names of these accessories. Different tools such as kettlebells, yoga blocks, lacrosse balls, and foam rollers each play important roles in specific exercises. However, people frequently don't know or confuse the exact names of these tools. As a result, customers experience confusion about which tools to use during workouts and how to utilize them. Additionally, not knowing the names often leads to the need for additional searches to find proper information or wasted time in selecting the right tool. To prevent this, we provide real-time recognition of accessories and practical training information.**

</aside>

# **Proposed idea for enhancements to the project**

---

- **Efficient learning: Customers can obtain real-time information about tools without direct searching, increasing the speed of learning**
- **Enhanced user experience: Providing an environment where users can focus on exercising without confusion by instantly recognizing tools used during workouts**
- **Maximizing exercise effectiveness: Ability to use the correct tools accurately, maximizing exercise effects and reducing the risk of injury**
- **Integration of technology and exercise: Providing a smarter exercise experience by offering an environment where users can exercise and learn simultaneously using the latest AI technologyIn fact, places like PT shops provide sufficient competitiveness and convenience as the visual aspect and service provision are important**
    
    (**In fact, places like PT shops offer enough competitiveness and convenience for what they see and what they serve to be important)**
    

- **Strengthening communication between trainers and clients: Trainers can help clients use tools correctly, and through this system, provide better feedback through smooth communication with clients**

# **Value and significance of the project**

---

<aside>
**This project is an AI system that recognizes fitness accessories in real-time and provides their names and usage instructions. Many customers may learn inefficiently or risk injury due to lack of knowledge about the names or proper use of exercise equipment.**

**This system aims to solve this issue by helping customers quickly and accurately recognize tools, maximizing exercise effectiveness and preventing injuries. By utilizing YOLOv5 to recognize tools in real-time, it facilitates smoother communication between trainers and customers, providing a safer and more efficient exercise environment.**

</aside>

# **Current limitations**

---

<aside>
**This system provides real-time recognition of fitness accessories and personalized exercise tracking information, but there are limitations in perfectly personalizing all exercises. Due to the variety in design, color, and size depending on the brand or manufacturer of accessories, there may be cases where even identical tools are difficult to recognize. This presents a realistic challenge in achieving perfect recognition due to the varied forms and color differences of diverse accessories. However, we aim for gradually higher recognition rates through continuous improvements.**

</aside>

# **Literature review**

---

<aside>
**1. A thorough understanding of the technical background of this project is required through prior research on the limitations of cameras in recognizing multiple objects simultaneously and on object detection and tracking technologies using YOLOv5.**

**2. A comprehensive understanding of image recognition, object detection, and classification is necessary, supported by diverse training datasets and AI learning for recognizing various fitness accessories.**

</aside>

# **Image Acquisition Method**:

---

- **Filmed various props at the place where I work**

[https://drive.google.com/file/d/12TG2KZcvgloyKzglvqSZP8Uu5N6jdAa2/view?usp=drive_link](https://drive.google.com/file/d/12TG2KZcvgloyKzglvqSZP8Uu5N6jdAa2/view?usp=drive_link)

**Use this video to extract from DarkLabel through labeling**

# **Video Labeling and Annotation Using DarkLabel**

---

- **Extract the collected images from DarkLabel as images.**

[DarkLabel2.4.zip](https://github.com/user-attachments/files/17842932/DarkLabel2.4.zip)
![v14](https://github.com/user-attachments/assets/72177809-09f2-4666-b82d-d23cdd9b588c)


**(Since Yolov5 is supported by 640 * 640, the original image is set to 640 * 640 using a resolution conversion program.**

![v4](https://github.com/user-attachments/assets/6828c191-6c1b-4a77-acf4-a695b46005e3)

[[https://www.bing.com/ck/a?!&&p=17025025dbeef5d650a67a3b4a49c0218bed35529ef61e6ddbfc38d974981ab8JmltdHM9MTczMTYyODgwMA&ptn=3&ver=2&hsh=4&fclid=29425e80-95ec-62a3-2119-51b5944e63b9&psq=뱁믹스&u=a1aHR0cHM6Ly93d3cudmFwc2hpb24uY29tL3ZhcHNoaW9uMy9kb3dubG9hZC5waHA&ntb=1](https://www.bing.com/ck/a?!&&p=17025025dbeef5d650a67a3b4a49c0218bed35529ef61e6ddbfc38d974981ab8JmltdHM9MTczMTYyODgwMA&ptn=3&ver=2&hsh=4&fclid=29425e80-95ec-62a3-2119-51b5944e63b9&psq=%eb%b1%81%eb%af%b9%ec%8a%a4&u=a1aHR0cHM6Ly93d3cudmFwc2hpb24uY29tL3ZhcHNoaW9uMy9kb3dubG9hZC5waHA&ntb=1)](https://www.bing.com/ck/a?!&&p=17025025dbeef5d650a67a3b4a49c0218bed35529ef61e6ddbfc38d974981ab8JmltdHM9MTczMTYyODgwMA&ptn=3&ver=2&hsh=4&fclid=29425e80-95ec-62a3-2119-51b5944e63b9&psq=%eb%b1%81%eb%af%b9%ec%8a%a4&u=a1aHR0cHM6Ly93d3cudmFwc2hpb24uY29tL3ZhcHNoaW9uMy9kb3dubG9hZC5waHA&ntb=1)

[https://www.bing.com/ck/a?!&&p=17025025dbeef5d650a67a3b4a49c0218bed35529ef61e6ddbfc38d974981ab8JmltdHM9MTczMTYyODgwMA&ptn=3&ver=2&hsh=4&fclid=29425e80-95ec-62a3-2119-51b5944e63b9&psq=뱁믹스&u=a1aHR0cHM6Ly93d3cudmFwc2hpb24uY29tL3ZhcHNoaW9uMy9kb3dubG9hZC5waHA&ntb=1](https://www.bing.com/ck/a?!&&p=17025025dbeef5d650a67a3b4a49c0218bed35529ef61e6ddbfc38d974981ab8JmltdHM9MTczMTYyODgwMA&ptn=3&ver=2&hsh=4&fclid=29425e80-95ec-62a3-2119-51b5944e63b9&psq=%eb%b1%81%eb%af%b9%ec%8a%a4&u=a1aHR0cHM6Ly93d3cudmFwc2hpb24uY29tL3ZhcHNoaW9uMy9kb3dubG9hZC5waHA&ntb=1)

**Open the darklabel.yaml file in a development environment such as text format or VScode in classes_set, the names of the objects to be labeled, that is, classes, are written in the form of a list.**

```python
classes_set: "my_classes1"   # predefined classes set (tag name of classes set)
```

```python
my_classes1:  [ "YogaBlock", "Kettlebell","MedBall","FoamRoller","LacrosseBall", "AquaBall"]
```

![v6](https://github.com/user-attachments/assets/b0c429e3-07be-476b-973a-d3f7c1805a01)

**In order to see the classes set in the DarkLabel GUI when announcing by entering the code as follows in VS Studio, class_set adds a preset 'my_classes1' and sets the name to be viewed in the GUI to 'fitness_accessories’**

![v12](https://github.com/user-attachments/assets/1d4d7445-32bf-4e18-a04b-a0016229afd9)

```python
format1:    # darknet yolo (predefined format]
  fixed_filetype: 1                 # if specified as true, save setting isn't changeable in GUI
  data_fmt: [classid, ncx, ncy, nw, nh]
  gt_file_ext: "txt"                 # if not specified, default setting is used
  gt_merged: 0                    # if not specified, default setting is used
  delimiter: " "                     # if not spedified, default delimiter(',') is used
  classes_set: "my_classes1"     # if not specified, default setting is used
  name: "fitness_accessories"           # if not specified, "[fmt%d] $data_fmt" is used as default format name

```
![v10](https://github.com/user-attachments/assets/0b0dfc92-70ca-47d3-a4ed-c02ae481ce28)

![v9](https://github.com/user-attachments/assets/3556e128-3b83-42b6-a2a6-e43d8737b0b2)

**You can check on the GUI that the names to label objects are the same as the class names I set**

****

**Press Open Video to sing the original image to label**

# **How to Extract a Video into Images and .txt Files**

---

**Open the video and select the file to extract.**
![v1](https://github.com/user-attachments/assets/8f24b988-e62e-4acb-9404-49c37d3e14e5)


**Make sure you open the video and create a folder to store the image you want to extract and create more images folders in the folder you created to distinguish it from the notated .txt file**

**Check the box + label and label it according to the name of each accessory
When labeling, Box + Label is selected to distinguish the screen during labeling.

After all labeling, press the as images button in the pre-saved folder images folder to save it in the form of an image.**

![v3](https://github.com/user-attachments/assets/50175d39-501e-4da5-a169-207b31a87108)

**After you complete the save in image format, press the save as GT button to save it distinct from the images folder. This distinction is much more convenient when you put it in the colab later.**

![v2](https://github.com/user-attachments/assets/981e464a-27e9-4aeb-a300-86cef214ce42)

# Learning Yolov5 with Colab

---

### **1.** Connect to Colab and connect to Google Drive to create subfolders

```python
# prompt: 구글 드라이브랑 연결

from google.colab import drive
drive.flush_and_unmount()  # 기존 마운트 해제
drive.mount('/content/drive')  # 다시 마운트
```

```python
%cd /content/drive/MyDri
```

```python
# prompt: 구글 드라이브랑 연결

from google.colab import drive
drive.flush_and_unmount()  # 기존 마운트 해제
drive.mount('/content/drive')  # 다시 마운트
```

![v5](https://github.com/user-attachments/assets/444977e5-4990-46b5-a187-1b0dec2f6963)

---

### **2. Download YOLOv5**

```python
##
#clone YOLOv5 and
!git clone https://github.com/ultralytics/yolov5  # clone repo
%cd yolov5
%pip install -qr requirements.txt # install dependencies
```

```python
!pip install Pillow==10.3
```

**YOLOv5 downloads pip, a tool that makes it easy to install and manage Python packages, and Pillow Library, which is responsible for image processing.**

![v13](https://github.com/user-attachments/assets/829fb87b-00e5-45f6-a7e9-81775dd1f201)

---

### **3.** Create a management folder for image files

```python
!mkdir -p Train/labels
!mkdir -p Train/images
!mkdir -p Val/labels
!mkdir -p Val/images
%pw
```

```python
##검증 데이터 만들기
import os
import shutil
from sklearn.model_selection import %pwdtrain_test_split

def create_validation_set(train_path, val_path, split_ratio=0.3):
    """
    Train 데이터의 일부를 Val로 이동
    """
    # 필요한 디렉토리 생성
    os.makedirs(os.path.join(val_path, 'images'), exist_ok=True)
    os.makedirs(os.path.join(val_path, 'labels'), exist_ok=True)

    # Train 이미지 리스트 가져오기
    train_images = os.listdir(os.path.join(train_path, 'images'))
    train_images = [f for f in train_images if f.endswith(('.jpg', '.jpeg', '.png'))]

    # Train/Val 분할
    _, val_images = train_test_split(train_images,
                                   test_size=split_ratio,
                                   random_state=42)

    # Val로 파일 복사
    for image_file in val_images:
        # 이미지 복사
        src_image = os.path.join(train_path, 'images', image_file)
        dst_image = os.path.join(val_path, 'images', image_file)
        shutil.copy2(src_image, dst_image)

        # 라벨 파일 복사
        label_file = os.path.splitext(image_file)[0] + '.txt'
        src_label = os.path.join(train_path, 'labels', label_file)
        dst_label = os.path.join(val_path, 'labels', label_file)
        if os.path.exists(src_label):
            shutil.copy2(src_label, dst_label)

    print(f"Created validation set with {len(val_images)} images")

# 실행
train_path = '/content/drive/MyDrive/yolov5/Train'
val_path = '/content/drive/MyDrive/yolov5/Val'

create_validation_set(train_path, val_path)
```

**The validation dataset is composed by extracting images from the training data at a specified rate, separating and copying them into validation data, and copying the label file along with the image to the corresponding path. The functions of the code are as follows.**

- **Evaluation of the performance of the model**
    - **Validation data is data that the model has not learned, and is needed to evaluate the generalization performance of the model (how well it works on new data**
- **Data bias prevention**
    - **Using only the training data is likely to overfit the model to the data.**
    - **You can check the model to have balanced performance for various data**
- **Hyperparameter tuning**
    - **When adjusting hyperparameters such as learning rate, number of epochs, and model structure during learning, refer to the results of validation data and optimize the hyperparameters in the direction of increasing validation performance.**
    

**Isolation of validation data is an essential process for performance evaluation and improvement of the model.**

```python
def check_dataset():
    train_path = '/content/drive/MyDrive/yolov5/Train'
    val_path = '/content/drive/MyDrive/yolov5/Val'

    # Train 데이터 확인
    train_images = len(os.listdir(os.path.join(train_path, 'images')))
    train_labels = len(os.listdir(os.path.join(train_path, 'labels')))

    # Val 데이터 확인
    val_images = len(os.listdir(os.path.join(val_path, 'images')))
    val_labels = len(os.listdir(os.path.join(val_path, 'labels')))

    print("Dataset status:")
    print(f"Train - Images: {train_images}, Labels: {train_labels}")
    print(f"Val - Images: {val_images}, Labels: {val_labels}")

# 데이터셋 상태 확인
check_dataset()
```

![v7](https://github.com/user-attachments/assets/9d81273f-6017-4dae-a7f4-084e55c05ddb)

If the size of the dataset differs to the extent that there is no significant difference between a few tens and a few hundred chapters as follows, there is no big problem in learning afterwards. The accuracy will be slightly lowered, but it does not significantly affect the current number of original images.

---

### **4. Start learning**

```python
import torch
import os
from IPython.display import Image, clear_output  # to display images
```

```python
%pwd
```

**import os :  OS for interacting with the operating system**

**import torch** : **It is used to build and train deep learning models
                        Pytorch library used for deep learning model training, inference, and tensor                
                        operations**

```python
import numpy as np
import tensorflow as tf
import os
from PIL import Image
from tensorflow.python.eager.context import eager_mode

def _preproc(image, output_height=512, output_width=512, resize_side=512):
    ''' imagenet-standard: aspect-preserving resize to 256px smaller-side, then central-crop to 224px'''
    with eager_mode():
        h, w = image.shape[0], image.shape[1]
        scale = tf.cond(tf.less(h, w), lambda: resize_side / h, lambda: resize_side / w)
        resized_image = tf.compat.v1.image.resize_bilinear(tf.expand_dims(image, 0), [int(h*scale), int(w*scale)])
        cropped_image = tf.compat.v1.image.resize_with_crop_or_pad(resized_image, output_height, output_width)
        return tf.squeeze(cropped_image)

def Create_npy(imagespath, imgsize, ext) :
    images_list = [img_name for img_name in os.listdir(imagespath) if
                os.path.splitext(img_name)[1].lower() == '.'+ext.lower()]
    calib_dataset = np.zeros((len(images_list), imgsize, imgsize, 3), dtype=np.float32)

    for idx, img_name in enumerate(sorted(images_list)):
        img_path = os.path.join(imagespath, img_name)
        try:
            # 파일 크기가 정상적인지 확인
            if os.path.getsize(img_path) == 0:
                print(f"Error: {img_path} is empty.")
                continue

            img = Image.open(img_path)
            img = img.convert("RGB")  # RGBA 이미지 등 다른 형식이 있을 경우 강제로 RGB로 변환
            img_np = np.array(img)

            img_preproc = _preproc(img_np, imgsize, imgsize, imgsize)
            calib_dataset[idx,:,:,:] = img_preproc.numpy().astype(np.uint8)
            print(f"Processed image {img_path}")

        except Exception as e:
            print(f"Error processing image {img_path}: {e}")

    np.save('calib_set.npy', calib_dataset)
```

****

**This code reads the image of the specified folder, contains the ratio maintenance resize and Pretreatment with center crop/padding and save in a Numpy array. The preprocessed data is stored as a .npy file and used as model training or calibration data**.

```python
#모델 학습하기
!python  /content/drive/MyDrive/yolov5/train.py  --img 640 --batch 16 --epochs 300 --data /content/drive/MyDrive/yolov5/data.yaml --weights yolov5n.pt --cache --patience 0  

```

**Run `train.py` to execute YOLOv5. It includes various options, as follows:**

- **`--img 640`:**
    
    **Set the size of the input image to 640x640.**
    
- **`--batch 16`:**
    
    **Set the batch size. Indicates the number of images processed at a time**
    
- **`--epochs 300`:**
    
    **Sets the total number of epochs to learn**
    
- **`--data /content/drive/MyDrive/yolov5/data.yaml`**
    
    **: Specify the path to the YAML file containing settings for the dataset and model configurations.**
    
- **`--weights yolov5n.pt`:**
    
     **Specify the path to pre-trained weight files.  `yolov5n.pt` files are being used here.**
    
- **`--patience 0` :**
    
    **It prevents learning from stopping in the middle. Set to 10, if the epoch remains unchanged for 10 years, it stops.**
    
    ---
    
  ![v11](https://github.com/user-attachments/assets/3d255e2a-a9f5-4a53-bc3d-cdabb7006248)
    
    **학습이 완료되면 yolov5/runs/train/exp10 의 경로에 결과가 저장되었다는 문구를 볼 수 있다.**
    
    ---
    
    ### **5.  yolov5모델 학습 결과 검증**
    
    ```python
    %load_ext tensorboard
    %tensorboard --logdir /content/drive/MyDrive/yolov5/runs/train/exp10
    ```
    
    **위의 코드를 이용하여 --logdir /content/drive/MyDrive/yolov5/runs/train/exp10와 같이 학습한 경로를라벨리 지정하고 텐서보드를 이용하여 시각화 할 수 있다.**
    

![v8](https://github.com/user-attachments/assets/6acb3860-2d73-4bab-b3db-61630dbd5eee)

**The code for re-learning and verifying that the object labeled based on the learned materials appears in other images or images is as follows.**

```python
!python /content/drive/MyDrive/yolov5/detect.py --weights /content/drive/MyDrive/yolov5/runs/train/exp4/weights/best.pt --img 640 --conf 0.1 --source /content/drive/MyDrive/yolov5/Train/images
```

```python
!python /content/drive/MyDrive/yolov5/detect.py --weights /content/drive/MyDrive/yolov5/runs/train/exp5/weights/best.pt --img 640 --conf 0.1 --source /content/drive/MyDrive/yolov5/Train/라있.mp4
```

# **The results of learning**

![F1_curve](https://github.com/user-attachments/assets/61dd6aea-790d-4ebb-b616-cd2cf51d2d7a)

![labels](https://github.com/user-attachments/assets/1ff564a4-557c-4596-9dd4-5bbeba0f725f)

![labels_correlogram](https://github.com/user-attachments/assets/06cc2f25-ab6c-459f-a4b5-024a0207293a)

![P_curve](https://github.com/user-attachments/assets/36553112-ca39-49cc-8125-d2d422d86d42)

![PR_curve](https://github.com/user-attachments/assets/0edfdccf-1b08-443e-b22e-287a7134ce3f)


![R_curve](https://github.com/user-attachments/assets/3587b8ff-77bc-4b9a-b04e-8ca41bb4d30a)

![confusion_matrix](https://github.com/user-attachments/assets/1ec8b51f-7de7-4ba0-93da-6d6421a8ab50)
![results](https://github.com/user-attachments/assets/2eb2a489-4c07-4fc2-81a9-39c64643a24e)

![val_batch0_labels](https://github.com/user-attachments/assets/47dceb21-d28d-408a-97b1-d817e82afc0b)

![val_batch2_labels](https://github.com/user-attachments/assets/58e5a8d3-0235-465a-85c4-09c8818a2095)
![val_batch2_pred](https://github.com/user-attachments/assets/c05b3e3f-d016-41f7-9530-b2083b1b920e)

![image](https://github.com/user-attachments/assets/7ef9dbda-6551-4852-8f67-5d2e2cf31493)

# **Learning Results Video**

[https://youtu.be/yWuiWQbhLDA?si=vcco28nqa3DvEiR3](https://youtu.be/yWuiWQbhLDA?si=vcco28nqa3DvEiR3)

---

[https://youtube.com/shorts/7mulq1dcq00?si=3GKYVtTEMI6OMfBT](https://youtube.com/shorts/7mulq1dcq00?si=3GKYVtTEMI6OMfBT)

---

[https://youtu.be/xB4_d9nBZXw?si=Lv8a9Qi-PQ2SNWN4](https://youtu.be/xB4_d9nBZXw?si=Lv8a9Qi-PQ2SNWN4)

---

[https://youtube.com/shorts/riOYFq0lBrA?si=aCtcZegWiGhgOptZ](https://youtube.com/shorts/riOYFq0lBrA?si=aCtcZegWiGhgOptZ)

---

[https://youtu.be/31t7jyiUw3I?si=IIRwK7cRcrfU0K1E](https://youtu.be/31t7jyiUw3I?si=IIRwK7cRcrfU0K1E)

---

[https://youtu.be/50bJGmlF54Q?si=KXy3Aq4l-5f_SBgm](https://youtu.be/50bJGmlF54Q?si=KXy3Aq4l-5f_SBgm)

[https://drive.google.com/drive/folders/1eQhV7VjYvbUjdPRBkt-Feh6n9A50mIaH?usp=drive_link](https://drive.google.com/drive/folders/1eQhV7VjYvbUjdPRBkt-Feh6n9A50mIaH?usp=drive_link)
