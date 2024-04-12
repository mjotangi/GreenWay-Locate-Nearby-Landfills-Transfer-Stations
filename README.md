# **Green Way: Locate Nearby Landfills and Transfer Stations**

## **Overview**

- Sustainability is the practice of meeting current needs without compromising the ability of future generations to meet their own needs. This principle is crucial for several reasons, with one of the key aspects being environmental conservation.
- When we talk about sustainability, we're emphasizing the importance of using resources efficiently and reducing waste. This approach plays a significant role in preserving natural resources like clean air, water, forests, and biodiversity. By managing resources responsibly, we can protect ecosystems and minimize the impact of climate change.

<img width="1440" alt="image" src="https://github.com/mjotangi/GreenWay-Locate-Nearby-Landfills-Transfer-Stations/assets/146262756/5daec52f-571e-4a71-b676-387fc39d18f6">


## **The "Green Way" project contributes to sustainability in several ways:**

### **1. Efficient Waste Management:**

By helping users locate nearby landfills and transfer stations, leading to proper waste disposal which reduces pollution, minimizes the force on natural resources, and prevents environmental degradation.
### **2. Reduces Carbon Footprint:**

The project minimizes carbon footprints by enabling easy access to waste facilities, reducing transportation distances, and lowering vehicle emissions, thus aiding climate change mitigation and fostering environmental sustainability.
### **3. Supports Green Infrastructure:**

The project promotes green infrastructure adoption through interactive maps and geolocation services, showcasing digital tools that enhance waste management efficiency, reduce resource use, and foster sustainable urban development.


## **Project Planning**

### **1. Scope and Objective:**

A web application named "Green Way" that helps users locate nearby landfills and transfer stations based on their address input within Phoenix city area. The key features and functionalities of the application include:

#### **A. User Address Validation:** 	
Users can input their address, and application validates the address against active_service_addresses.csv file to ensure its accuracy and eligibility.
#### **B. Location Display:**
Upon successful address validation, the application displays the entered address, service area information, a link to the bulk-trash collection schedule, and shows the user’s address with a custom marker icon on the map using the OpenStreetMap API.
#### **C. Distance Calculation:**
Utilize Mapbox Direction API to calculate the distance between the user's address and nearby stations to determine the nearest station.
#### **D. Nearest Station Search:**
Users can click on the "Landfill/Transfer Station" button to find the nearest station to their address. The application calculates the distance to each station, displays the nearest station, and shows the shortest driving route between them on the map.
#### **E. Detailed Nearest Station Information:**
The application provides detailed information about the nearest station, including its name, address, operating hours, holidays, and directions. It also displays the distance in miles from the user's address to the station.
#### **F. Error Handling:**
Implement error handling mechanisms to handle unexpected errors during address validation, map loading, and API interactions to ensure smooth functionality.

### **2. Data Source**

We have downloaded the dataset "Public_Works_Solid_Waste_Active_Service_Addresses.csv" from https://www.phoenixopendata.com/dataset/public-works-solid-waste-active-service-addresses/resource/fa1ff854-4b88-4b47-8909-4556efedd823.

We have created a “Transfer_Station_Dataframe.csv” file which has landfills & transfer stations of Phoenix city.

We have used “City_Limit_Dark_Outline.geojson” file from https://mappingphoenix.opendata.arcgis.com/datasets/d4e1e600f9404d9ea104de8ac36b5724_0/explore to show boundary of Phoenix city area.

### **3.Target Audiences**

- Resident Homeowners
- Business Owners
- Communities
- Landscapers
- Waste Management Professionals

### **4.Tools and Technologies**

- Languages: Python,HTML,CSS,JavaScript
- Tool: Visual Studio Code
- API: OpenStreetMap API, MapBox Direction API

## **Use Cases**

- Any city resident can utilize this website when needing to transfer bulk trash.
- Landscapers with substantial amounts of green or garden waste can directly bring it to one of the city's transfer stations.
- Users can check their collection day; however, if they have a pile exceeding 20 cubic yards or containing more than 25 pounds of construction and demolition waste, it will not be collected. Instead, they must deliver it to the nearest transfer station.






