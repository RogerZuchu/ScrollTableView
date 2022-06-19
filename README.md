# ScrollTableView

# Step 1
Tạo UIViewController

-------------------------------------------------------------------------------------------------------------------------------------------

# Step 2
Add Scrollview Kéo tay full màn hình
<img width="1680" alt="Screenshot 2022-06-20 at 01 06 18" src="https://user-images.githubusercontent.com/107794765/174494532-62ae634a-a2ec-4dc6-bdef-74a89530dfdf.png">
-------------------------------------------------------------------------------------------------------------------------------------------
# Step 3 Set Top,lail,trail,bot với thằng View hoặc SafeArea
<img width="1680" alt="Screenshot 2022-06-20 at 01 08 11" src="https://user-images.githubusercontent.com/107794765/174494678-5a2b5042-c9f5-4429-a7fc-fdf5c16b610a.png">

-------------------------------------------------------------------------------------------------------------------------------------------
# Step 4 Add TableView
<img width="1680" alt="Screenshot 2022-06-20 at 01 11 49" src="https://user-images.githubusercontent.com/107794765/174494701-97221202-6f0d-46d3-a319-37fe1ad30a3d.png">


-------------------------------------------------------------------------------------------------------------------------------------------

# Step 5 Chọn Tableview và set  0 0 0 0 với FrameLayout 

<img width="1680" alt="Screenshot 2022-06-20 at 01 13 48" src="https://user-images.githubusercontent.com/107794765/174494802-5782753e-6257-4e3c-8452-2216ea47ee69.png">
-------------------------------------------------------------------------------------------------------------------------------------------

# Step 6 Kéo lên Set Top,lail,trail,bot,horizontal với thằng Scroolview là xong . Nhìn lại vô màn hình đã xanh lè :)))
<img width="1680" alt="Screenshot 2022-06-20 at 01 17 32" src="https://user-images.githubusercontent.com/107794765/174494963-fd32f76f-61be-474a-a166-85458cccf86a.png">


-------------------------------------------------------------------------------------------------------------------------------------------

# Step 7 Add TableView Cell và kéo full height
<img width="1680" alt="Screenshot 2022-06-20 at 01 22 55" src="https://user-images.githubusercontent.com/107794765/174495174-72ab776b-fd6d-47fe-a36e-f92516845bf3.png">


-------------------------------------------------------------------------------------------------------------------------------------------

# Step 8 Set Landcape Mode 
Để set chế độ ngang cần biết view lớn nhất mà mình set đầu tiên là layout nào. 
Chọn View Lớn nhất nhấn thu hết tất cả layout lại sẽ hiện ra constraint của view lớn đó.
Trong trường hợp này là scrollview được tạo đầu tiên và nó là supperview của các layout còn lại
Khi thu nhỏ 1 View lại, Constraints nào mà gần nó thì đó là những Constraints của nó
<img width="1680" alt="Screenshot 2022-06-20 at 02 14 20" src="https://user-images.githubusercontent.com/107794765/174496978-a47e4d96-3f0a-4c29-8268-969f1869844a.png">


-------------------------------------------------------------------------------------------------------------------------------------------

# Step 9 Set Constraint của imageView và label hoặc những phần tử có trong cell 
Chọn tất cả constraints neo của từng subview trong màn hình dọc và chuyển qua widthC heightR và bỏ installed
<img width="1680" alt="Screenshot 2022-06-20 at 03 24 01" src="https://user-images.githubusercontent.com/107794765/174499271-cbbe137d-9489-4481-a1dc-4cafabac89a3.png">


-------------------------------------------------------------------------------------------------------------------------------------------

# Step 10 Lưu ý : wC hR là cho máy dọc, wR hC là cho máy ngang ->
wC là widthCao -> máy dọc .
wR là widthRộng -> máy ngang
<img width="1680" alt="Screenshot 2022-06-20 at 03 20 06" src="https://user-images.githubusercontent.com/107794765/174498971-a0971c74-55aa-42ec-9873-a0930f6e7af1.png">


-------------------------------------------------------------------------------------------------------------------------------------------



# Step 11 Chỉnh layout lại cho imageview hoặc label
Lưu ý vừa autolayout vừa xem thuộc tính bên màn hình dọc có bị đổi theo hay không
Nếu đổi theo thì check lại các constrainst của màn hình dọc xem đã chuyển về variation wC hR hết chưa
<img width="1680" alt="Screenshot 2022-06-20 at 03 34 37" src="https://user-images.githubusercontent.com/107794765/174499453-2220347e-e5e3-4a55-9f90-bbb0b50f44c6.png">
-------------------------------------------------------------------------------------------------------------------------------------------







