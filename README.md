# py_2d_map_into_3d_cv2_pyqtgraph
Turn 2d map into 3d map using cv2 and pyqtgraph in Python
<p>
  <h3 style = "text-align = center ;">Step1. IDEA</h3>

  I wanted to change 2d map into 3d map. What it means is when i put 2d map <br>
  The program scans the image and analyze location of structures like buildings, houses<br>
  And visualize it on 3d moniter.<br>
  <img src = "shinjung.png"><img src =  "">
</p>

<p>
  <h3 style = "text-align = center ;">Step2. Implement</h3>

  What I thknk first is to extract pixel data from 2d map using opencv(cv2).<br>
  Since the color area of each structure(like apartment, school, load / and if it's just one building whatever) color differs on both side of one line<br>
  cv2를 이용해 이미지의 픽셀값 추출 -> 지도에서 구역(아파트, 길) 마다 색이 다르고, 건물일경우 건물과 외부 사이 색이 다르므로 건물의 색, 또는 아파트의 색 추출<br>
  
</p>
