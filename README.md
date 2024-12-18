# Neural Networks and Deep Learning AI315 Project

## Project Instructions

السلام عليكم ازيكم يا شباب
 
هبعت ليكم دلوقتى افكار المشاريع ؛ هم تقريبا 17 فكرة كلهم classification tasks 
كل فكرة هيشتغل فيها 5 تيمات كحد اقصى 
فبالتالى كل تيم هيختار 5 افكار بالترتيب اول فكرة هتختارها هتبقى ليها اعلى اولوية يعنى هترتبهم بترتيب الاولويات بتاعتك
وفى الاخر انا هعلن لكم الفكرة اللى اتعمللها assign لكل تيم بناءا على ترتيب اختيارات واسبقية الاختيار
 
التيم هيكون من 6-7 افراد 
وهفتح لكم فورم التتسجيل يوم الجمعة الساعة 4 عصرا باذن الله وهتفضل متاحة لغاية يوم الاثنين القادم الساعة 12 ظهرا علشان بعدها مباشرة هعلن لكم الassigned idea for each team 
الفورم دى هتسجلو فيها بيانات اعضاء التيم واختيار ال5 افكار 
لذلك مطلوب منكم دلوقتى انكم تكونوا التيمات وتستقرو على الافكار اللى هتختاروها 
 
ايا كانت الفكرة اللى هتختاروها فال requirements ثابتة كدا كدا 
مطلوب منكم: 
- تطبقو ResNet architecture from scratch with its implementation
- وتطبقو Xception, DenseNet as pre-trained models with only transfer learning on your dataset
- تعرضو الevaluation metrics لكل مودل من التلاتة وهنحتاج accuracy, confusion matrix visualization, recall, precision, f-score, ROC, AUC visualization
 - تعملو documentation تتضمن شرح التلاتة architectures بخطوات و , graphs وتحطو الreferences اللى اعتمدتم عليها ومن ضمنها اهم حاجة طبعا reference للpapers اللى قدملتنا الarhitectures دى 
- مقارنة بين ال3models على مستوى النتائج اولا وفى الdocumentation ثانيا بحيث توضحلى pros,cons لكل architecture وليه فيه افضلية مثلا ل architecure محدد مع التاسك والداتا بتاعتك

## Project Deliverables as per Instructions

- Implementation and training of ResNet architecture from scratch. 
- Transfer learning with pretrained Xception and DenseNet architectures on assigned dataset.
- Performance comparison between models on assigned dataset.
- Comprehensive documentation.

## Models 

- **Name**: ResNet 
     - **Paper**: Deep Residual Learning for Image Recognition - https://arxiv.org/abs/1512.03385
- **Name**: Xception
    - **Paper**: Xception: Deep Learning with Depthwise Separable Convolutions - https://arxiv.org/abs/1610.02357
    - **Implementations**:  
         - Keras Applications - https://keras.io/api/applications/xception/
         - Xception-PyTorch - https://github.com/tstandley/Xception-PyTorch 
 - **Name**: DenseNet
     - **Paper**: Densely Connected Convolutional Networks - https://arxiv.org/abs/1608.06993
     - **Implementations**: 
        - DenseNet Official Repo - https://github.com/liuzhuang13/DenseNet 
        - Keras Applications - https://keras.io/api/applications/
        - Pytorch/TorchVision - https://pytorch.org/hub/pytorchvisiondensenet/
     
## Assigned Dataset

**Name**: PlantVillage Dataset

![image](https://github.com/user-attachments/assets/7cd8d925-8386-4598-ae2f-12258f0aef54)

**Dataset Links**: 
   - Kaggle - https://www.kaggle.com/datasets/emmarex/plantdisease
   - PapersWithCode - https://paperswithcode.com/dataset/plantvillage
   - Mendeley - https://data.mendeley.com/datasets/tywbtsjrjv/1
**Paper**: Identification of Plant Leaf Diseases Using a 9-layer Deep Convolutional Neural Network - https://doi.org/10.1016/j.compeleceng.2019.04.011

## Project Team

- Abdelrahman Hatem (Team Leader)
- Motawea Mohammed
- Essam Ali
- Mariam El Saket
- Mostafa Mohamed
- Mohamed Nasser
- Ahmed Harmas 
