# 3DP-Notfix
1. 압축 파일은 Delta형 CreatableD3 3D 프린터의 **설정 연습용 파일**입니다. 
 - 이 펌웨어는 Marlin v2.0.1 펌웨어로 만들었고, configuration.h 파일 내용이 수정되지 않은 파일입니다
  
2. 압축 파일은 Marlin 2.0.1 펌웨어를 **Creatable 3D 프린터에 적합하게 수정**하였습니다.  
 - **(절대로 Marlin 오리지널 파일을 다운 받아 D3프린터에 업로드 하면 않됩니다.)** 

- 아래는 오리진파일에서 수정하거나 추가된 파일항목으로 변경하지 마십시오.   
> configuration.h <설정이 않된 연습용 파일>  
> configuration_adv.h   
> lcd/thermistornames.h   
> lcd/ultralcd.h   
> lcd/HD44780/ultralcd_HD44780.h   
> lcd/HD44780/ultralcd_HD44780.cpp   
> lcd/language/language_en.h   
> lcd/menu/menu_main.cpp   
> lcd/menu/menu_delta_calibrate.cpp   
> module/delta.cpp   
> module/thermistor/thermistor_1407.h add   
> module/thermistor/thermistor_1407.h add   
> pins/pins_RUMBA.h  

3. config 폴더의 파일은 D3 프린터에 맞게 수정된 파일 입니다.

***

4. HEX파일 업로드 방법(오류로 실패할 경우만 해당됨)
 - 만약 설정파일이 오류로 실패할 경우 HEX파일을 다운로드 받아 업로드하면 프린터가 작동합니다.
 - Xloader 사이트에서 다운로더 프로그램을 내려받아 설치 합니다. 
   [XLoader 다운로드](http://www.hobbytronics.co.uk/download/XLoader.zip, "hobbytronics link")
 - 디바이스는 Mega2560
 - 프린터와 연결 후 잡힌 컴포트와 보레이트는 115200 설정후
 - Upload 버튼을 누른다.
