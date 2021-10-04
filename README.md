# Mapping tool - Wheelchair users travel in city and the urban development direction

## Description
As a normal person living in a developed city, it is usually difficult to feel the inconvenience in life, but the wheelchair users often face many problems during living in the modern city. For example, if there is no disabled path/slope for wheelchairs to pass, the wheelchair users cannot enter the building or an area through the stairs. The extent of the convenience provided by the city for the wheelchair users reflects a city's inclusiveness for the disabled. This tool studied this topic and provide direction for the development of the city in future.


This tool considered the residents who use wheelchairs and wheelchair users from other places and detected the travel convenience of wheelchair users in the current city. It screened out the buildings with wheelchair facilities first and took some common places that wheelchair users usually visit, and then tested the connectivity of these places.

For example: Residential area-Transport station-Public openspace (residents who use wheelchair); Hotel-Transport station-Historical building (visitors who use wheelchair).

Based on the idea of the wheelchair facilities will increase in city over time, this tool also have a slider control time,that can help find out the issue in urban planning and predict the development of the city. 

This is a file based on grasshopper, integrated the information of the chosen site and present the site analysis in a effective and clear way.You may need to download your city map form Open Street Map and intsert to run the program.


## How to use
1. Insert your own OSM file in to the *File Path* at top left corner.
2. You can change the number slider that highlighted with yellow panel notes to make it fit your map.
3. You can change the time slider to predict future development at middle left.
4. Map done!

## Example
Here takes Marseille as an example to run this program.

### Overview:
A note befor showing the example: Legend is on the left of the original panel, in case it's hard to find when insert a large city map.

![rm4](https://user-images.githubusercontent.com/88953049/135787633-d83b5de0-a772-47ac-bdf6-b1dfd1300159.JPG)

![rm8](https://user-images.githubusercontent.com/88953049/135787590-46c4d898-cac8-4273-ad82-45187406bb8d.JPG)
![rm9](https://user-images.githubusercontent.com/88953049/135787579-6663dce6-f637-49ef-b9bd-44c855a4f47c.JPG)
![rm10](https://user-images.githubusercontent.com/88953049/135787601-1645b4bf-754b-40a8-9673-fb62a4f1f726.JPG)


The following three screenshots show the map changing over time, with connection lines on. 

![rm1](https://user-images.githubusercontent.com/88953049/135784806-11319be1-765b-4044-9cd5-6698a6a4d362.JPG)
![rm2](https://user-images.githubusercontent.com/88953049/135784809-beb478db-59aa-47ae-a38c-8c47148d137c.JPG)
![rm3](https://user-images.githubusercontent.com/88953049/135784820-cddac7d5-2061-4f47-8f3c-afec605ee655.JPG)

The yellow and green lines are the connection between tranport stations and destinations (Historical buildings and Public openspaces) with wheelchair facilities (detail annotions are in GH file). More lines represent more options for wheelchair users. You can only check the connection between starting points (Residential area, school, hotel and hospital) and transport stations by turn off the preview in red rectangle in below.

![rm11](https://user-images.githubusercontent.com/88953049/135788176-26034e87-b2e2-48dc-a840-a7928db70755.JPG)

### Detail 1:
The following three screenshots show the map changing over time, with the connection lines off. This provides a clearer version of the travel options for wheelchair users.

![rm5](https://user-images.githubusercontent.com/88953049/135784965-5281f287-3c71-479a-acbf-785e959c872b.JPG)
![rm6](https://user-images.githubusercontent.com/88953049/135784970-f4e28e05-5807-4ad3-8ade-8c2b121dc81f.JPG)
![rm7](https://user-images.githubusercontent.com/88953049/135784972-d1c9d494-3e0d-42f0-9eee-dcf8e6f3c807.JPG)

### Detail 2:
The tool also provide charts to track the change over time.

![捕获3](https://user-images.githubusercontent.com/88953049/135784981-64f5c141-57aa-482e-b73f-19669132d184.JPG)
![8](https://user-images.githubusercontent.com/88953049/135784983-0cc152da-0e27-4dd0-ad58-0000ad00c4b1.JPG)


## Appendix
Please check the development log on Notion by link: <https://www.notion.so/3635634-Log-Bonnie-Zhang-4a6312dd05b04ed58b375f379b4b2d1c>.
