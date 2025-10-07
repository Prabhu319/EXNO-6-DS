# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 <img width="775" height="763" alt="image" src="https://github.com/user-attachments/assets/3a4b807d-e27a-4c9d-87c6-6cababe05d53" />

 <img width="616" height="644" alt="image" src="https://github.com/user-attachments/assets/72328a6e-98c3-4f67-a6aa-3eeb265b525b" />
 <img width="863" height="686" alt="image" src="https://github.com/user-attachments/assets/83e4e96c-690e-4e2f-921f-63e371ff2410" />

<img width="845" height="828" alt="image" src="https://github.com/user-attachments/assets/d25464f3-12ff-4f89-bf82-9cbca96ad4a3" />

<img width="909" height="254" alt="image" src="https://github.com/user-attachments/assets/dc515d73-61ec-4098-8aa3-5e2c229fc77d" />

<img width="890" height="769" alt="image" src="https://github.com/user-attachments/assets/69a6a1f1-4235-4bd0-bceb-edb69f98ca29" />

<img width="834" height="210" alt="image" src="https://github.com/user-attachments/assets/fb3c5b53-8594-4a75-973d-d7304a67b8f5" />
<img width="912" height="647" alt="image" src="https://github.com/user-attachments/assets/901fe38d-2b5f-4181-a695-6a374690fa33" />

<img width="850" height="743" alt="image" src="https://github.com/user-attachments/assets/df63caf4-c229-4a40-ab59-bd787aa67602" />

<img width="917" height="788" alt="image" src="https://github.com/user-attachments/assets/f44ae69c-a59f-403e-b79c-5a20c89443f9" />
<img width="1383" height="600" alt="image" src="https://github.com/user-attachments/assets/91538988-8352-4441-b5b0-8d384319e36c" />

<img width="884" height="83" alt="image" src="https://github.com/user-attachments/assets/e61b444e-7258-4154-a117-763a3364fa75" />
<img width="921" height="673" alt="image" src="https://github.com/user-attachments/assets/e495222a-7097-4521-aef7-762bfd398ca1" />

<img width="904" height="759" alt="image" src="https://github.com/user-attachments/assets/41e2a85a-8a6d-4d41-81e1-643903d9e07a" />

<img width="932" height="797" alt="image" src="https://github.com/user-attachments/assets/39c38613-2912-4e2c-a225-6bd67ff6dcad" />

<img width="873" height="519" alt="image" src="https://github.com/user-attachments/assets/5e425897-c7fe-48fd-b29d-f6b748a1aad4" />
<img width="908" height="667" alt="image" src="https://github.com/user-attachments/assets/cc017ae1-11a8-4260-996d-e2d541c69c6d" />
<img width="921" height="704" alt="image" src="https://github.com/user-attachments/assets/6a97e597-6d9c-4ccb-88b4-e19ccd2eea7c" />

<img width="899" height="634" alt="image" src="https://github.com/user-attachments/assets/fa77f1fa-6cf0-4d3e-ab5a-320e69b2d39b" />
```
sns.histplot(data=marks,bins=10,kde=True,stat='count',cumulative=False,multiple='stack',element='bars',palette='Set1',shrink=0.7)
plt.xlabel('Marks')
plt.ylabel('Density')
plt.title('Histogram of Student Marks')
```
<img width="933" height="655" alt="image" src="https://github.com/user-attachments/assets/66d643bd-e18a-4db0-bfbc-30899a327e4e" />

<img width="916" height="720" alt="image" src="https://github.com/user-attachments/assets/23300bb6-b9a4-4d1a-bcf2-94f733bfffde" />
```
sns.boxplot(x="day",y="total_bill",hue="smoker",data=tips,linewidth=2,width=0.6,boxprops={"facecolor":"lightblue","edgecolor":"darkblue"},
            whiskerprops={"color":"black","linestyle":"--","linewidth":1.5},capprops={"color":"black","linestyle":"--","linewidth":1.5})
```
<img width="906" height="657" alt="image" src="https://github.com/user-attachments/assets/fd9921f7-d376-464e-a536-6fe0420b86eb" />

<img width="910" height="783" alt="image" src="https://github.com/user-attachments/assets/c547205a-d228-423f-bf29-9871b17a0b28" />
```
sns.violinplot(x="day",y="total_bill",hue="smoker",data=tips,linewidth=2,width=0.6,palette="Set3",inner="quartile")
plt.xlabel("Day of the week")
plt.ylabel("Total Bill")
plt.title("Violin Plot of Total Bill by Day and Smoker Status")
```
<img width="909" height="642" alt="image" src="https://github.com/user-attachments/assets/6da9d0e5-46d2-461e-86b3-8b584e1a5ea7" />

<img width="934" height="760" alt="image" src="https://github.com/user-attachments/assets/08d74084-5c10-4b58-a45e-ac7b09f5e0a3" />
<img width="861" height="813" alt="image" src="https://github.com/user-attachments/assets/7e939181-bef7-49c4-a2b4-b46ba8e15e17" />

<img width="914" height="734" alt="image" src="https://github.com/user-attachments/assets/801b903d-b7b4-4c2b-8426-ad81f370ec9e" />
```
sns.kdeplot(data=tips,x='total_bill',hue='time',multiple='layer',linewidth=3,palette='Set2',alpha=0.8)
```
<img width="909" height="653" alt="image" src="https://github.com/user-attachments/assets/c4218b5d-c15e-404d-a1b8-9125e29897ba" />

<img width="761" height="410" alt="image" src="https://github.com/user-attachments/assets/4e3dc334-cc86-4b39-bfe2-15455572aa78" />

<img width="948" height="621" alt="image" src="https://github.com/user-attachments/assets/1d7a42b3-ec91-4a75-b599-1cb0c421fcce" />

<img width="891" height="771" alt="image" src="https://github.com/user-attachments/assets/ac05382b-569e-4dcf-b834-3ca3b87eb806" />


# Result:
 Data Visualization using seaborn python library for the given datas has been performed successfully.
