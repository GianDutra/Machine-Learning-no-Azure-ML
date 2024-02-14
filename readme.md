## Machine Learning on Azure ML [:us: Video Tutorial](https://www.youtube.com/watch?v=p7zSlx5j-e4&t=45s) | [:brazil: Video Tutorial](https://www.youtube.com/watch?v=scEeK9juXOQ) | [🇪🇸 Video Tutorial](https://www.youtube.com/watch?v=PbmIYPwWtP8&t=3s)




<p align="center">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/GianDutra/Machine-Learning-no-Azure-ML">

   <a href="https://github.com/GianDutra/Machine-Learning-no-Azure-ML/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/GianDutra/Machine-Learning-no-Azure-ML">
  </a>
  
</p>
<img src="./images/capa.png" alt="dashboard apresentando diversos números estatísticos, um gráfico comparando o que estava previsto e o que realmente aconteceu e um gráfico de histograma" title="Machine-Learning-Azure-ML">
> Project developed as a challenge - AI-900 Preparation!

## About the project

My first project on Azure Machine Learning, in which, using regression, I trained a model with more than 6000 different games to make assumptions or predict global video game sales, as well as to generate a dashboard with various insights.
  
## **Step-by-step**

### **Step one**

First, I created a new workspace in Azure Machine Learning, as well as creating a new resource group and choosing a name for my project. Then, I simply left the rest as default and clicked on "create", and then waited about 5 minutes for the successful creation of my workspace.

<img src="./images/1.png" alt="">
<img src="./images/2.png" alt="">
<img src="./images/3.png" alt="">
<img src="./images/4.png" alt="">
<img src="./images/5.png" alt="">


### **Step two**

I initiated the studio as you can see in the photo, I chose the "Automated ML" option and created a new automated ML job. Next, I put in a name I thought was suitable for my project, a name for my experiment, and a description. After that, I chose to perform regression because I wanted to predict a numerical value. I selected "Tabular" as the data asset type, imported a .csv file that I wanted to experiment with, and processed the data to see if it was in the correct format. Finally, I chose the primary metric "NormalizedRootMeanSquaredError" and allowed the "RandomForest" and "LightGBM" models, setting in the limits tab the respective values of: 3, 3, 3, 0.085, 15, 15, and enabling early termination, in addition to choosing the validation option called "Training validation split".

<img src="./images/6.png" alt="">
<img src="./images/7.png" alt="">
<img src="./images/8.png" alt="">
<img src="./images/9.png" alt="">
<img src="./images/10.png" alt="">
<img src="./images/11.png" alt="">
<img src="./images/12.png" alt="">
<img src="./images/13.png" alt="">
<img src="./images/14.png" alt="">
<img src="./images/15.png" alt="">
<img src="./images/16.png" alt="">
<img src="./images/17.png" alt="">
<img src="./images/18.png" alt="">
<img src="./images/19.png" alt="">
<img src="./images/20.png" alt="">
<img src="./images/21.png" alt="">
<img src="./images/22.png" alt="">
<img src="./images/23.png" alt="">


### **Step three**

aaaa

<img src="./images/24.png" alt="">
<img src="./images/25.png" alt="">
<img src="./images/26.png" alt="">
<img src="./images/27.png" alt="">
<img src="./images/28.png" alt="">
<img src="./images/29.png" alt="">
<img src="./images/30.png" alt="">
<img src="./images/31.png" alt="">
<img src="./images/32.png" alt="">
<img src="./images/33.png" alt="">
<img src="./images/34.png" alt="">
<img src="./images/35.png" alt="">
<img src="./images/36.png" alt="">
<img src="./images/37.png" alt="">
<img src="./images/38.png" alt="">
### Step 2

## 👨‍💼 Autor

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://github.com/GianDutra.png" width="100px;" alt="Foto do Gian no GitHub"/><br>
        <sub>
          <b>Gian Dutra</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
