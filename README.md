EXPORTED TEACHABLE MACHINE MODEL FILES:
 https://drive.google.com/drive/folders/19u3NhrxKh345FJ0kFQbw44qKxnEXNnLj?usp=drive_link
																																								
 DATA SET SCREENSHOT
 <img width="1753" height="902" alt="image" src="https://github.com/user-attachments/assets/5de2a4de-b701-4fd5-9ba5-781fd028bf02" />
 
A. Project Overview
Brief description of the project -


This project uses Teachable Machine to create an image classification model for different types of creeper plants. The dataset contains 5,000 total images, with 250 images per class, to ensure balanced and accurate training results. Each image shows creeper plants under different angles, lighting conditions, and backgrounds to help the model learn real-world variations.

The images are organized into labeled categories and uploaded to Teachable Machine for training, testing, and validation. The goal of the project is to build an AI model that can automatically recognize and classify creeper plants based on visual features such as leaves, stems, and growth patterns.

This approach makes the model more reliable and reduces bias because every class has the same number of training images. The trained model can be used for plant identification, educational demonstrations, and basic computer vision applications.

PURPOSE OF THE IMAGE CLASSIFICATION MODEL

This project develops an image classification system for different creeper plants using Teachable Machine. The dataset contains 5,000 total images, with 250 images per class, to ensure balanced and unbiased model training. Images were collected with variations in angle, lighting, and background so the model can learn real-world visual differences such as leaf shape, vine structure, and surface texture. The purpose of the image classification model is to automatically recognize and categorize creeper plants based on these visual features, providing fast and consistent identification without manual checking. This project demonstrates practical computer vision and machine learning concepts and can be used for educational activities, basic plant identification, and AI model training practice.


B. Plant Species Section
 

![1](https://github.com/user-attachments/assets/5694eb11-ac35-4602-af5d-c528889c11bf)
Common Name: Kabocha squash (also called Japanese pumpkin)
Scientific Name: Cucurbita maxima (Kabocha group)

Kabocha squash, also known as Japanese pumpkin (Cucurbita maxima), is a warm-season creeping vine in the gourd family (Cucurbitaceae), which includes pumpkins, melons, and cucumbers. It grows long trailing stems with curling tendrils, broad green leaves, and bright yellow flowers that develop into round or slightly flattened fruits with hard green rinds and sweet, dense orange flesh.

Kabocha thrives in warm, sunny climates with fertile, well-drained soil. It requires consistent watering and proper spacing, and is sensitive to frost. The fruit is nutritious, rich in beta-carotene, vitamin C, fiber, and antioxidants, making it a popular ingredient in soups, roasting, and desserts.

For image classification or machine learning projects, kabocha squash is ideal due to its distinct vine growth, leaf shape, fruit color, and texture, making it easy to recognize as a creeper plant.


C. Model Training Details

<img width="328" height="673" alt="Screenshot 2026-02-14 004309" src="https://github.com/user-attachments/assets/8343538c-7260-43c6-8acc-a6be171ecbe6" />

Number of images per class :250


D. Model Evaluation

<img width="898" height="885" alt="Screenshot 2026-02-14 010135" src="https://github.com/user-attachments/assets/d242429c-3364-45e9-a695-164fcac156d7" />

E. Model Testing

<img width="254" height="871" alt="sample1" src="https://github.com/user-attachments/assets/b55151f0-4f39-4e71-b2ae-f838de93204d" /> <img width="260" height="887" alt="sample3" src="https://github.com/user-attachments/assets/47f2dc3e-9a04-4121-984d-ee6ffda1647b" />

<img width="329" height="893" alt="sample2" src="https://github.com/user-attachments/assets/5e854f70-6aa9-4efd-a6c0-b7bba0f46f19" /> <img width="317" height="896" alt="sample4" src="https://github.com/user-attachments/assets/298e06b3-e2e7-42d2-9365-46263de6fb24" />

<img width="254" height="887" alt="sample5" src="https://github.com/user-attachments/assets/f84aab34-6060-4a30-be34-a35fa9096080" /> <img width="273" height="887" alt="sample6" src="https://github.com/user-attachments/assets/6194c420-c0c1-4e64-8d61-caac8d87257f" />

<img width="266" height="889" alt="sample7" src="https://github.com/user-attachments/assets/10451682-d6c4-4aa7-a718-6e3727c218d0" /> <img width="245" height="892" alt="sample8" src="https://github.com/user-attachments/assets/36f14fe6-1fd6-4ea7-9f03-1195850c991c" />

<img width="300" height="893" alt="sample9" src="https://github.com/user-attachments/assets/ebc50293-4cba-4609-801d-54e9f3ac1a2d" /> <img width="263" height="889" alt="sample10" src="https://github.com/user-attachments/assets/f72f4c50-8676-4b4e-b5ff-45c6f3df11d4" />

REFLECTION QUESTIONS :

 1. How did the number of images per class affect your model’s accuracy?
   
   ANSWER : It affects significantly

 2. Which plant species were most commonly misclassified and why?
   
   ANSWER : The ivy gourd,because there are other creepers that has the same color, and also ivy gourd can adapt the similarity of any other creepers mentioned
   
 3. How did changing the epochs, batch size, or learning rate affect the training results?
   
   ANSWER : after changing those settings the training results are getting more likely accurate.

 4. What challenges did you encounter during dataset collection and labeling?

    ANSWER: The dataset is too many, to the point that labeling each one is tiresome

 5. If you were to improve your model, what specific changes would you make and why?

    ANSWER: Probably on the epoch side , becuase the current model tend to misclassified the sample of those images that are being fed to it.
   

