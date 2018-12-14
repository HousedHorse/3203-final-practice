# GPS (Global Positioning System)
## We discussed localization
- **Geographic location** is defined by two coordinates (**longitude** and **latitude**)
- **Geographic localization** refers to **algorithms for** finding your **geographic location**
- **Triangulation**: process of **determining location** of a point by **comparing angles** to it from known points
  - **SOHCAHTOA**
  - <insert slide 4, and 5 here>
- **Another way to measure distance**:
  - <insert slide 6, 7, and 8 here>
- **Three techniques** (Assuming distance based GPS)
  - **Three position aware neighbours** are required for **2D**, and 4 for 3D
  - A **base station** will **synchronize** the location **aware nodes/anchor** to emit signal at same time
    - using these signals, **sensor node** can **calculate its location**
  - **TOA** (Time Difference of Arrival)
    - Time difference of arrival from two anchors |t<sub>1</sub> - t<sub>2</sub>|
    
