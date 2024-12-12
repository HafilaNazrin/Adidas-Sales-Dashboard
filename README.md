# Adidas-Sales-Dashboard
Have you ever been curious about building an interactive Excel dashboard using tables? I was eager to dive into this process, so I followed a brilliant tutorial by “Adewale Yusuf” and added my tweaks to the wireframe to enhance its potential. In this article, I’ll present screenshots showcasing the dashboard’s impressive features and provide a detailed, step-by-step guide on how I created it from start to finish.

![Dashboard](https://github.com/user-attachments/assets/8484f7cc-56ea-44c3-a353-3ccb8f6c7489)

Data analysis is a game-changer for optimizing business operations, empowering informed decisions and strategic planning. Recently, I worked on a project where I analyzed sales data from an Adidas Store, designed an interactive dashboard, and visualized the insights using Excel. In this article, I’ll walk you through my approach, from collecting the data to crafting the interactive dashboard.

## Objective
The client wanted us to design an interactive dashboard containing a slicer to filter by Year and Store Type. They wanted to have an Annual sales Development. Also, the charts display the Total units sold by Region and Profit Retailer.

![Adidas Wireframe](https://github.com/user-attachments/assets/669c88b0-b5f1-4f38-bfc2-1450815a5561)

## Collection of Data from source
Link to the dataset : [Adidas Dataset](https://drive.google.com/drive/folders/1bh0nlX0EaXpWOpd34oC_7c46mxGpWdS_?source=post_page-----a1e04e618610--------------------------------)
We have a sheet that contains Retailer, Retailer ID, Invoice Date, Location Key, Product, Price per Unit, Units Sold, Total Sales, Operating Profit, Operating Margin, Sales Method, Product URL, Region, State and City.

## Building Dashboard
Since the dataset was cleaned there was no need for data cleaning and transformation.

### 1. Charts using Pivot Tables
* Using a Pivot Table by placing Region and sum of units sold. By using this I created a bar chart.

![Pivot Table](https://github.com/user-attachments/assets/0cb4c081-2f83-4edc-b5fc-3ddf7ea88fa6)
![Chart 1-Bar Charts](https://github.com/user-attachments/assets/f3c13e99-88b2-4539-a27d-1735ee1c9129)

* Using a Pivot Table by placing Profit, Sales and Units Sold. By using this I created a line chart.

![Pivot Table-DIff bw month](https://github.com/user-attachments/assets/56b4da51-39fd-4ba8-803e-63523f249e22)
![chart 2-Line Chart](https://github.com/user-attachments/assets/8eeae1ce-fb7d-4083-a725-88914b1659a9)

### 2. Filters using Slicer
Using Slicer I have created the Filter for Store Type and Year. The Slicer was connected with all the Pivot Tables by using report connections.

### 3. Visual Cards
Visual Cards are created using Pivot Tables and it can be Variable depending on the Filter.

![Card Visuals](https://github.com/user-attachments/assets/3615c352-cde0-4eaa-9236-3bc5c0a851f5)

## Conclusion
At last, the Final Interactive Report is created with all the requirements of the user.

* I created an interactive dashboard that serves as a valuable tool for shop owners and managers.
* This dashboard not only gives a snapshot of the performance but also helps in making strategic decisions by highlighting key trends and areas for improvement.
  
Thanks for reading, see my profile for more Data Analysis projects!
