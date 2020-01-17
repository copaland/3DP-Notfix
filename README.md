# 3DP-Notfix
1. 압축 파일은 Delta형 3D 프린터의 설정 연습용 파일이다.(configuration.h) 
 - 이 펌웨어는 Marlin v2.0.1 펌웨어로 만들었고, 설정이 정확하지 않음.
  
2. Marlin 2.0.1 펌웨어를 Creatable 3D 프린터에 적합하게 수정하였습니다.
 - 아래는 수정되거나 추가된 항목입니다. 

configuration.h <연습용 파일>
configuration_adv.h 
lcd/thermistornames.h 
lcd/ultralcd.h 
lcd/HD44780/ultralcd_HD44780.h 
lcd/HD44780/ultralcd_HD44780.cpp 
lcd/language/language_en.h 
lcd/menu/menu_main.cpp 
lcd/menu/menu_delta_calibrate.cpp 
module/delta.cpp 
module/thermistor/thermistor_1407.h add 
module/thermistor/thermistor_1407.h add 
pins/pins_RUMBA.h

3.HEX파일 업로드 방법
 - HEX파일을 다운로드 받아 출력 연습 가능합니다.
 - Xloader 사이트에서 다운로더 프로그램을 내려받아 설치 합니다. 
http://www.hobbytronics.co.uk/download/XLoader.zip
 - 디바이스는 Mega2560
 - 프린터와 연결 후 잡힌 컴포트와 보레이트는 115200 설정후
 - Upload 버튼을 누른다.
