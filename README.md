# GLIE Internship Code
Repository of code that I have made within ITP

- This is a repository of the code I have made within the 13 weeks that I was assigned inside GLIE. The code will be pretty rough, but I will document it by week within this README file
- My personal branch impementation of the code is always found in: https://github.com/devInTrainin/symmetrical-disco
- My branch of implementation is there inside : https://symmetrical-disco-tbn5omdg6dgvpohpga3yrx.streamlit.app/
- The team's implementation of the code is found inside : https://symmetrical-disco-uzipvbamdwegcydzfwgszt.streamlit.app/Search_Companies

## Week 1
- Untitled.ipynb
  - This file is the ipynb file which has us working with fuzzy searching methods and working together on how to refine its parameters in order to work


## Week 2
- Making a filter for FCA, FET.ipynb
  - this file works on combining FCA file and FET file together, which also starts work with making jobstreet pairing as well. 
- 10 August still working on FET
  - This file continuing on the work done which is mainly testing out basic stuff such as column reconfiguration for the dataset

## Week 3
- 15-8 reading the jobstreet attached data
  - this file continuing on the attaching the jobstreet from previous weeks with my FET and FCA file
- 15-8 reading the population data
  - this file is a test of using population.xlsx for trying to gain more information from the places that we are looking into
- Combining FCI, FET and FCA
  - this is the file in which we start using the code to directly manipulate the master list to fix the names and addresses.
    - some stuff that we do is fixing the names from online, as well as addresses and the company ID.
    - This file is also the making of the final dataset from 8 faculties, saving it into a file named master_df

## Week 4
- 22-8 - intern.ipynb
  - this file is the start of manipulating the data which is already paired with jobstreet. The main reasoning for doing this is to see if we can figure out which of the names has duplicates within the set
- 23-8 finishing work
  - this code simply looks at the code for a dataset and sees which both the main address and secondary address, then decides which one is the one to be kept.
    - This is because the addresses sometimes have duplicates and as such needs to be validated on which one is the proper one.
- 24-8 make pie chart smile
  - this file simply looks at the dataset that we have compiled together and makes graphs, both bar charts as well as pie charts and
- Reading the dataframe and cleaning the addresses given
  - this one reiterates over the whole dataset for my part, and then figures out within the addresses which one is the one to keep, either the main address or the secondary address
  
## Week 5
- 30-8 - doing the intern work of attaching the two sheets.ipynb
  - We are working with poskod.csv in which that we are taking the poskod and manipulating it to pair it with the master csv.
- New FOM list, to combine with the final one (29 - 8)
  - This code shows how we do the cleaning code, for only one faculty. This one being new FOM, which was given to us later on, on Week 5
- 30-8_40k_to_50k_geocoded.xlsx & other xlsx with the poskod data
  - This is the work done in which we added the poskod towards the geolocating using Awesome Table
  - The main limit for our student emails is 10k rows, with normal emails capping at 1k rows.
  - We feed it manually to output the data that we want, which is the rows for addresses, with the lat/long data

## Week 6
- FINAL_LIST_Processed_with_new_FOM_address.xlsx
  - this file shows the processed data after adding the newer FOM addreses
- Folium folder
  - This folder shows the code as well as the training files we used to teach the other interns on how to both add pushpins as well as how to manipulate data using choropleth as well as heatmaps
- Poskod file
  - This file shows the experiment on implementation of the code above onto our code
 
## Week 7
- Labuan Johor Terengganu Melaka.ipynb
  - This file is the part of which I am responsible for, for making the pushpins for the states of labuan, johor, terengganu as well as Melaka.
  - it shows the basic pushpin application inside the maps, for each of the states
- Choropleth WIP file
  - This file shows my implementation of the heatmap, with changing the sliding scales to ensure the companies are within a good scale to not lose information during the heatmap
- Streamlit map plot
  - This is the method on which we manipulate the map data to attach the pushpins as well as the choropleth inside the geojson map

## Week 8
- Combine inside streamlit folder
  - This folder has a number of code inside it, with some basic charts to be put inside the website, as well as some map testing
  - it also has one of the implementations of the streamlit inside it, with the folder 'Thursday new streamlit'
- Input FIST data folder
- Input FOM data folder
 - These two folders show the methodology in implementing new datasets into the old code, to add it inside the main dataset

## Week 9
- companylist1-main (1)
  - This folder shows the implementation of MMU logo as well as consolidating some of the code in a more cohesive manner.
- Test pair with geocode.ipynb
  - This file shows the implementation of the code in which we pair the company address data, with manual changing of problematic addreses

## Week 10
- Hamid's work
  - This folder shows the work done by the intern Hamid, and my testing of its work. Its should be the one which adds more features inside the pushpins so that we can see more information when we click on the pushpins
- Sample_Streamlit Map Plot.zip
  - An old implementation of the streamlit map application

## Week 11 and above
- Untitled.ipynb
  - mainly this is a test for the code of pyrosm data to implement it inside, but we cut it out due to some members not being able to run this work
