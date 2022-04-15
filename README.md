### 运动控制
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
### 拍照
rosrun image_view image_view image:=camera/image_raw
### 相机仿真的内参矩阵
camera:
    camera_matrix: [762.7249337622711, 0.0,      640.5,
                0.0,     762.7249337622711,  360.5,
                0.0,     0.0,      1.0     ]
    dist_coeffs: [0, 0, 0, 0, 0]
### 雷达到相机的外参矩阵
- Translation: [-0.010, 0.000, 0.043]
- Rotation: in Quaternion [0.000, 0.000, 0.000, 1.000]
            in RPY (radian) [0.000, -0.000, 0.000]
            in RPY (degree) [0.000, -0.000, 0.000]

### 相机到雷达的外参矩阵
- Translation: [0.010, -0.000, -0.042]
- Rotation: in Quaternion [0.000, 0.000, 0.000, 1.000]
            in RPY (radian) [0.000, -0.000, 0.000]
            in RPY (degree) [0.000, -0.000, 0.000]




