cam=webcam(1);
preview(cam);
img1=snapshot(cam);
imshow(img1);
refgray=rgb2gray(img1);
ref=refgray>240;
for i=1:100
    img=snapshot(cam);
%     figure,imshow(img);
    imggray=rgb2gray(img);
    a=imggray>240;
    b=isequal(ref,a);
    if b==0
        light=1;
    else
        light=0;
    end
    pause(5);
end
    
