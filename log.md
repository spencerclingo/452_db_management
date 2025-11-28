# Cesium Location Data

| Date      | Work                                                                                                                   | Hours |
| :-------- | :--------------------------------------------------------------------------------------------------------------------- | :---- |
| 9/29      | Started ticket to port standalone frontend to existing application                                                     | 4     |
| 9/30      | Finished port of Cesium application so it is workable in application                                                   | 3     |
| 10/1      | Renamed images to follow standard naming convention to make it easier to load into Cesium                              | 2.5   |
| 10/2      | Work on loading existing edges between nodes                                                                           | 3     |
| 10/3      | Continue work on getting polylines to load properly in 3d space                                                        | 3.5   |
| 10/6      | Re-designed frontend to match existing application styles rather than being separate                                   | 2.3   |
| 10/7      | Continued with the redesign, adding a custom description panel for nodes instead of Cesium default                     | 3.4   |
| 10/8      | Attempted to get nodes into collapsable divs for easy side-panel access                                                | 4.3   |
| 10/9      | Figured out how to get recursive collapsable divs to not open other collapsables at the same time                      | 3     |
| 10/10     | Design flyway migration to add GeographicCoordinate table to database                                                  | 2     |
| 10/13     | Add the proper Spring domain objects and column for node to reference the GeographicCoordiante table                   | 2.2   |
| 10/14     | Hook everything up so that location data for nodes is persistent                                                       | 2.5   |
| 10/15     | Add the same columns to graphs so that the entire graph can be moved across the map at once instead of only one by one | 1.5   |
| 10/16     | Full testing session to make sure that every implementation so far works as designed                                   | 4     |
| 10/17     | Re-design frontend with the guide of UI/UX Designer                                                                    | 4.8   |
| 10/20     | Add the ability to hide all nodes that have not been given positions, as well as hiding them from side panel data      | 3.3   |
| 10/21     | Add the ability to type in coordinates for nodes instead of only drag and drop to change individual node positions     | 2.6   |
| 10/22     | Design process to implement WiFi probability into probability of success calculations                                  | 2.5   |
| 10/23     | Start implementing WiFi probability                                                                                    | 3.5   |
| 10/24     | Redo what I did yesterday because I did it wrong                                                                       | 4.7   |
| 10/27     | Finally I can communicate with the other server to actually do the calculations I've been getting the data for         | 2.5   |
| 10/28     | Organize data so it can be sent to calculation backend                                                                 | 2.2   |
| 10/29     | Get walked through step by step of where to put stuff in the calculation backend because I have no clue where stuff is | 3.8   |
| 10/30     | Get calculation backend working. Write tests.                                                                          | 4.5   |
| 10/31     | Get tests to work because its feature freeze day for the release                                                       | 5.8   |
|           |                                                                                                                        |       |
| **Total** |                                                                                                                        | 81.4  |
