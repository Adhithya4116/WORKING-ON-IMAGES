# WORKING-ON-IMAGES
My submission Instructions for submission

1.The image should be a plant, Tree, flower or building

2.The filename should be username.jpg

3.The image should be Converted to gray scale and HSV

4.Display the H, S and V planes

## PROGRAM
### Name: Adhithya Perumal.D
### Register Number: 212222230007
```
#Convert to Gray Scale and HSV:
import cv2
image = cv2.imread('Screenshot 2024-03-08 092502.png')
grayscale_image = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)
hsv_image = cv2.cvtColor(image, cv2.COLOR_BGR2HSV)

h, s, v = cv2.split(hsv_image)

# Display the H, S, and V planes
cv2.imshow('Hue', h)
cv2.imshow('Saturation', s)
cv2.imshow('Value', v)
cv2.waitKey(0)
cv2.destroyAllWindows()

#Save the Processed Image:
cv2.imwrite('username_gray.jpg', grayscale_image)
cv2.imwrite('username_hsv.jpg', hsv_image)

```

### OUTPUT

![Screenshot 2024-03-14 093717](https://github.com/Adhithya4116/WORKING-ON-IMAGES/assets/118707079/c2b6bbea-5b2d-4a92-a7e3-9264d26624a8)

![Screenshot 2024-03-14 093827](https://github.com/Adhithya4116/WORKING-ON-IMAGES/assets/118707079/f7382baa-508f-41eb-8afe-5192777d10de)

![Screenshot 2024-03-14 093751](https://github.com/Adhithya4116/WORKING-ON-IMAGES/assets/118707079/6362e234-4f6c-4138-b179-e7ee3c3c43cd)

![Screenshot 2024-03-14 094745](https://github.com/Adhithya4116/WORKING-ON-IMAGES/assets/118707079/14472027-718d-4743-ad21-76d1e4f232e9)







