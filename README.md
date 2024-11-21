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

[DarkLabel2.4.zip](https://github.com/user-attachments/files/17842272/DarkLabel2.4.zip)
https://private-user-images.githubusercontent.com/188140080/388418371-c2e135b3-a945-4ee1-bd90-e683b06f6358.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzcxLWMyZTEzNWIzLWE5NDUtNGVlMS1iZDkwLWU2ODNiMDZmNjM1OC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jZTBiYzE2OGJhMjU3OWIyNmRmOGZjOTk3MzRjZTNiZTkyYTZkNmQyZTM4MjQ5OGFiYTU3ZDcwMmUwMDhlMWE2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.jioeNKSVPFDhkbNiAIfEVhQr0z-OjBRjlzgCWbC3xxs


**(Since Yolov5 is supported by 640 * 640, the original image is set to 640 * 640 using a resolution conversion program.**

https://private-user-images.githubusercontent.com/188140080/388418431-b8323972-845d-46f8-aede-66c80c2de5c2.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4NDMxLWI4MzIzOTcyLTg0NWQtNDZmOC1hZWRlLTY2YzgwYzJkZTVjMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kNGVjZGVhMzQ5YWE0MDIwZTI3MzRmZmQyODU3OGUxNGU2ZDBjNjYyYjZiMmNmM2M4MzIxYjNkYjFmOWFhMjMxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.Hl8V_olF1MU_QRJRZxHqDoEqFfqCbUU1MZHIg_e3_K0

[[https://www.bing.com/ck/a?!&&p=17025025dbeef5d650a67a3b4a49c0218bed35529ef61e6ddbfc38d974981ab8JmltdHM9MTczMTYyODgwMA&ptn=3&ver=2&hsh=4&fclid=29425e80-95ec-62a3-2119-51b5944e63b9&psq=뱁믹스&u=a1aHR0cHM6Ly93d3cudmFwc2hpb24uY29tL3ZhcHNoaW9uMy9kb3dubG9hZC5waHA&ntb=1](https://www.bing.com/ck/a?!&&p=17025025dbeef5d650a67a3b4a49c0218bed35529ef61e6ddbfc38d974981ab8JmltdHM9MTczMTYyODgwMA&ptn=3&ver=2&hsh=4&fclid=29425e80-95ec-62a3-2119-51b5944e63b9&psq=%eb%b1%81%eb%af%b9%ec%8a%a4&u=a1aHR0cHM6Ly93d3cudmFwc2hpb24uY29tL3ZhcHNoaW9uMy9kb3dubG9hZC5waHA&ntb=1)](https://www.bing.com/ck/a?!&&p=17025025dbeef5d650a67a3b4a49c0218bed35529ef61e6ddbfc38d974981ab8JmltdHM9MTczMTYyODgwMA&ptn=3&ver=2&hsh=4&fclid=29425e80-95ec-62a3-2119-51b5944e63b9&psq=%eb%b1%81%eb%af%b9%ec%8a%a4&u=a1aHR0cHM6Ly93d3cudmFwc2hpb24uY29tL3ZhcHNoaW9uMy9kb3dubG9hZC5waHA&ntb=1)

[https://www.bing.com/ck/a?!&&p=17025025dbeef5d650a67a3b4a49c0218bed35529ef61e6ddbfc38d974981ab8JmltdHM9MTczMTYyODgwMA&ptn=3&ver=2&hsh=4&fclid=29425e80-95ec-62a3-2119-51b5944e63b9&psq=뱁믹스&u=a1aHR0cHM6Ly93d3cudmFwc2hpb24uY29tL3ZhcHNoaW9uMy9kb3dubG9hZC5waHA&ntb=1](https://www.bing.com/ck/a?!&&p=17025025dbeef5d650a67a3b4a49c0218bed35529ef61e6ddbfc38d974981ab8JmltdHM9MTczMTYyODgwMA&ptn=3&ver=2&hsh=4&fclid=29425e80-95ec-62a3-2119-51b5944e63b9&psq=%eb%b1%81%eb%af%b9%ec%8a%a4&u=a1aHR0cHM6Ly93d3cudmFwc2hpb24uY29tL3ZhcHNoaW9uMy9kb3dubG9hZC5waHA&ntb=1)

**Open the darklabel.yaml file in a development environment such as text format or VScode in classes_set, the names of the objects to be labeled, that is, classes, are written in the form of a list.**

```python
classes_set: "my_classes1"   # predefined classes set (tag name of classes set)
```

```python
my_classes1:  [ "YogaBlock", "Kettlebell","MedBall","FoamRoller","LacrosseBall", "AquaBall"]
```

https://private-user-images.githubusercontent.com/188140080/388418477-22365e14-41d7-48c4-9e41-b035accb7e21.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4NDc3LTIyMzY1ZTE0LTQxZDctNDhjNC05ZTQxLWIwMzVhY2NiN2UyMS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT04MWJkYmZmMzU0ZGMwNzZlNTdhZWU3YmUwNTE3MzY2Y2QwZTZkMDRmMzZiZDZkNzhlYWMyMDdlNWFhYjNlZjg3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.LSQz1J4zr0W_nuMxgkbGm_he-N0OSnueXhVVo8hm-Dk

**In order to see the classes set in the DarkLabel GUI when announcing by entering the code as follows in VS Studio, class_set adds a preset 'my_classes1' and sets the name to be viewed in the GUI to 'fitness_accessories’**
https://private-user-images.githubusercontent.com/188140080/388418133-bd56bb58-be07-4d30-a02a-688a73bdea9b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MTMzLWJkNTZiYjU4LWJlMDctNGQzMC1hMDJhLTY4OGE3M2JkZWE5Yi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lZmNkOGNiNTkzMDNiMGVhZGViNjUyZGY2Y2IyZDg2ZGFhOGQ2ZDQ4ZjIzZDMyYTFiNDA3MWEzOGEwZDU5ZjVjJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.qbhZxbmyKN7CcRDZAQ51N_um5RIi0ZMbdht2vXaqux0

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
https://private-user-images.githubusercontent.com/188140080/388418120-3245e062-256d-40e5-ad86-288a91d99712.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MTIwLTMyNDVlMDYyLTI1NmQtNDBlNS1hZDg2LTI4OGE5MWQ5OTcxMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hODU5ZGM0OTZhYjMxOWJlNmYzODk4YWFjY2IyMTAyNmMzZTg3OGE2YjIzNmE3ZTZiODFmOGQ3NWU3MDRmZjIxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.D8X1bn_kt1MgDiROZyGzl4l7sXHrIw4zPlkaL4T2VIo

https://private-user-images.githubusercontent.com/188140080/388418116-8901856d-3ea5-4396-a9e9-2b82f6a9dc77.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MTE2LTg5MDE4NTZkLTNlYTUtNDM5Ni1hOWU5LTJiODJmNmE5ZGM3Ny5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jM2U3MjYxMWQ5NmY5MzdiYWI4OTlkNTI2YzhhODRlYTUyYzdhYmZlMGQ2OTVhZmVmNTRlMDJjZGQwYjIwNDhhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.jQoTZycIJdZLj4OIhmkcAiER7YXDyLvFJC5wssuvBdc

**You can check on the GUI that the names to label objects are the same as the class names I set**

****

**Press Open Video to sing the original image to label**

# **How to Extract a Video into Images and .txt Files**

---

**Open the video and select the file to extract.**

https://private-user-images.githubusercontent.com/188140080/388418392-97705665-2cdd-497e-a94a-883d56f62df2.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzkyLTk3NzA1NjY1LTJjZGQtNDk3ZS1hOTRhLTg4M2Q1NmY2MmRmMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kNTliNWJiMTM4MDI4MzkzN2YzNGJhYmEwMTcwMDg5MDAyZTIyODk0ZDNjMGM4NDA5Nzg2MTE2OWMzYjRkZmI2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.Kx42fTfFNSu8Wu7iYj-F4o76UMGb-CREXlWzZoDvhp8

**Make sure you open the video and create a folder to store the image you want to extract and create more images folders in the folder you created to distinguish it from the notated .txt file**

**Check the box + label and label it according to the name of each accessory
When labeling, Box + Label is selected to distinguish the screen during labeling.

After all labeling, press the as images button in the pre-saved folder images folder to save it in the form of an image.**

https://private-user-images.githubusercontent.com/188140080/388418417-97038587-fe48-43b2-b20d-b2e72e33e0d1.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4NDE3LTk3MDM4NTg3LWZlNDgtNDNiMi1iMjBkLWIyZTcyZTMzZTBkMS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03MzAwZGY0YTYxYTg0ZGUwNjA2MjA3ZmZlZDYyNDlmYThlMzY0YzMzMDY0OTMwNmMzNjQ0NzNhZWE2NjU5YzgyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9._xyEYEp4GunrYtIQMGwKByJ9nQE82hAEZiiR-a6Q7eM

**After you complete the save in image format, press the save as GT button to save it distinct from the images folder. This distinction is much more convenient when you put it in the colab later.**

https://private-user-images.githubusercontent.com/188140080/388418406-cbcfef8d-6299-47fa-9054-5af3e6eaa20e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4NDA2LWNiY2ZlZjhkLTYyOTktNDdmYS05MDU0LTVhZjNlNmVhYTIwZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03YjcyNWQ5ZWFiZDI4MTc3YTk5YjhiZjc5ZGI1MWQzNzliNGQxYmFjMjc3OTMyMGE1YWZjMWIyNzM0MjZkZjViJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.m_29F7-gf5XOOxwcI8iANK2Iw0OosZFphkA0RNTltmM

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

https://private-user-images.githubusercontent.com/188140080/388418454-b8408832-0252-4384-bc44-ad8a77d0394d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4NDU0LWI4NDA4ODMyLTAyNTItNDM4NC1iYzQ0LWFkOGE3N2QwMzk0ZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03ZmFjMWZlYzBmMmIxMWM4OTExNjk1OTYxNTQ0NWNlZTFmMDJiMGI1NmM1M2E2N2RkMTgyYjczMDk5MDQ5ZjVmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.pWUUgG1rX9P3sB852ZsuPinQkpbmy-agNpkwqv6HA0U

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

https://private-user-images.githubusercontent.com/188140080/388418301-3ff10721-762d-4404-b7fc-6e6b7b287667.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzAxLTNmZjEwNzIxLTc2MmQtNDQwNC1iN2ZjLTZlNmI3YjI4NzY2Ny5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01ZjcyNGNiNTMyNDQyMWRkMzdkOTlkYTA4NzNiNWM4Nzc1YjNiYzRmNjZjNmIwMTU2ZGYyMGJkZjUzMWFjMzkxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.Jh6QuNfYJuTzTd_0RTgMLc-LLvVc9Ea5tzo7xeq2Dm8

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

https://private-user-images.githubusercontent.com/188140080/388418101-3f4a32bb-df43-40f0-8f9a-694dfcfc278b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MTAxLTNmNGEzMmJiLWRmNDMtNDBmMC04ZjlhLTY5NGRmY2ZjMjc4Yi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jYTg5MmI5ODY2MzFiZGFlYzZlODk3Mzc0OWJlOWI3MjU5ZDc4Y2VkMWQ1YzM5NGZhMjZlMzZmZjc3NzJmNzIzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.biTBBxnqez3Gw-Y2vBILjrNgwn8qBSNEuRLlPNm8B5Q

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
    
  https://private-user-images.githubusercontent.com/188140080/388418131-d8060b74-b3dd-49ca-8b2c-0157bfea2893.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MTMxLWQ4MDYwYjc0LWIzZGQtNDljYS04YjJjLTAxNTdiZmVhMjg5My5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT02MjE2ODA1MGI4MWRjZWE4YWU2MGRkOTI3MDE3ZTE4ZWEzNzkyOGIxYjExOTI4OWFiMDFhMTljOGMyM2NiN2M2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.db-t74_qkIXbG5b3QbRpiK64VTjOp_Rk8kBd3DQmiLM
    
    **학습이 완료되면 yolov5/runs/train/exp10 의 경로에 결과가 저장되었다는 문구를 볼 수 있다.**
    
    ---
    
    ### **5.  yolov5모델 학습 결과 검증**
    
    ```python
    %load_ext tensorboard
    %tensorboard --logdir /content/drive/MyDrive/yolov5/runs/train/exp10
    ```
    
    **위의 코드를 이용하여 --logdir /content/drive/MyDrive/yolov5/runs/train/exp10와 같이 학습한 경로를라벨리 지정하고 텐서보드를 이용하여 시각화 할 수 있다.**
    

https://private-user-images.githubusercontent.com/188140080/388418112-6b40205f-18a1-4a31-8f89-2ef562585d63.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MTEyLTZiNDAyMDVmLTE4YTEtNGEzMS04Zjg5LTJlZjU2MjU4NWQ2My5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kYjBlNzY4MmM1ODM4NzFmNGIyZGI2ZmZlMGQwNDY1OTY2ZTIzZTUxMmNiMmZkN2QxYzg1ZTk5ODFjYjlmYzE2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.NxhBVuIj5wM78SBYsvT7syMFWOplBJ8QsVh2fowktUY

**The code for re-learning and verifying that the object labeled based on the learned materials appears in other images or images is as follows.**

```python
!python /content/drive/MyDrive/yolov5/detect.py --weights /content/drive/MyDrive/yolov5/runs/train/exp4/weights/best.pt --img 640 --conf 0.1 --source /content/drive/MyDrive/yolov5/Train/images
```

```python
!python /content/drive/MyDrive/yolov5/detect.py --weights /content/drive/MyDrive/yolov5/runs/train/exp5/weights/best.pt --img 640 --conf 0.1 --source /content/drive/MyDrive/yolov5/Train/라있.mp4
```

# **The results of learning**

https://private-user-images.githubusercontent.com/188140080/388418310-4fc685b1-8f04-47e9-a85e-87f78540998e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzEwLTRmYzY4NWIxLThmMDQtNDdlOS1hODVlLTg3Zjc4NTQwOTk4ZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mMTFmOWRkM2FlMzI2ODEzZGRiMzIzZDM2NzU2NWVlMDE0MWMyN2Q5YjNkY2EyMzQ4M2MwYTVmOTFjYWYyMjJiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.49rbwgNqzjczeh7Df9LX9JymZ3blBQ2Xoja8DBF4nrI

https://private-user-images.githubusercontent.com/188140080/388418341-33d4d25c-7fa5-42c7-b548-a7c1552d8333.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzQxLTMzZDRkMjVjLTdmYTUtNDJjNy1iNTQ4LWE3YzE1NTJkODMzMy5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lYTAyYzVkNDEyNTdhYTFmN2I3YjY1ZWQ2Y2M0ZWI2ZmRjM2I2ZjJmMzgyZjU3NjE3MzcwYzIxODJiNjA5YWM2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.KiHPUdFWrLePmOUBMi4yzPG6Dmll5M7KmwxSqakbNhU

https://private-user-images.githubusercontent.com/188140080/388418340-cbdd9769-c2ad-46fb-86fc-57b4ccd9dcb1.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzQwLWNiZGQ5NzY5LWMyYWQtNDZmYi04NmZjLTU3YjRjY2Q5ZGNiMS5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT02NGJhZjE3Y2Q1MzRiNDY3ZGYzOWJkMDU3MWVlYmI2ZDg5N2EyMDcxMmFmMDJjOGY2Y2RjYjUyNTJiZmZlNTBlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.f4ulhCMotjEpkpShBBPntN9gHWaYxsYpTsgAjRxh91M

https://private-user-images.githubusercontent.com/188140080/388418352-4fb6050b-a610-467c-bad6-2c33c274f04a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzUyLTRmYjYwNTBiLWE2MTAtNDY3Yy1iYWQ2LTJjMzNjMjc0ZjA0YS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hMzQ1N2NlN2E5ZGZmMmFkOGI0ZGFhZWYyMWFlNDUxNWYwOWMwYTgxNTM0OGJhM2EzMDAyMmNjOTZmMzU2NTYwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.Y_WqM6unA5qbyG1ok7CnydJGq3gq4UsaZ-AM4xv1gHA

https://private-user-images.githubusercontent.com/188140080/388418346-bdfc2ca3-ea68-4d83-8e77-7164d06b1a50.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzQ2LWJkZmMyY2EzLWVhNjgtNGQ4My04ZTc3LTcxNjRkMDZiMWE1MC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00YTM1ZmM2MmYyYmIyOTJhY2M1OGI0MWMxYzBkYTdmNmYxNzVjNmE3YmQ0Y2E5ZmIyNDAyZDhlMDZmYjI0YzAwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.Zh-WbjKtp1uKXaPrgz8RkeQsxNF6W0TckHb_KKaQ8yQ

https://private-user-images.githubusercontent.com/188140080/388418358-528addbc-0f84-4a0a-96e9-29b0f58018b0.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzU4LTUyOGFkZGJjLTBmODQtNGEwYS05NmU5LTI5YjBmNTgwMThiMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lYjhkYzAxNmIxMjVmNmZhYmZkMTllYWRlZTM0ZGNkMzYxN2NhMjA0YmM3ZmU0ZmVkNzczZDhhZTNkYjM1ZDI2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.h5Cf6E1vpOPKgvHdMXCaKpNwPPuGKv3Gf0QeUEOZONU

https://private-user-images.githubusercontent.com/188140080/388418136-24b1ed84-723b-4c73-b76b-d8b6b268a7df.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MTM2LTI0YjFlZDg0LTcyM2ItNGM3My1iNzZiLWQ4YjZiMjY4YTdkZi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01ZmIxOGE1ZWYyOTNkYmQ1ZDkyZmU1YTZlZmVmMzE3MzhhZjc4M2EyZmE5NDZmMGI1MmYxYzUzOTBjYTI0NjQ5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.u13k1G0fPvzb0jadT3i8TuzPZk7amgypKkwQe8VP02c

https://private-user-images.githubusercontent.com/188140080/388418366-9372365f-5767-48f6-a485-5e81aa0bd80e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzY2LTkzNzIzNjVmLTU3NjctNDhmNi1hNDg1LTVlODFhYTBiZDgwZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00ZWE4N2Y0MDQxOTRhMzM1YWI4ZWNlOGU1NTg0YWNlYzViZmE1MzVhZmNiYzYwMWJhZTM4MzM0MDljMzFjODllJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.LHh9Wci3Aob4qp8nwwWUFvc4cuWyeDXFWvcdcZyj8tI

https://private-user-images.githubusercontent.com/188140080/388418374-e352ef1c-0cee-43df-a227-ff075882f160.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4Mzc0LWUzNTJlZjFjLTBjZWUtNDNkZi1hMjI3LWZmMDc1ODgyZjE2MC5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03NDk4Yzk4MmM4YmM4YmI1ZWM5YzNjZjQ1ZDcwOWZkYWMyMWMyOGViYzExODVhYTg0MThkZDUyMGFjMjQ0MzVkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.6a1REDNWOXJN7E5xF5A1dWFviUwacWIqd-fNlPjUW5Q

https://private-user-images.githubusercontent.com/188140080/388418380-f6baf3f7-a12e-4755-923b-5651e24cf280.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzgwLWY2YmFmM2Y3LWExMmUtNDc1NS05MjNiLTU2NTFlMjRjZjI4MC5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00YmFjOTI4YWQ5NDI4ZTNiMzQ2NmU3YzhjZWEwNmU0NWU5N2Y4NTg1YTE2NTI4YzlkZGIxNWRjYzU5NjA2NTU4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.4xxrvPS4rA7AYQQzPgFKYbjaFIHIzFrGFDbb7u-r0cA

https://private-user-images.githubusercontent.com/188140080/388418388-aad9340e-aead-4caf-ab8f-584ee21a8034.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4Mzg4LWFhZDkzNDBlLWFlYWQtNGNhZi1hYjhmLTU4NGVlMjFhODAzNC5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yOWY2ZDVjMGUyMmM0OGM2MWZkM2Y1YWViYTNlMzFiOGQ5MGRjMTA5MmYxZTA2N2M2ZGM2ZTM3ZTNkOTZlYTdmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.DC51zeWbAhU1yK2sG_LrmisBDKlBkR6uH6H5IOGGY7g

https://private-user-images.githubusercontent.com/188140080/388418315-8fd43fb2-14b5-4f57-a47f-f7efdcc1261c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzIxNzc5NTAsIm5iZiI6MTczMjE3NzY1MCwicGF0aCI6Ii8xODgxNDAwODAvMzg4NDE4MzE1LThmZDQzZmIyLTE0YjUtNGY1Ny1hNDdmLWY3ZWZkY2MxMjYxYy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyMVQwODI3MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01ZDhkNzQ5Yzk0MTdhNWM5YmI2NzZkOTcwZWNkNGMwYmY3NGM5NGRhNWYwMmYyZWVlZGY2MGNkZjBlYjFiOTIyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.SrIbYkOVFop-9riAeBcsly9y3rFikIKUO6Go7ADeUHU

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
