## Overview  

The **Forest Habitat Blocks** layer shows all forest habitat blocks that overlap the town of Cornwall.  

## Instructions  

By default, the Forest Habitat Blocks layer will draw when the atlas first loads. You can control the visibility and transparency through the **Layers** panel. 

## Model    

The Forest Habitat Blocks layer results from a model that uses high resolution [land cover](lc.md) data to update the spatial detail of landscape blocks identified by the 2016 [Vermont Conservation Design](vcd.md) program.  

The model consists of the three processing steps described below.   

### Step 1: forest habitat building blocks  

I first created **forest habitat building blocks** by identifying contiguous regions of tree canopy and grass/shrub land cover. This involved selecting a subset of land cover classes that are parts of habitat blocks, as shown in Table 1, and then identifying contiguous regions of contributing classes. In this model, the building blocks thus consist of contiguous patches of tree canopy or grass/shrub lands. Open water was not considered a component of habitat blocks, but instead contributes to habitat connectors discussed in the next section.     

---   

<center>

_Table 1: Land cover components of forest habitat building blocks._ 

| Land Cover type   | Building Block Component? |  
| :---              | :---:                     |
| Tree canopy       |   Yes                     |
| Grass/shrub       |   Yes                     |
| Open water        |   No                      |
| Active clearing   |   No                      |
| Bare soil         |   No                      |
| Buildings         |   No                      |
| Roads             |   No                      |
| Other pavement    |   No                      |
| Railroads         |   No                      |
| Build proximity   |   No                      |

</center>

---  

### Step 2: forest habitat targets  

I then created **forest habitat targets** by selecting Interior Forest Blocks, Connectivity Forest Blocks, or Physical Landscape Blocks that were identified through the Vermont Conservation Design program, as shown in Table 2. Habitat targets include both Highest and High Priority blocks. The three VCD elements that were not used as targets in this step will be used in the forest habitat connector model discussed in the next section.       

---   

<center>

_Table 2. VCD elements contributing to forest habitat targets._

| VCD Element                       | Habitat Target?           |
| :---                              | :---:                     |
| Interior Forest Blocks            | Yes                       |
| Connectivity Forest Blocks        | Yes                       |  
| Surface Water and Riparian Areas  | No                        |
| Riparian Wildlife Connectivity    | No                        |  
| Physical Landscape Diversity      | No                        | 
| Physical Landscape Blocks         | Yes                       |  

</center>

---  

### Step 3: forest habitat blocks  

I selected all the forest habitat building blocks that overlapped one or more forest habitat targets and then filtered these results for blocks that are at least 20 acres in area and overlap the town of Cornwall. 

This model identified 33 distinct forest habitat blocks that range in area from roughly 24 to 3226 acres.   

## Salt  

_The layer represents forest habitat blocks as they likely existed in 2016, not today._    

The high resolution land cover dataset used in the model represents land cover from the year 2016. Therefore, it does not capture any changes to land cover that have occurred over the last seven years.   

When a more recent high resolution land cover dataset becomes available, the model described is easily reproducible and will allow the opportunity to describe changes in habitat blocks since 2016.  

Qualitative investigations of change are possible by comparing the forest blocks to more recent [aerial images captured by the National Agricultural Imagery Program](naip.md). 

## Tests  

As preliminary tests of the model, the Forest Habitat Blocks can be compared to several independent efforts to identify [communities, habitats, and species locations](chs.md).  

Visual comparisons with these layers indicates that forest habitat blocks identified here include nearly all ecologically significant sites of Cornwall identified by these previous efforts with the exception of a small number of rare species locations that are represented as buffered points and are likely rough approximations of location. 

