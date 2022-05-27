# opencv_diary

//顺序很重要，mjpg放最后才行

VideoCapture cap(0);

cap.set(CAP_PROP_FRAME_WIDTH, 640);

cap.set(CAP_PROP_FRAME_HEIGHT , 480);

cap.set(CAP_PROP_FOURCC, CV_FOURCC('M', 'J', 'P', 'G'));
