# solution
뭔가 애러가나거나 문제가있는부분 어떤식으로 해결했는지 나중에 써먹게 메모

제로베이스강의중 파일을 받았는데 완성파일도그렇고 전부다 버튼이짤리는 상황
wrap div 안에 header가 있고 css상 header는 width가 100%로 되어있는데 넘쳐버리는상황
wrap에 overflow가 히든으로 되어있어 넘쳐버리는부분은 모두 숨김처리가 되서 짤린다

![image](https://user-images.githubusercontent.com/89917101/184613377-2362da34-75d5-4be7-98d2-016afcd7418e.png)

![image](https://user-images.githubusercontent.com/89917101/184613535-388c2301-fb5c-4ade-a74e-696d6f11250a.png)

![image](https://user-images.githubusercontent.com/89917101/184613738-303de4e6-657c-480f-8569-293d8c1aea51.png)

header가 가지는 padding값만큼 값이 넘치는거같아서 padding값을 고려해서 크기를조절하는
box-sizing : border-box를 추가해서 해결했다.

![image](https://user-images.githubusercontent.com/89917101/184615267-bccedf1d-f57d-4339-8055-137f0ea61497.png)

![image](https://user-images.githubusercontent.com/89917101/184615387-bb7cf70f-4cad-4e87-b787-4874dbc6f24c.png)
