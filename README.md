jpeg_encoder
============

ѹ��bmpͼ����jpg�ļ���
�������ʦΪ�ҵĲ����е�һ��ϵ������׼���� 
http://thecodeway.com/blog/?p=69
Ŀ����Ϊ�˽���jpegѹ���㷨�Ĺ��̣�����û�п����Ż���ֻ������ѧϰ������������ʵ����Ŀ��

ʹ�÷���

	#include "jpeg_encoder.h"
	
	JpegEncoder encoder;
	//������ļ�������24bit��bmp�ļ����ߴ������8�ı���
	encoder.readFromBMP(inputFileName);
	
	//�ڶ���������1~199֮�䣬�����ļ�ѹ���̶ȣ�����Խ��ѹ������ļ����ԽС
	encoder.encodeToJPG(outputFileName, 50);
	